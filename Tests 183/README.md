# Net 183 ((768 x 512) x 2) x 1

Used [RukChessTrainer](https://github.com/Ilya-Ruk/RukChessTrainer), commit [319ab9d2cb3400b84472af4bccd1b9955e4be462](https://github.com/Ilya-Ruk/RukChessTrainer/commit/319ab9d2cb3400b84472af4bccd1b9955e4be462)

## Train and valid data

1. CCRL 40/2 Archive (04.02.2020) - 2165313 games (300475130 fens)
2. CCRL Blitz (29.03.2025) - 1542299 games (214001491 fens)
3. CCRL 40/15 (28.03.2025) - 2065518 games (275777569 fens)

Train positions: 711228770  
Valid positions:  20000000

## Tests (rukchess_111.nnue)

game_001.pgn (tc=15+0.15)

    Score of RukChess 512 vs RukChess 3.0.19 NNUE2: 355 - 210 - 435  [0.573] 1000
    ...      RukChess 512 playing White: 272 - 44 - 184  [0.728] 500
    ...      RukChess 512 playing Black: 83 - 166 - 251  [0.417] 500
    ...      White vs Black: 438 - 127 - 435  [0.655] 1000
    Elo difference: 50.7 +/- 16.2, LOS: 100.0 %, DrawRatio: 43.5 %

game_002.pgn (tc=15+0.15)

    Score of RukChess 512 vs RukChess 3.0.19 NNUE2: 319 - 223 - 458  [0.548] 1000
    ...      RukChess 512 playing White: 248 - 52 - 200  [0.696] 500
    ...      RukChess 512 playing Black: 71 - 171 - 258  [0.400] 500
    ...      White vs Black: 419 - 123 - 458  [0.648] 1000
    Elo difference: 33.5 +/- 15.9, LOS: 100.0 %, DrawRatio: 45.8 %

game_003.pgn (tc=60+0.6)

    Score of RukChess 512 vs RukChess 3.0.19 NNUE2: 349 - 178 - 473  [0.586] 1000
    ...      RukChess 512 playing White: 279 - 25 - 196  [0.754] 500
    ...      RukChess 512 playing Black: 70 - 153 - 277  [0.417] 500
    ...      White vs Black: 432 - 95 - 473  [0.668] 1000
    Elo difference: 60.0 +/- 15.6, LOS: 100.0 %, DrawRatio: 47.3 %

game_004.pgn (tc=60+0.6)

    Score of RukChess 4.1.0 vs RukChess 3.0.19 NNUE2: 338 - 179 - 483  [0.580] 1000
    ...      RukChess 4.1.0 playing White: 271 - 23 - 206  [0.748] 500
    ...      RukChess 4.1.0 playing Black: 67 - 156 - 277  [0.411] 500
    ...      White vs Black: 427 - 90 - 483  [0.668] 1000
    Elo difference: 55.7 +/- 15.5, LOS: 100.0 %, DrawRatio: 48.3 %
