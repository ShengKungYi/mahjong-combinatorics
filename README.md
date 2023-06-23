# Mahjong Combinatorics

A miscellaneous collection of scripts, notebooks, and data files related to combinatorics and probabilities in the classic table game of Mahjong.

## Calculation Framework

In order to facilitate calculation of combinations and probabilities, a pre-computed library of hand properties is performed. These properties include how many sets of three tiles are included in a group of tiles (sets being sequences of three consecutive tiles, or triplets of identical tiles), how many incomplete blocks of two (or three) tiles there are, and how many pairs can be formed by the set of hands. Two different types of tables are computed: one for numeric tiles (_suuhai_) which can form sequences, and one for honor tiles (_jihai_) which can only form pairs and triplets. The approach for calculating properties used here follows that which is outlined in [this blog post](http://blog.ezyang.com/2014/04/calculating-shanten-in-mahjong/). Properties are calculated for small groups of three tiles or fewer first, then dynamic programming is used for larger hand sizes by dividing them into splits of two smaller groups, and finding the best split.

Final results can be found in the `shanten_suuhai.csv` and `shanten_jihai.csv` files, with generation code in the `Shanten_Framework.ipynb` notebook.

## Shanten and Winning Hand Probabilities

The `shanten_*` tables are used to calculate the probabilities of winning hands and _shanten_ for increasingly complex variants of Mahjong. A winning hand consists of one to four sets of three tiles (increasing with complexity) and one pair of tiles. (This will be five tiles in a one-set hand, eight tiles in a two-set hand, eleven tiles in a three-set hand, and fourteen tiles in a four-set hand.) Probabilities for winning hands are calculated as the proportion of complete hands out of all possible hands of the given size. Furthermore, mahjong hands are normally scored based on the patterns of tiles in the winning hand; these are calculated for hands with larger numbers of tiles. As for _shanten_, this is a numeric value that indicates the closeness of a hand with one fewer tile (i.e. four tiles in a one-set hand, seven tiles in a two-set hand, etc.) to becoming a complete hand with a new tile. A _shanten_ of 0 indicates that there exists a tile that would make the hand complete; this state is also known as _tenpai_. Increasing _shanten_ values indicate that additional tiles are required in order to bring the hand to a _tenpai_ state.

Note: all of these computations are performed on independent, arbitrary hands. In actual play, player may choose tiles to discard which bring themselves closer to hand completion, as well as use calls on other players' discards to meld completed sets of tiles. The relative rates of occurrence for different hand patterns should not necessarily be taken as representative for how likely or how difficult they will come up in actual play.

A summary of results can be found in `Small_Mahjong_Probabilities.md`, and individual computations for each hand size are performed in the `*Set_Probabilities.ipynb` notebooks.

## Revision Roadmap

- While statistics on complete hands appears to be correct, there appear to be errors in compilation of shanten statistics, on about 0.04% of all possible hands. (See [this page](http://www10.plala.or.jp/rascalhp/mjmath.htm) for reference)
- Add notebooks and standalone docs for full 3- and 4-player mahjong.
