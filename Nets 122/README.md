# Nets 122 ((768 x 512) x 2) x 1

Used [RukChessTrainer](https://github.com/Ilya-Ruk/RukChessTrainer), commit [d16f41954501da29c90d492f69da4f5ee29fa05c](https://github.com/Ilya-Ruk/RukChessTrainer/commit/d16f41954501da29c90d492f69da4f5ee29fa05c)

## Valid (10%) and train (90%) data

Source: CCRL.40-2.Archive.[2165313].pgn.7z (04.02.2020) + CCRL-404.[1036964].pgn.7z (03.12.2023)

Valid positions:  44291201 (10%) - games_valid.fen
Train positions: 398620803 (90%) - games_train.fen
Total positions: 442912004

## Train the network

c:\Train>trainer.exe -t games_train.fen -v games_valid.fen

No net specified, generating a random net...
No net specified, generating a random net...DONE

Loading valid data from games_valid.fen...
Loaded positions:   44291201
Loading valid data from games_valid.fen...DONE

Loading train data from games_train.fen...
Loaded positions:  398620803
Loading train data from games_train.fen...DONE

Valid error: 0.10963880

Epoch:   1 Valid error: 0.07326476 (-0.03637404) Time: 607 sec Speed:  655791 pos/sec
Epoch:   2 Valid error: 0.07147934 (-0.00178542) Time: 506 sec Speed:  787115 pos/sec
Epoch:   3 Valid error: 0.07091432 (-0.00056502) Time: 511 sec Speed:  780040 pos/sec
Epoch:   4 Valid error: 0.07062422 (-0.00029010) Time: 526 sec Speed:  756632 pos/sec
Epoch:   5 Valid error: 0.07042279 (-0.00020143) Time: 497 sec Speed:  800948 pos/sec
Epoch:   6 Valid error: 0.07024209 (-0.00018070) Time: 493 sec Speed:  806993 pos/sec
Epoch:   7 Valid error: 0.07014363 (-0.00009846) Time: 494 sec Speed:  805600 pos/sec
Epoch:   8 Valid error: 0.06999976 (-0.00014387) Time: 494 sec Speed:  806495 pos/sec
Epoch:   9 Valid error: 0.06986973 (-0.00013003) Time: 493 sec Speed:  807615 pos/sec
Epoch:  10 Valid error: 0.06981573 (-0.00005400) Time: 495 sec Speed:  804864 pos/sec
Epoch:  11 Valid error: 0.06972246 (-0.00009327) Time: 496 sec Speed:  803292 pos/sec
Epoch:  12 Valid error: 0.06964839 (-0.00007407) Time: 493 sec Speed:  807854 pos/sec
Epoch:  13 Valid error: 0.06957377 (-0.00007462) Time: 493 sec Speed:  808098 pos/sec
Epoch:  14 Valid error: 0.06952880 (-0.00004496) Time: 495 sec Speed:  804028 pos/sec
Epoch:  15 Valid error: 0.06949802 (-0.00003078) Time: 493 sec Speed:  807944 pos/sec
Epoch:  16 Valid error: 0.06945347 (-0.00004455) Time: 493 sec Speed:  807692 pos/sec
Epoch:  17 Valid error: 0.06941397 (-0.00003950) Time: 494 sec Speed:  806805 pos/sec
Epoch:  18 Valid error: 0.06938215 (-0.00003181) Time: 507 sec Speed:  785522 pos/sec
Epoch:  19 Valid error: 0.06934708 (-0.00003508) Time: 505 sec Speed:  788344 pos/sec
Epoch:  20 Valid error: 0.06934275 (-0.00000432) Time: 493 sec Speed:  808129 pos/sec
Epoch:  21 Valid error: 0.06932268 (-0.00002008) Time: 493 sec Speed:  808368 pos/sec
Epoch:  22 Valid error: 0.06928989 (-0.00003279) Time: 504 sec Speed:  790532 pos/sec
Epoch:  23 Valid error: 0.06926867 (-0.00002122) Time: 492 sec Speed:  809290 pos/sec
Epoch:  24 Valid error: 0.06926706 (-0.00000160) Time: 491 sec Speed:  810480 pos/sec
Epoch:  25 Valid error: 0.06921252 (-0.00005455) Time: 492 sec Speed:  810126 pos/sec
Epoch:  26 Valid error: 0.06924434 (+0.00003182) Time: 499 sec Speed:  797350 pos/sec
Epoch:  27 Valid error: 0.06917787 (-0.00006647) Time: 498 sec Speed:  800072 pos/sec
Epoch:  28 Valid error: 0.06920388 (+0.00002600) Time: 491 sec Speed:  810337 pos/sec
Epoch:  29 Valid error: 0.06914938 (-0.00005449) Time: 492 sec Speed:  809325 pos/sec
Epoch:  30 Valid error: 0.06915846 (+0.00000908) Time: 492 sec Speed:  808730 pos/sec
Epoch:  31 Valid error: 0.06916068 (+0.00000221) Time: 491 sec Speed:  810434 pos/sec
Epoch:  32 Valid error: 0.06912228 (-0.00003839) Time: 492 sec Speed:  808563 pos/sec
Epoch:  33 Valid error: 0.06909043 (-0.00003185) Time: 500 sec Speed:  797122 pos/sec
Epoch:  34 Valid error: 0.06908686 (-0.00000357) Time: 496 sec Speed:  803273 pos/sec
Epoch:  35 Valid error: 0.06912844 (+0.00004157) Time: 491 sec Speed:  810492 pos/sec
Epoch:  36 Valid error: 0.06908146 (-0.00004698) Time: 493 sec Speed:  808393 pos/sec
Epoch:  37 Valid error: 0.06908376 (+0.00000229) Time: 491 sec Speed:  810314 pos/sec
Epoch:  38 Valid error: 0.06904873 (-0.00003503) Time: 492 sec Speed:  808808 pos/sec
Epoch:  39 Valid error: 0.06901674 (-0.00003199) Time: 493 sec Speed:  807013 pos/sec
Epoch:  40 Valid error: 0.06902810 (+0.00001136) Time: 507 sec Speed:  784704 pos/sec
Epoch:  41 Valid error: 0.06901556 (-0.00001255) Time: 547 sec Speed:  728134 pos/sec
Epoch:  42 Valid error: 0.06902398 (+0.00000843) Time: 879 sec Speed:  453394 pos/sec
Epoch:  43 Valid error: 0.06900956 (-0.00001442) Time: 493 sec Speed:  807018 pos/sec
Epoch:  44 Valid error: 0.06898835 (-0.00002121) Time: 494 sec Speed:  806789 pos/sec
Epoch:  45 Valid error: 0.06898583 (-0.00000252) Time: 493 sec Speed:  807716 pos/sec
Epoch:  46 Valid error: 0.06898440 (-0.00000142) Time: 493 sec Speed:  807985 pos/sec
Epoch:  47 Valid error: 0.06896885 (-0.00001555) Time: 493 sec Speed:  807188 pos/sec
Epoch:  48 Valid error: 0.06897556 (+0.00000671) Time: 501 sec Speed:  794168 pos/sec
Epoch:  49 Valid error: 0.06895989 (-0.00001567) Time: 501 sec Speed:  795225 pos/sec
Epoch:  50 Valid error: 0.06894147 (-0.00001843) Time: 492 sec Speed:  809082 pos/sec
Epoch:  51 Valid error: 0.06894337 (+0.00000190) Time: 493 sec Speed:  808235 pos/sec
Epoch:  52 Valid error: 0.06893408 (-0.00000929) Time: 492 sec Speed:  808914 pos/sec
Epoch:  53 Valid error: 0.06891409 (-0.00001998) Time: 492 sec Speed:  808635 pos/sec
Epoch:  54 Valid error: 0.06890306 (-0.00001103) Time: 502 sec Speed:  793999 pos/sec
Epoch:  55 Valid error: 0.06890583 (+0.00000277) Time: 498 sec Speed:  798940 pos/sec
Epoch:  56 Valid error: 0.06890904 (+0.00000321) Time: 497 sec Speed:  801714 pos/sec
Epoch:  57 Valid error: 0.06890925 (+0.00000021) Time: 503 sec Speed:  791865 pos/sec
Epoch:  58 Valid error: 0.06887081 (-0.00003844) Time: 499 sec Speed:  798145 pos/sec
Epoch:  59 Valid error: 0.06890394 (+0.00003313) Time: 492 sec Speed:  808945 pos/sec
Epoch:  60 Valid error: 0.06890706 (+0.00000312) Time: 493 sec Speed:  808356 pos/sec
Epoch:  61 Valid error: 0.06889467 (-0.00001239) Time: 493 sec Speed:  807955 pos/sec
Epoch:  62 Valid error: 0.06885640 (-0.00003827) Time: 493 sec Speed:  807922 pos/sec
Epoch:  63 Valid error: 0.06893337 (+0.00007696) Time: 495 sec Speed:  804342 pos/sec
Epoch:  64 Valid error: 0.06889438 (-0.00003899) Time: 494 sec Speed:  805591 pos/sec
Epoch:  65 Valid error: 0.06888877 (-0.00000561) Time: 493 sec Speed:  808193 pos/sec
Epoch:  66 Valid error: 0.06885818 (-0.00003059) Time: 492 sec Speed:  808891 pos/sec
Epoch:  67 Valid error: 0.06885075 (-0.00000743) Time: 493 sec Speed:  806939 pos/sec
Epoch:  68 Valid error: 0.06888893 (+0.00003818) Time: 492 sec Speed:  808717 pos/sec
Epoch:  69 Valid error: 0.06884450 (-0.00004444) Time: 493 sec Speed:  807998 pos/sec
Epoch:  70 Valid error: 0.06887147 (+0.00002697) Time: 494 sec Speed:  806251 pos/sec
Epoch:  71 Valid error: 0.06885560 (-0.00001587) Time: 494 sec Speed:  805439 pos/sec
Epoch:  72 Valid error: 0.06887136 (+0.00001576) Time: 493 sec Speed:  808084 pos/sec
Epoch:  73 Valid error: 0.06885027 (-0.00002109) Time: 494 sec Speed:  806778 pos/sec
Epoch:  74 Valid error: 0.06883866 (-0.00001161) Time: 495 sec Speed:  804992 pos/sec
Epoch:  75 Valid error: 0.06883848 (-0.00000018) Time: 494 sec Speed:  806445 pos/sec
Epoch:  76 Valid error: 0.06881837 (-0.00002012) Time: 493 sec Speed:  808350 pos/sec
Epoch:  77 Valid error: 0.06883493 (+0.00001656) Time: 492 sec Speed:  809193 pos/sec
Epoch:  78 Valid error: 0.06881929 (-0.00001564) Time: 493 sec Speed:  808483 pos/sec
Epoch:  79 Valid error: 0.06879158 (-0.00002772) Time: 493 sec Speed:  808561 pos/sec
Epoch:  80 Valid error: 0.06882773 (+0.00003616) Time: 493 sec Speed:  807274 pos/sec
Epoch:  81 Valid error: 0.06881115 (-0.00001658) Time: 492 sec Speed:  809065 pos/sec
Epoch:  82 Valid error: 0.06881140 (+0.00000025) Time: 493 sec Speed:  808396 pos/sec
Epoch:  83 Valid error: 0.06881436 (+0.00000296) Time: 493 sec Speed:  807579 pos/sec
Epoch:  84 Valid error: 0.06882598 (+0.00001162) Time: 496 sec Speed:  802411 pos/sec
Epoch:  85 Valid error: 0.06879162 (-0.00003436) Time: 501 sec Speed:  795536 pos/sec
Epoch:  86 Valid error: 0.06878845 (-0.00000317) Time: 506 sec Speed:  787234 pos/sec
Epoch:  87 Valid error: 0.06882663 (+0.00003818) Time: 495 sec Speed:  805218 pos/sec
Epoch:  88 Valid error: 0.06879111 (-0.00003552) Time: 492 sec Speed:  808913 pos/sec
Epoch:  89 Valid error: 0.06876146 (-0.00002965) Time: 492 sec Speed:  808771 pos/sec
Epoch:  90 Valid error: 0.06879114 (+0.00002968) Time: 493 sec Speed:  808448 pos/sec
Epoch:  91 Valid error: 0.06876758 (-0.00002355) Time: 493 sec Speed:  808409 pos/sec
Epoch:  92 Valid error: 0.06877765 (+0.00001007) Time: 492 sec Speed:  809372 pos/sec
Epoch:  93 Valid error: 0.06885539 (+0.00007774) Time: 498 sec Speed:  799726 pos/sec
Epoch:  94 Valid error: 0.06879241 (-0.00006298) Time: 501 sec Speed:  794263 pos/sec
Epoch:  95 Valid error: 0.06877937 (-0.00001304) Time: 492 sec Speed:  808680 pos/sec
Epoch:  96 Valid error: 0.06879645 (+0.00001708) Time: 492 sec Speed:  808983 pos/sec
Epoch:  97 Valid error: 0.06877865 (-0.00001780) Time: 492 sec Speed:  808890 pos/sec
Epoch:  98 Valid error: 0.06877749 (-0.00000116) Time: 492 sec Speed:  808775 pos/sec
Epoch:  99 Valid error: 0.06880461 (+0.00002712) Time: 495 sec Speed:  804768 pos/sec
Epoch: 100 Valid error: 0.06873907 (-0.00006554) Time: 494 sec Speed:  806291 pos/sec
Epoch: 101 Valid error: 0.06874451 (+0.00000544) Time: 492 sec Speed:  809310 pos/sec
Epoch: 102 Valid error: 0.06875446 (+0.00000995) Time: 492 sec Speed:  808929 pos/sec
Epoch: 103 Valid error: 0.06877117 (+0.00001671) Time: 492 sec Speed:  809192 pos/sec
Epoch: 104 Valid error: 0.06875291 (-0.00001825) Time: 492 sec Speed:  808911 pos/sec
Epoch: 105 Valid error: 0.06873108 (-0.00002183) Time: 492 sec Speed:  808809 pos/sec
Epoch: 106 Valid error: 0.06871964 (-0.00001144) Time: 492 sec Speed:  809151 pos/sec
Epoch: 107 Valid error: 0.06874748 (+0.00002784) Time: 492 sec Speed:  808684 pos/sec
Epoch: 108 Valid error: 0.06873573 (-0.00001175) Time: 492 sec Speed:  809280 pos/sec
Epoch: 109 Valid error: 0.06876009 (+0.00002436) Time: 497 sec Speed:  801757 pos/sec
Epoch: 110 Valid error: 0.06875638 (-0.00000371) Time: 493 sec Speed:  807739 pos/sec
Epoch: 111 Valid error: 0.06876630 (+0.00000992) Time: 492 sec Speed:  809599 pos/sec
Epoch: 112 Valid error: 0.06874347 (-0.00002283) Time: 493 sec Speed:  807880 pos/sec
Epoch: 113 Valid error: 0.06872042 (-0.00002306) Time: 492 sec Speed:  809300 pos/sec
Epoch: 114 Valid error: 0.06873087 (+0.00001045) Time: 492 sec Speed:  809152 pos/sec
Epoch: 115 Valid error: 0.06873330 (+0.00000244) Time: 493 sec Speed:  808438 pos/sec
Epoch: 116 Valid error: 0.06871279 (-0.00002052) Time: 501 sec Speed:  794295 pos/sec
Epoch: 117 Valid error: 0.06873167 (+0.00001888) Time: 500 sec Speed:  795852 pos/sec
Epoch: 118 Valid error: 0.06881465 (+0.00008298) Time: 494 sec Speed:  806814 pos/sec
Epoch: 119 Valid error: 0.06872045 (-0.00009420) Time: 493 sec Speed:  807682 pos/sec
Epoch: 120 Valid error: 0.06873129 (+0.00001083) Time: 493 sec Speed:  808430 pos/sec
Epoch: 121 Valid error: 0.06872538 (-0.00000591) Time: 493 sec Speed:  807042 pos/sec
Epoch: 122 Valid error: 0.06871124 (-0.00001414) Time: 495 sec Speed:  804865 pos/sec
Epoch: 123 Valid error: 0.06868328 (-0.00002795) Time: 492 sec Speed:  808722 pos/sec
Epoch: 124 Valid error: 0.06871869 (+0.00003541) Time: 514 sec Speed:  774101 pos/sec
Epoch: 125 Valid error: 0.06871703 (-0.00000166) Time: 846 sec Speed:  470855 pos/sec

## Valid error by epoch

![Valid error by epoch](../Tests%20122/ValidError.jpg)

## Tests by epoch

game_001.pgn (rukchess_039.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 102 - 11 - 17  [0.850] 130
...      RukChess 3.0.18 NNUE2 playing White: 51 - 6 - 8  [0.846] 65
...      RukChess 3.0.18 NNUE2 playing Black: 51 - 5 - 9  [0.854] 65
...      White vs Black: 56 - 57 - 17  [0.496] 130
Elo difference: 301.3 +/- 74.8, LOS: 100.0 %, DrawRatio: 13.1 %

game_002.pgn (rukchess_122.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 51 - 54 - 5  [0.486] 110
...      RukChess 3.0.18 NNUE2 playing White: 26 - 26 - 3  [0.500] 55
...      RukChess 3.0.18 NNUE2 playing Black: 25 - 28 - 2  [0.473] 55
...      White vs Black: 54 - 51 - 5  [0.514] 110
Elo difference: -9.5 +/- 64.1, LOS: 38.5 %, DrawRatio: 4.5 %

game_003.pgn (rukchess_075.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 781 - 109 - 110  [0.836] 1000
...      RukChess 3.0.18 NNUE2 playing White: 376 - 66 - 58  [0.810] 500
...      RukChess 3.0.18 NNUE2 playing Black: 405 - 43 - 52  [0.862] 500
...      White vs Black: 419 - 471 - 110  [0.474] 1000
Elo difference: 282.9 +/- 26.1, LOS: 100.0 %, DrawRatio: 11.0 %

game_004.pgn (rukchess_062.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 804 - 84 - 112  [0.860] 1000
...      RukChess 3.0.18 NNUE2 playing White: 392 - 50 - 58  [0.842] 500
...      RukChess 3.0.18 NNUE2 playing Black: 412 - 34 - 54  [0.878] 500
...      White vs Black: 426 - 462 - 112  [0.482] 1000
Elo difference: 315.3 +/- 27.3, LOS: 100.0 %, DrawRatio: 11.2 %

game_005.pgn (rukchess_058.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 793 - 105 - 102  [0.844] 1000
...      RukChess 3.0.18 NNUE2 playing White: 385 - 59 - 56  [0.826] 500
...      RukChess 3.0.18 NNUE2 playing Black: 408 - 46 - 46  [0.862] 500
...      White vs Black: 431 - 467 - 102  [0.482] 1000
Elo difference: 293.3 +/- 26.7, LOS: 100.0 %, DrawRatio: 10.2 %

game_006.pgn (rukchess_069.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 784 - 101 - 115  [0.842] 1000
...      RukChess 3.0.18 NNUE2 playing White: 387 - 51 - 62  [0.836] 500
...      RukChess 3.0.18 NNUE2 playing Black: 397 - 50 - 53  [0.847] 500
...      White vs Black: 437 - 448 - 115  [0.494] 1000
Elo difference: 290.0 +/- 26.2, LOS: 100.0 %, DrawRatio: 11.5 %

game_007.pgn (rukchess_067.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 784 - 106 - 110  [0.839] 1000
...      RukChess 3.0.18 NNUE2 playing White: 380 - 64 - 56  [0.816] 500
...      RukChess 3.0.18 NNUE2 playing Black: 404 - 42 - 54  [0.862] 500
...      White vs Black: 422 - 468 - 110  [0.477] 1000
Elo difference: 286.8 +/- 26.2, LOS: 100.0 %, DrawRatio: 11.0 %

game_008.pgn (rukchess_025.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 768 - 118 - 114  [0.825] 1000
...      RukChess 3.0.18 NNUE2 playing White: 369 - 70 - 61  [0.799] 500
...      RukChess 3.0.18 NNUE2 playing Black: 399 - 48 - 53  [0.851] 500
...      White vs Black: 417 - 469 - 114  [0.474] 1000
Elo difference: 269.4 +/- 25.5, LOS: 100.0 %, DrawRatio: 11.4 %

game_009.pgn (rukchess_065.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 800 - 92 - 108  [0.854] 1000
...      RukChess 3.0.18 NNUE2 playing White: 388 - 51 - 61  [0.837] 500
...      RukChess 3.0.18 NNUE2 playing Black: 412 - 41 - 47  [0.871] 500
...      White vs Black: 429 - 463 - 108  [0.483] 1000
Elo difference: 306.8 +/- 27.1, LOS: 100.0 %, DrawRatio: 10.8 %

game_010.pgn (rukchess_064.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 819 - 86 - 95  [0.867] 1000
...      RukChess 3.0.18 NNUE2 playing White: 406 - 42 - 52  [0.864] 500
...      RukChess 3.0.18 NNUE2 playing Black: 413 - 44 - 43  [0.869] 500
...      White vs Black: 450 - 455 - 95  [0.497] 1000
Elo difference: 324.9 +/- 28.3, LOS: 100.0 %, DrawRatio: 9.5 %

game_011.pgn (rukchess_063.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 775 - 123 - 102  [0.826] 1000
...      RukChess 3.0.18 NNUE2 playing White: 374 - 75 - 51  [0.799] 500
...      RukChess 3.0.18 NNUE2 playing Black: 401 - 48 - 51  [0.853] 500
...      White vs Black: 422 - 476 - 102  [0.473] 1000
Elo difference: 270.6 +/- 25.8, LOS: 100.0 %, DrawRatio: 10.2 %

game_012.pgn (rukchess_050.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 790 - 91 - 119  [0.850] 1000
...      RukChess 3.0.18 NNUE2 playing White: 385 - 51 - 64  [0.834] 500
...      RukChess 3.0.18 NNUE2 playing Black: 405 - 40 - 55  [0.865] 500
...      White vs Black: 425 - 456 - 119  [0.484] 1000
Elo difference: 300.7 +/- 26.5, LOS: 100.0 %, DrawRatio: 11.9 %

game_013.pgn (rukchess_064.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 787 - 90 - 123  [0.849] 1000
...      RukChess 3.0.18 NNUE2 playing White: 386 - 47 - 67  [0.839] 500
...      RukChess 3.0.18 NNUE2 playing Black: 401 - 43 - 56  [0.858] 500
...      White vs Black: 429 - 448 - 123  [0.490] 1000
Elo difference: 299.3 +/- 26.3, LOS: 100.0 %, DrawRatio: 12.3 %

game_014.pgn (rukchess_081.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 806 - 85 - 109  [0.861] 1000
...      RukChess 3.0.18 NNUE2 playing White: 386 - 52 - 62  [0.834] 500
...      RukChess 3.0.18 NNUE2 playing Black: 420 - 33 - 47  [0.887] 500
...      White vs Black: 419 - 472 - 109  [0.473] 1000
Elo difference: 316.1 +/- 27.4, LOS: 100.0 %, DrawRatio: 10.9 %

game_015.pgn (rukchess_089.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 785 - 88 - 127  [0.849] 1000
...      RukChess 3.0.18 NNUE2 playing White: 380 - 53 - 67  [0.827] 500
...      RukChess 3.0.18 NNUE2 playing Black: 405 - 35 - 60  [0.870] 500
...      White vs Black: 415 - 458 - 127  [0.478] 1000
Elo difference: 299.3 +/- 26.1, LOS: 100.0 %, DrawRatio: 12.7 %

game_016.pgn (rukchess_100.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 790 - 104 - 106  [0.843] 1000
...      RukChess 3.0.18 NNUE2 playing White: 387 - 53 - 60  [0.834] 500
...      RukChess 3.0.18 NNUE2 playing Black: 403 - 51 - 46  [0.852] 500
...      White vs Black: 438 - 456 - 106  [0.491] 1000
Elo difference: 292.0 +/- 26.6, LOS: 100.0 %, DrawRatio: 10.6 %

game_017.pgn (rukchess_110.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.18 Toga: 732 - 142 - 126  [0.795] 1000
...      RukChess 3.0.18 NNUE2 playing White: 359 - 82 - 59  [0.777] 500
...      RukChess 3.0.18 NNUE2 playing Black: 373 - 60 - 67  [0.813] 500
...      White vs Black: 419 - 455 - 126  [0.482] 1000
Elo difference: 235.4 +/- 24.0, LOS: 100.0 %, DrawRatio: 12.6 %

## ELO by epoch

![ELO by epoch](../Tests%20122/ELObyEpoch.jpg)

### Hidden weights (epoch 81)

![Hidden weights (epoch 81)](../Tests%20001/HiddenWeights.jpg)

## RukChess 3.0.18 NNUE2 vs RukChess 3.0.15 NNUE2

RukChess 3.0.18 NNUE2 (rukchess_064.nnue) vs RukChess 3.0.15 NNUE2 (#877)

game_019.pgn (tc=120+1)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.15 NNUE2: 281 - 170 - 549  [0.555] 1000
...      RukChess 3.0.18 NNUE2 playing White: 129 - 98 - 273  [0.531] 500
...      RukChess 3.0.18 NNUE2 playing Black: 152 - 72 - 276  [0.580] 500
...      White vs Black: 201 - 250 - 549  [0.475] 1000
Elo difference: 38.7 +/- 14.4, LOS: 100.0 %, DrawRatio: 54.9 %

RukChess 3.0.18 NNUE2 (rukchess_081.nnue) vs RukChess 3.0.15 NNUE2 (#877)

game_020.pgn (tc=120+1)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.15 NNUE2: 300 - 171 - 529  [0.565] 1000
...      RukChess 3.0.18 NNUE2 playing White: 117 - 111 - 272  [0.506] 500
...      RukChess 3.0.18 NNUE2 playing Black: 183 - 60 - 257  [0.623] 500
...      White vs Black: 177 - 294 - 529  [0.442] 1000
Elo difference: 45.1 +/- 14.7, LOS: 100.0 %, DrawRatio: 52.9 %

game_021.pgn (tc=15+0.15)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.15 NNUE2: 356 - 237 - 407  [0.559] 1000
...      RukChess 3.0.18 NNUE2 playing White: 166 - 127 - 207  [0.539] 500
...      RukChess 3.0.18 NNUE2 playing Black: 190 - 110 - 200  [0.580] 500
...      White vs Black: 276 - 317 - 407  [0.479] 1000
Elo difference: 41.5 +/- 16.6, LOS: 100.0 %, DrawRatio: 40.7 %

## SPRT

cutechess-cli.exe
 -each proto=uci tc=15+0.15 option.Hash=128 option.Threads=1
 -engine dir="c:\RukChess 3.0.18" name="RukChess 3.0.18 NNUE2" cmd="RukChess 3.0.18 NNUE2.exe"
 -engine dir="c:\RukChess 3.0.15" name="RukChess 3.0.15 NNUE2" cmd="RukChess 3.0.15 NNUE2.exe"
 -openings file=book.epd format=epd -repeat
 -draw movenumber=40 movecount=10 score=20
 -resign movecount=5 score=1000
 -sprt elo0=0 elo1=10 alpha=0.05 beta=0.05
 -games 2 -rounds 2500
 -concurrency 6
 -ratinginterval 10
 -pgnout game_023.pgn

game_023.pgn (net-7cf57d4dc994.nnue)

Score of RukChess 3.0.18 NNUE2 vs RukChess 3.0.15 NNUE2: 187 - 123 - 255  [0.557] 565
...      RukChess 3.0.18 NNUE2 playing White: 92 - 63 - 128  [0.551] 283
...      RukChess 3.0.18 NNUE2 playing Black: 95 - 60 - 127  [0.562] 282
...      White vs Black: 152 - 158 - 255  [0.495] 565
Elo difference: 39.5 +/- 21.2, LOS: 100.0 %, DrawRatio: 45.1 %

SPRT: llr 2.97 (101.0%), lbound -2.94, ubound 2.94 - H1 was accepted
