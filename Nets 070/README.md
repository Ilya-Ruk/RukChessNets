# Nets 070 ((768 x 512) x 2) x 1

Used [RukChessTrainer](https://github.com/Ilya-Ruk/RukChessTrainer), commit [04e9b9b9eb18be17d98815887809cb0337fe229a](https://github.com/Ilya-Ruk/RukChessTrainer/commit/04e9b9b9eb18be17d98815887809cb0337fe229a)

## Valid (10%) and train (90%) data - CCRL-404.[2915638].pgn.7z

    Valid positions:  40284592
    Train positions: 362561328
    Total positions: 402845920

## Tests by epoch

game_253.pgn (rukchess_100.nnue)

    Score of RukChess 3.0.5 NNUE2 vs RukChess 3.0.5 Toga: 779 - 118 - 103  [0.831] 1000
    ...      RukChess 3.0.5 NNUE2 playing White: 389 - 66 - 45  [0.823] 500
    ...      RukChess 3.0.5 NNUE2 playing Black: 390 - 52 - 58  [0.838] 500
    ...      White vs Black: 441 - 456 - 103  [0.492] 1000
    Elo difference: 276.1 +/- 26.0, LOS: 100.0 %, DrawRatio: 10.3 %

game_254.pgn (rukchess_080.nnue)

    Score of RukChess 3.0.5 NNUE2 vs RukChess 3.0.5 Toga: 780 - 121 - 99  [0.830] 1000
    ...      RukChess 3.0.5 NNUE2 playing White: 386 - 66 - 48  [0.820] 500
    ...      RukChess 3.0.5 NNUE2 playing Black: 394 - 55 - 51  [0.839] 500
    ...      White vs Black: 441 - 460 - 99  [0.490] 1000
    Elo difference: 274.8 +/- 26.1, LOS: 100.0 %, DrawRatio: 9.9 %

game_255.pgn (rukchess_120.nnue)

    Score of RukChess 3.0.5 NNUE2 vs RukChess 3.0.5 Toga: 790 - 104 - 106  [0.843] 1000
    ...      RukChess 3.0.5 NNUE2 playing White: 394 - 57 - 49  [0.837] 500
    ...      RukChess 3.0.5 NNUE2 playing Black: 396 - 47 - 57  [0.849] 500
    ...      White vs Black: 441 - 453 - 106  [0.494] 1000
    Elo difference: 292.0 +/- 26.6, LOS: 100.0 %, DrawRatio: 10.6 %

game_256.pgn (rukchess_140.nnue)

    Score of RukChess 3.0.5 NNUE2 vs RukChess 3.0.5 Toga: 749 - 132 - 119  [0.808] 1000
    ...      RukChess 3.0.5 NNUE2 playing White: 363 - 75 - 62  [0.788] 500
    ...      RukChess 3.0.5 NNUE2 playing Black: 386 - 57 - 57  [0.829] 500
    ...      White vs Black: 420 - 461 - 119  [0.479] 1000
    Elo difference: 250.2 +/- 24.6, LOS: 100.0 %, DrawRatio: 11.9 %

**Choosing a neural network with the maximum increase in ELO: epoch 120 (+292 ELO)**
