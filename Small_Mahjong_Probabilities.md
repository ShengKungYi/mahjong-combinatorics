# Mahjong Hand Combinatorics for Teaching Variants with Reduced Tiles

Note that all hand counts and probabilities in this document assume no calls or set-aside sets.
A collection of four identical tiles can only count as a triplet or pair, with any unused tiles
available for other sets and pairs.

## 1 Suit; 1 Set + 1 Pair

- **Tiles**: 36 tiles from a single numeric suit (e.g. _pinzu_ / dots).
- **Hand**:  A completed hand consists of five tiles: one set of three (sequence or triplet) and one pair.

### Shanten probabilities

There are 58 905 possible hands of four tiles.
A randomly selected hand of four tiles has an average shanten of 0.63, in the following distribution:

| shanten |  count | proportion |
|:-------:|-------:|-----------:|
|    0    | 21 753 | 0.369      |
|    1    | 37 152 | 0.631      |

### Winning hand probabilities

There are 376 992 possible hands of five tiles.
There are  19 200 complete five-tile hands, or 0.051 of all hands (1 in 20).


## 2 Suits; 2 Sets + 1 Pair

- **Tiles**: 72 tiles from two numeric suits (e.g. pinzu and _souzu_ / bamboo).
- **Hand**:  A completed hand consists of eight tiles: two sets of three and one pair.

### Shanten probabilities

There are 1 473 109 704 possible hands of seven tiles.
A randomly selected hand of seven tiles has an average shanten of 1.50, in the following distribution:

| shanten |    count    | proportion |    ratio   |
|:-------:|------------:|-----------:|-----------:|
|    0    |  49 386 696 | 0.033 525  | 1 in 29.8  |
|    1    | 676 727 040 | 0.459 387  | 1 in  2.18 |
|    2    | 708 534 528 | 0.480 979  | 1 in  2.08 |
|    3    |  38 461 440 | 0.026 109  | 1 in 38.3  |

### Winning hand probabilities

There are 11 969 016 345 possible hands of eight tiles.
There are     29 132 488 complete eight-tile hands, or 0.002 434 of all hands (1 in 411).

Among those complete hands, their tile compositions include the following properties:

| pattern                 |    count   | proportion |    ratio    |
|:------------------------|-----------:|-----------:|------------:|
| All Simples             |  9 722 776 | 0.333 743  | 1 in   3.00 |
| Included Terminals      |    402 000 | 0.013 799  | 1 in  72.5  |
|-------------------------|------------|------------|-------------|
| All Sequences           | 24 161 608 | 0.829 370  | 1 in   1.21 |
| All Triplets            |    235 008 | 0.008 067  | 1 in 124    |
|-------------------------|------------|------------|-------------|
| Full Flush              |  3 497 512 | 0.120 055  | 1 in   8.33 |
|-------------------------|------------|------------|-------------|
| Two Identical Sequences |    258 120 | 0.008 860  | 1 in 113    |

Aside: There are 3 965 760 hands that are made up of four unique pairs.
This is 0.000 331 of all hands (1 in 3018), or 1 to 7.35 in ratio vs. standard complete hands.


## 2 Suits + Dragons; 3 Sets + 1 Pair

- **Tiles**: 84 tiles from two numeric suits (pinzu, souzu), plus dragon honors.
- **Hand**:  A completed hand consists of eleven tiles: three sets of three and one pair.

### Shanten probabilities

There are 2 761 025 887 620 possible hands of ten tiles.
A randomly selected hand of ten tiles has an average shanten of 2.27, in the following distribution:

| shanten | count (mil) | proportion |    ratio    |
|:-------:|------------:|-----------:|------------:|
|    0    |    14 024 M | 0.005 079  | 1 in 197    |
|    1    |   369 033 M | 0.133 658  | 1 in   7.48 |
|    2    | 1 367 330 M | 0.495 225  | 1 in   2.02 |
|    3    |   881 904 M | 0.319 412  | 1 in   3.13 |
|    4    |   125 447 M | 0.045 435  | 1 in  22.0  |
|    5    |     3 287 M | 0.001 191  | 1 in 840    |

### Winning hand probabilities

There are 18 574 174 153 080 possible hands of eleven tiles.
There are      6 232 346 696 complete eleven-tile hands, or 0.000 336 of all hands (1 in 2980).

Among those complete hands, their tile compositions include the following properties:

| pattern                     |     count     | proportion |       ratio       |
|:----------------------------|--------------:|-----------:|------------------:|
| All Simples                 |   835 960 840 | 0.134 133  | 1 in         7.46 |
| Included Terminals & Honors |    35 279 040 | 0.005 661  | 1 in       177    |
| Included Terminals          |    13 579 968 | 0.002 179  | 1 in       459    |
| All Terminals & Honors      |        52 224 | 8.380 e-06 | 1 in   119 339    |
| All Terminals               |         1 536 | 2.465 e-07 | 1 in 4 057 517    |
|-----------------------------|---------------|------------|-------------------|
| All Sequences               | 4 274 787 328 | 0.685 903  | 1 in         1.46 |
| All Sequences (no dragons)  | 3 344 259 328 | 0.536 597  | 1 in         1.86 |
| All Triplets                |     9 192 960 | 0.001 475  | 1 in       678    |
|-----------------------------|---------------|------------|-------------------|
| One Dragon Triplet          |   402 121 056 | 0.064 522  | 1 in        15.5  |
| Two Dragon Triplets         |     4 352 256 | 0.000 698  | 1 in     1 432    |
| Small Three Dragons         |       278 784 | 4.473 e-05 | 1 in    22 355    |
| Big Three Dragons           |         6 912 | 1.109 e-06 | 1 in   901 671    |
|-----------------------------|---------------|------------|-------------------|
| Half Flush                  |   161 640 624 | 0.025 936  | 1 in        38.6  |
| Full Flush                  |    94 074 760 | 0.015 095  | 1 in        66.2  |
|-----------------------------|---------------|--------------------------------|
| Two Identical Sequences     |   195 974 976 | 0.031 445  | 1 in        31.8  |
| Full Straight               |    42 467 328 | 0.006 814  | 1 in       147    |


## 3 Suits + Dragons; 4 Sets + 1 Pair

- **Tiles**: 120 tiles from all three numeric suits (pinzu, souzu, manzu / characters), plus dragon honors.
  - Note that wind honors are excluded from the set of tiles in play.
- **Hand**:  A completed hand consists of fourteen tiles: (standard) four sets of three and one pair.
  - Additionally allow irregular hand Seven Pairs, consisting of seven unique pairs of tiles.

### Shanten probabilities

There are 87 586 833 265 107 120 possible hands of thirteen tiles.
A randomly selected hand of thirteen tiles has an average shanten of 3.08, in the following distribution:
| shanten |  count (mil) | proportion |      ratio     |
|:-------:|-------------:|-----------:|---------------:|
|    0    |     27 510 M | 0.000 314  | 1 in  3 184    |
|    1    |  1 648 470 M | 0.018 821  | 1 in     53.1  |
|    2    | 17 819 632 M | 0.203 451  | 1 in      4.92 |
|    3    | 42 600 348 M | 0.486 378  | 1 in      2.06 |
|    4    | 22 661 496 M | 0.258 732  | 1 in      3.87 |
|    5    |  2 778 894 M | 0.031 727  | 1 in     31.5  |
|    6    |     50 483 M | 0.000 576  | 1 in  1 735    |

Fitting to only standard hands, the average shanten is 3.19, in the following distribution:

| shanten |  count (mil) | proportion |      ratio     |
|:-------:|-------------:|-----------:|---------------:|
|    0    |     24 856 M | 0.000 284  | 1 in  3 524    |
|    1    |  1 489 474 M | 0.017 006  | 1 in     58.8  |
|    2    | 15 930 210 M | 0.181 879  | 1 in      5.50 |
|    3    | 40 217 914 M | 0.459 063  | 1 in      2.18 |
|    4    | 24 721 978 M | 0.282 257  | 1 in      3.54 |
|    5    |  4 911 173 M | 0.056 072  | 1 in     17.8  |
|    6    |    297 635 M | 0.003 398  | 1 in    294    |
|    7    |      3 594 M | 4.103 e-05 | 1 in 24 372    |

### Winning hand probabilities

There are 669 413 654 240 461 560 possible hands of fourteen tiles.
There are       9 409 703 768 322 complete fourteen-tile hands, or 1.406 e-05 of all hands (1 in 71 141).
This includes   8 840 918 606 082 standard hands    (1 in    75 718) and
                  568 785 162 240 Seven Pairs hands (1 in 1 176 918; 15.5 to 1 ratio vs. standard hands).

Among those complete hands, their tile compositions include the following properties:

| pattern                       |       count       |        ratio        |
|:------------------------------|------------------:|--------------------:|
| All Simples                   |   931 920 119 892 | 1 in          10.1  |
| Included Terminals & Honors   |     9 744 752 364 | 1 in         966    |
| Included Terminals            |     6 368 641 140 | 1 in       1 478    |
| All Terminals & Honors        |         1 201 536 | 1 in   7 831 396    |
| All Terminals                 |            46 080 | 1 in 204 203 641    |
|-------------------------------|-------------------|---------------------|
| All Sequences                 | 5 604 375 406 650 | 1 in           1.68 |
| All Sequences (no dragons)    | 4 778 454 510 672 | 1 in           1.97 |
| All Triplets                  |     1 094 446 080 | 1 in       8 598    |
|-------------------------------|-------------------|---------------------|
| One Dragon Triplet            |   493 083 162 000 | 1 in          19.1  |
| Two Dragon Triplets           |     5 764 832 064 | 1 in       1 632    |
| Small Three Dragons           |       258 792 192 | 1 in      36 360    |
| Big Three Dragons             |        13 722 624 | 1 in     685 707    |
|-------------------------------|-------------------|---------------------|
| Half Flush                    |     5 462 454 474 | 1 in       1 723    |
| Full Flush                    |     1 336 897 596 | 1 in       7 038    |
|-------------------------------|-------------------|---------------------|
| Two Identical Sequences       |   356 952 436 224 | 1 in          26.4  |
| Twice Two Identical Sequences |     1 119 645 018 | 1 in       8 404    |
|-------------------------------|-------------------|---------------------|
| Full Straight                 |    95 777 832 960 | 1 in          98.2  |
|-------------------------------|-------------------|---------------------|
| Three Similar Sequences       |   178 559 238 144 | 1 in          52.7  |
| Three Similar Triplets        |        88 187 904 | 1 in     106 701    |
