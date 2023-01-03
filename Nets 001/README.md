# Nets 001 ((768 x 512) x 2) x 1
Used [RukChessTrainer](https://github.com/Ilya-Ruk/RukChessTrainer), commit cde6949546edca35b9049b986a231ca0212e9032

    Valid positions:   39351346
    Train positions:  354162112

    Starting Error: [0.11077870]

    Epoch: [#    1], Error: [0.07529054], Delta: [+0.03548817], LR: [0.00500], Speed: [   664765 pos/s], Time: [532s]
    Epoch: [#    2], Error: [0.07363149], Delta: [+0.00165905], LR: [0.00500], Speed: [   666712 pos/s], Time: [531s]
    Epoch: [#    3], Error: [0.07272401], Delta: [+0.00090748], LR: [0.00500], Speed: [   658063 pos/s], Time: [538s]
    ...
    Epoch: [#   30], Error: [0.07056406], Delta: [+0.00002952], LR: [0.00500], Speed: [   665461 pos/s], Time: [532s]
    ...
    Epoch: [#   40], Error: [0.07039113], Delta: [+0.00003380], LR: [0.00500], Speed: [   661991 pos/s], Time: [534s]
    ...
    Epoch: [#   50], Error: [0.07025012], Delta: [+0.00007295], LR: [0.00500], Speed: [   665987 pos/s], Time: [531s]
    ...
    Epoch: [#  100], Error: [0.07001872], Delta: [-0.00002374], LR: [0.00500], Speed: [   660850 pos/s], Time: [535s]
    ...
    Epoch: [#  117], Error: [0.06996010], Delta: [-0.00002921], LR: [0.00500], Speed: [   656156 pos/s], Time: [539s]

## Tests by epoch

game_001.pgn (epoch 50)

    Score of RukChess 3.0 NNUE2 vs RukChess 3.0 Toga: 755 - 117 - 128  [0.819] 1000
    ...      RukChess 3.0 NNUE2 playing White: 363 - 65 - 72  [0.798] 500
    ...      RukChess 3.0 NNUE2 playing Black: 392 - 52 - 56  [0.840] 500
    ...      White vs Black: 415 - 457 - 128  [0.479] 1000
    Elo difference: 262.2 +/- 24.8, LOS: 100.0 %, DrawRatio: 12.8 %

game_002.pgn (epoch 100)

    Score of RukChess 3.0 NNUE2 vs RukChess 3.0 Toga: 713 - 143 - 144  [0.785] 1000
    ...      RukChess 3.0 NNUE2 playing White: 349 - 78 - 73  [0.771] 500
    ...      RukChess 3.0 NNUE2 playing Black: 364 - 65 - 71  [0.799] 500
    ...      White vs Black: 414 - 442 - 144  [0.486] 1000
    Elo difference: 225.0 +/- 23.3, LOS: 100.0 %, DrawRatio: 14.4 %

game_003.pgn (epoch 30)

    Score of RukChess 3.0 NNUE2 vs RukChess 3.0 Toga: 774 - 102 - 124  [0.836] 1000
    ...      RukChess 3.0 NNUE2 playing White: 382 - 54 - 64  [0.828] 500
    ...      RukChess 3.0 NNUE2 playing Black: 392 - 48 - 60  [0.844] 500
    ...      White vs Black: 430 - 446 - 124  [0.492] 1000
    Elo difference: 282.9 +/- 25.7, LOS: 100.0 %, DrawRatio: 12.4 %

game_004.pgn (epoch 20)

    Score of RukChess 3.0 NNUE2 vs RukChess 3.0 Toga: 133 - 146 - 31  [0.479] 310
    ...      RukChess 3.0 NNUE2 playing White: 62 - 75 - 18  [0.458] 155
    ...      RukChess 3.0 NNUE2 playing Black: 71 - 71 - 13  [0.500] 155
    ...      White vs Black: 133 - 146 - 31  [0.479] 310
    Elo difference: -14.6 +/- 36.8, LOS: 21.8 %, DrawRatio: 10.0 %

game_005.pgn (epoch 40)

    Score of RukChess 3.0 NNUE2 vs RukChess 3.0 Toga: 781 - 103 - 116  [0.839] 1000
    ...      RukChess 3.0 NNUE2 playing White: 376 - 62 - 62  [0.814] 500
    ...      RukChess 3.0 NNUE2 playing Black: 405 - 41 - 54  [0.864] 500
    ...      White vs Black: 417 - 467 - 116  [0.475] 1000
    Elo difference: 286.8 +/- 26.0, LOS: 100.0 %, DrawRatio: 11.6 %

### ELO gain compared to RukChess 3.0 Toga

![ELO gain compared to RukChess 3.0 Toga](Tests%20001/ELO%20gain%20compared%20to%20RukChess%203.0%20Toga.jpg)

**Choosing a neural network with the maximum increase in ELO: epoch 40 (+287 ELO)**

### Hidden weights (epoch 40)

![Hidden weights (epoch 40)](Tests%20001/Hidden%20weights%20(epoch%2040).jpg)

## Tests with other engines (epoch 40 used)

game_006.pgn (Hakkapeliitta 3.0 x64, 2984 ELO)

    Score of RukChess 3.0 NNUE2 vs Hakkapeliitta 3.0 x64: 664 - 156 - 180  [0.754] 1000
    ...      RukChess 3.0 NNUE2 playing White: 308 - 91 - 101  [0.717] 500
    ...      RukChess 3.0 NNUE2 playing Black: 356 - 65 - 79  [0.791] 500
    ...      White vs Black: 373 - 447 - 180  [0.463] 1000
    Elo difference: 194.6 +/- 21.8, LOS: 100.0 %, DrawRatio: 18.0 %

game_007.pgn (Demolito 2021-10-04, 3166 ELO (2021-04-03))

    Score of RukChess 3.0 NNUE2 vs demolito_pext: 373 - 392 - 235  [0.490] 1000
    ...      RukChess 3.0 NNUE2 playing White: 182 - 204 - 114  [0.478] 500
    ...      RukChess 3.0 NNUE2 playing Black: 191 - 188 - 121  [0.503] 500
    ...      White vs Black: 370 - 395 - 235  [0.487] 1000
    Elo difference: -6.6 +/- 18.8, LOS: 24.6 %, DrawRatio: 23.5 %

game_008.pgn (Xiphos 0.6 BMI2, 3332 ELO)

    Score of RukChess 3.0 NNUE2 vs xiphos-0.6-w64-bmi2: 156 - 596 - 248  [0.280] 1000
    ...      RukChess 3.0 NNUE2 playing White: 70 - 303 - 127  [0.267] 500
    ...      RukChess 3.0 NNUE2 playing Black: 86 - 293 - 121  [0.293] 500
    ...      White vs Black: 363 - 389 - 248  [0.487] 1000
    Elo difference: -164.1 +/- 20.0, LOS: 0.0 %, DrawRatio: 24.8 %

## ELO calculation

1. Hakkapeliitta 3.0 x64: 2984 + 195 = 3179
2. Demolito 2021-10-04:   3166 -   7 = 3159
3. Xiphos 0.6 BMI2:       3332 - 164 = 3168

**Avg. 3169 ELO**
