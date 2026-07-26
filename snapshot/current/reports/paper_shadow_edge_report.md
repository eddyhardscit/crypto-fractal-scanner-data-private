# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-26T05:42:24+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **1846**
- Trade Shadow/Research chiusi: **3457**
- Eventi Shadow già presi dai Paper: **1004**
- Eventi Shadow saltati dai Paper: **2453**
- Profili con filtro Paper utile: **5**
- Profili in cui il Paper potrebbe scartare edge: **4**
- Profili con campione ancora insufficiente: **96**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 — madre | 76 | 202 | 36 | 166 | -0,32R | 0,02R | -0,34R | -0,00R | +0,31R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 42 | 170 | 10 | 160 | -0,26R | 0,01R | -0,27R | 0,27R | +0,52R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 26 | 120 | 6 | 114 | -0,72R | 0,05R | -0,76R | -0,13R | +0,58R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 24 | 115 | 12 | 103 | 0,19R | 0,06R | +0,13R | 0,17R | -0,02R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 72 | 111 | 37 | 74 | 0,16R | -0,03R | +0,19R | 0,07R | -0,09R | FILTRO PAPER UTILE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 24 | 93 | 7 | 86 | -0,31R | 0,08R | -0,39R | -0,04R | +0,26R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_TREND | Combo Trend | 34 | 88 | 12 | 76 | -0,24R | 0,10R | -0,35R | -0,12R | +0,12R | SELEZIONE DA RIVEDERE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 29 | 82 | 12 | 70 | -0,55R | 0,10R | -0,65R | -0,33R | +0,22R | SELEZIONE DA RIVEDERE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 32 | 80 | 16 | 64 | 0,14R | 0,24R | -0,10R | 0,51R | +0,37R | NESSUN EDGE CHIARO |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 42 | 76 | 20 | 56 | 0,15R | 0,10R | +0,05R | 0,27R | +0,12R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 40 | 71 | 17 | 54 | -0,04R | -0,03R | -0,01R | 0,09R | +0,13R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 44 | 68 | 25 | 43 | 0,12R | 0,12R | -0,01R | 0,19R | +0,07R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 28 | 68 | 13 | 55 | 0,28R | 0,30R | -0,02R | 0,19R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 46 | 67 | 25 | 42 | 0,12R | -0,12R | +0,24R | 0,02R | -0,11R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 47 | 66 | 27 | 39 | 0,13R | -0,11R | +0,24R | 0,00R | -0,13R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 25 | 66 | 14 | 52 | 0,40R | 0,26R | +0,14R | 0,46R | +0,07R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 41 | 63 | 15 | 48 | 0,52R | -0,29R | +0,82R | 0,01R | -0,51R | FILTRO PAPER UTILE |
| MAIN | Principale 4H | 19 | 58 | 15 | 43 | -0,03R | 0,09R | -0,12R | -0,10R | -0,07R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 38 | 57 | 23 | 34 | 0,11R | 0,04R | +0,06R | 0,21R | +0,10R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 14 | 57 | 6 | 51 | -0,06R | -0,12R | +0,06R | -0,24R | -0,18R | CAMPIONE INSUFFICIENTE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 23 | 52 | 16 | 36 | 0,70R | -0,38R | +1,08R | 0,40R | -0,29R | FILTRO PAPER UTILE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 32 | 51 | 20 | 31 | 0,10R | 0,29R | -0,19R | 0,15R | +0,05R | PAPER SCARTA EDGE |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 42 | 49 | 26 | 23 | 0,26R | 0,14R | +0,12R | 0,17R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_4H_WIDE | Ampia 4H | 17 | 49 | 11 | 38 | 0,01R | 0,08R | -0,06R | -0,06R | -0,07R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 29 | 48 | 15 | 33 | -0,39R | 0,04R | -0,42R | -0,20R | +0,19R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 39 | 47 | 23 | 24 | 0,22R | 0,43R | -0,21R | 0,08R | -0,14R | PAPER SCARTA EDGE |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 34 | 43 | 27 | 16 | 0,03R | 0,02R | +0,01R | -0,07R | -0,10R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 25% a 3R | 19 | 38 | 6 | 32 | -0,41R | -0,32R | -0,10R | 0,03R | +0,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 12 | 38 | 5 | 33 | -0,28R | -0,34R | +0,06R | -0,11R | +0,17R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 32 | 35 | 18 | 17 | -0,09R | -0,16R | +0,07R | -0,04R | +0,04R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 8 | 32 | 4 | 28 | 0,45R | -0,19R | +0,64R | 0,12R | -0,33R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 28 | 28 | 22 | 6 | -0,03R | 0,20R | -0,23R | 0,00R | +0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 27 | 28 | 22 | 6 | -0,03R | 0,20R | -0,23R | 0,02R | +0,05R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 10 | 28 | 9 | 19 | -0,07R | -0,75R | +0,68R | -0,04R | +0,03R | SELEZIONE POSITIVA |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 10 | 28 | 6 | 22 | -0,10R | -0,08R | -0,02R | 0,13R | +0,22R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 16 | 28 | 6 | 22 | -0,53R | 0,13R | -0,66R | -0,23R | +0,30R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 41 | 27 | 8 | 19 | -1,04R | 0,07R | -1,11R | -0,11R | +0,93R | SELEZIONE DA RIVEDERE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 7 | 27 | 3 | 24 | -1,08R | -0,16R | -0,93R | -0,21R | +0,87R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 7 | 27 | 3 | 24 | -1,08R | -0,16R | -0,93R | -0,21R | +0,87R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 17 | 26 | 12 | 14 | -0,54R | 0,03R | -0,57R | -0,28R | +0,26R | SELEZIONE DA RIVEDERE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 7 | 25 | 4 | 21 | 0,52R | -0,11R | +0,64R | 0,49R | -0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 23 | 23 | 10 | 13 | -0,08R | -0,04R | -0,04R | -0,17R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 10 | 23 | 6 | 17 | -0,52R | 0,11R | -0,63R | 0,11R | +0,62R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 8 | 21 | 5 | 16 | 0,54R | -0,29R | +0,83R | -0,29R | -0,83R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_MFE_V1 | Top 5 + BTC — Guard + BTC≤3 + MFE | 20 | 20 | 6 | 14 | 0,59R | -0,11R | +0,69R | -0,08R | -0,67R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_V1 | Top 5 + BTC — Guard + BTC≤3 | 7 | 20 | 2 | 18 | 0,59R | 0,05R | +0,54R | 0,62R | +0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 11 | 20 | 6 | 14 | 1,61R | -0,47R | +2,08R | 0,55R | -1,06R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 9 | 20 | 4 | 16 | 0,93R | -0,04R | +0,98R | 0,65R | -0,29R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 15 | 17 | 13 | 4 | -0,08R | 0,23R | -0,32R | 0,09R | +0,18R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_V1 | Combo Adaptive — Quality7 | 13 | 16 | 9 | 7 | 0,28R | -0,17R | +0,45R | 0,08R | -0,20R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 13 | 15 | 9 | 6 | 0,20R | 0,61R | -0,41R | 0,09R | -0,11R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 12 | 12 | 12 | 0 | -0,27R | 0,00R | -0,27R | 0,16R | +0,43R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 4 | 12 | 4 | 8 | -0,27R | 0,15R | -0,42R | -0,34R | -0,07R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 5 | 10 | 5 | 5 | -0,02R | -1,06R | +1,04R | -0,46R | -0,44R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 9 | 9 | 8 | 1 | -0,15R | -1,40R | +1,25R | -0,62R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_NOHIGH_CAP75_SHORT_ONLY_V1 | FAST NoHigh <7,5 · SHORT only | 6 | 6 | 3 | 3 | -0,23R | 1,47R | -1,70R | 0,58R | +0,80R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 6 | 6 | 3 | 3 | -0,11R | -0,11R | +0,00R | -0,55R | -0,45R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_PARTIAL_1R_V1 | Combo Adaptive — Quality7 + Regime + parziale 1R | 5 | 5 | 5 | 0 | -0,46R | 0,00R | -0,46R | -0,33R | +0,13R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_V1 | Combo Adaptive — Quality7 + Regime | 5 | 5 | 5 | 0 | -0,46R | 0,00R | -0,46R | -0,58R | -0,12R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 4 | 5 | 2 | 3 | 0,39R | -1,11R | +1,50R | -0,46R | -0,85R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 6 | 5 | 2 | 3 | 0,39R | -1,11R | +1,50R | -0,55R | -0,94R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_BOTTOM10_SHORT | Scanner Bottom10 Short | 5 | 5 | 2 | 3 | -1,10R | -1,11R | +0,01R | -1,12R | -0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_BOTTOM15_SHORT | Scanner Bottom15 Short | 5 | 5 | 2 | 3 | -1,10R | -1,11R | +0,01R | -1,12R | -0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_BOTTOM20_SHORT | Scanner Bottom20 Short | 5 | 5 | 2 | 3 | -1,10R | -1,11R | +0,01R | -1,12R | -0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 5 | 5 | 4 | 1 | 0,39R | -1,11R | +1,50R | -0,09R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 4 | 4 | 4 | 0 | -1,12R | 0,00R | -1,12R | -0,09R | +1,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 5 | 4 | 4 | 0 | -0,36R | 0,00R | -0,36R | -0,13R | +0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 8 | 4 | 3 | 1 | 0,89R | -1,09R | +1,98R | 0,23R | -0,66R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 4 | 4 | 4 | 0 | -0,37R | 0,00R | -0,37R | -0,36R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 10 | 4 | 2 | 2 | 0,16R | 0,66R | -0,50R | -0,42R | -0,58R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_NO_ESPORTS_MFE_LOCK_TP_R200_6b7c560f | n/a | 0 | 3 | 0 | 3 | 0,00R | 0,96R | -0,96R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_BALANCED_V3_LONG_ONLY_V1 | Bilanciata V3 · LONG only | 4 | 3 | 2 | 1 | -1,06R | 1,96R | -3,02R | -0,07R | +0,99R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 3 | 3 | 3 | 0 | -1,11R | 0,00R | -1,11R | 0,09R | +1,20R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 4 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | -0,01R | +0,11R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP10_LONG | Scanner Top10 Long | 4 | 3 | 2 | 1 | 1,97R | -1,02R | +2,98R | 0,89R | -1,07R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP15_LONG | Scanner Top15 Long | 4 | 3 | 2 | 1 | 1,97R | -1,02R | +2,98R | 0,89R | -1,07R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP20_LONG | Scanner Top20 Long | 4 | 3 | 2 | 1 | 1,97R | -1,02R | +2,98R | 0,89R | -1,07R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 3 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | 0,61R | +0,73R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_CAP75_V1_TP_R200_86882aa9 | n/a | 0 | 2 | 0 | 2 | 0,00R | 0,46R | -0,46R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_L_TP_R200_903364ad | n/a | 0 | 2 | 0 | 2 | 0,00R | 0,46R | -0,46R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V_TP_R200_051501d0 | n/a | 0 | 2 | 0 | 2 | 0,00R | 0,46R | -0,46R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_NOHIGH_V1_TP_R200_8346046b | n/a | 0 | 2 | 0 | 2 | 0,00R | -1,04R | +1,04R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_NO_ESPORTS_LONG_ONL_TP_R200_7bbb9481 | n/a | 0 | 2 | 0 | 2 | 0,00R | 1,94R | -1,94R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_NO_ESPORTS_V1_TP_R200_68f866e1 | n/a | 0 | 2 | 0 | 2 | 0,00R | -1,04R | +1,04R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_TP_R200_3ee5afb4 | n/a | 0 | 2 | 0 | 2 | 0,00R | -1,04R | +1,04R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 2 | 2 | 2 | 0 | 1,37R | 0,00R | +1,37R | 1,00R | -0,37R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_BOLLINGER_1H | Doge Bollinger 1H | 2 | 2 | 1 | 1 | -1,13R | -1,11R | -0,02R | -1,11R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_BOTTOM5_SHORT_MFE_TRAIL_V1 | Scanner Bottom5 Short Mfe Trail V1 | 4 | 2 | 2 | 0 | -1,10R | 0,00R | -1,10R | -0,65R | +0,45R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_BOTTOM5_SHORT_PROFIT_LOCK_V1 | Scanner Bottom5 Short Profit Lock V1 | 4 | 2 | 2 | 0 | -1,10R | 0,00R | -1,10R | -0,76R | +0,35R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 4 | 2 | 2 | 0 | -1,13R | 0,00R | -1,13R | -0,49R | +0,64R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_LONG_ONLY_V1_TP_R200_751e55c4 | n/a | 0 | 1 | 0 | 1 | 0,00R | -1,06R | +1,06R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_4H | Btc Adaptive 4H | 1 | 1 | 1 | 0 | -1,07R | 0,00R | -1,07R | -1,01R | +0,06R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_4H | Btc Bollinger 4H | 1 | 1 | 1 | 0 | 1,72R | 0,00R | +1,72R | 1,68R | -0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_4H | Btc Donchian 4H | 1 | 1 | 1 | 0 | -1,07R | 0,00R | -1,07R | -0,99R | +0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_4H | Btc Ema 4H | 1 | 1 | 1 | 0 | -1,07R | 0,00R | -1,07R | -0,99R | +0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_BOLLINGER_1H | Eth Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | 0,31R | +1,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_4H | Eth Ema 4H | 1 | 1 | 1 | 0 | -1,06R | 0,00R | -1,06R | -1,06R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_4H | Sol Adaptive 4H | 1 | 1 | 1 | 0 | -1,05R | 0,00R | -1,05R | -1,04R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_4H | Sol Bollinger 4H | 1 | 1 | 1 | 0 | 1,74R | 0,00R | +1,74R | 1,74R | +0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_4H | Sol Donchian 4H | 1 | 1 | 1 | 0 | -1,06R | 0,00R | -1,06R | -1,04R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_4H | Sol Ema 4H | 1 | 1 | 1 | 0 | -1,06R | 0,00R | -1,06R | -1,04R | +0,02R | CAMPIONE INSUFFICIENTE |
| MAIN_DYNAMIC_ASSET_SELECTOR_V1 | MAIN — Dynamic Asset Selector | 2 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 1,99R | +1,99R | CAMPIONE INSUFFICIENTE |
| MAIN_SIDE_REGIME_GUARD_V1 | MAIN — Side × Regime Guard | 3 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,97R | +0,97R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_BALANCED_LONG_NO_RHV_V1 | Bilanciata 1H — LONG senza Range High Vol | 5 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,17R | +0,17R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_BALANCED_SHORT_TREND_DOWN_STRICT_V1 | Bilanciata 1H — SHORT Trend Down stretto | 1 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,08R | -0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_COST_AWARE_V1 | Rapida score 6–7,5 — Cost Aware | 7 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 1,09R | +1,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_NO_TREND_UP_V1 | Rapida score 6–7,5 — senza Trend Up | 9 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,57R | +0,57R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_RANGE_ONLY_V1 | Rapida score 6–7,5 — Range Only | 8 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,57R | +0,57R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NOHIGH_RANGE_ONLY_V1 | Rapida V3 NoHigh — Range Only | 8 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,68R | +0,68R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NOHIGH_REGIME_GUARD_V1 | Rapida V3 NoHigh — Regime Guard | 9 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,77R | +0,77R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_LONG_ONLY_V1 | Rapida V3 senza ESPORTS — Long Only | 10 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,32R | +0,32R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_MFE_LOCK_V1 | Rapida V3 senza ESPORTS — MFE Lock | 17 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,27R | +0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_STRESS_GUARD_V1 | Rapida V3 senza ESPORTS — Stress Guard | 5 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,42R | +0,42R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_SIDE_REGIME_GUARD_V1 | Combo Adaptive — Side × Regime Guard | 6 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,92R | +0,92R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_TREND_SIDE_REGIME_GUARD_V1 | Combo Trend — Side × Regime Guard | 6 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,72R | +0,72R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_BE_V1 | Master Adaptive GB20 — Breakeven 0,5R | 6 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,38R | +0,38R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_LOSS_CAP_V1 | Master Adaptive GB20 — Loss Cap 0,75R | 5 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,28R | +0,28R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_PARTIAL_V1 | Master Adaptive GB20 — 50% a 0,75R | 4 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,30R | +0,30R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_BOTTOM5_SHORT_CONTINUATION_V1 | Scanner Bottom5 Short Continuation V1 | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 51 | 102 | 44 | 58 | -1,11% | -0,47% | -0,64% | -0,91% | +0,21% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 51 | 102 | 44 | 58 | -2,23% | -0,94% | -1,29% | -1,82% | +0,41% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 33 | 78 | 24 | 54 | -0,00% | -0,87% | +0,87% | -0,35% | -0,35% | SELEZIONE POSITIVA |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 26 | 47 | 24 | 23 | -1,09% | 0,42% | -1,51% | -1,02% | +0,07% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 26 | 47 | 24 | 23 | -2,17% | 0,84% | -3,02% | -2,03% | +0,14% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 19 | 41 | 16 | 25 | 0,45% | 0,16% | +0,28% | 0,14% | -0,30% | SELEZIONE POSITIVA |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 6 | 35 | 6 | 29 | 1,11% | -1,46% | +2,57% | 1,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 6 | 35 | 6 | 29 | 2,22% | -2,92% | +5,14% | 2,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 3 | 33 | 3 | 30 | 2,33% | -1,26% | +3,59% | 2,33% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 7 | 12 | 6 | 6 | -1,40% | -3,90% | +2,50% | -1,76% | -0,36% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 7 | 12 | 6 | 6 | -2,80% | -7,80% | +5,00% | -3,51% | -0,71% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 6 | 12 | 5 | 7 | -3,20% | -2,77% | -0,43% | -3,20% | +0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -7,80% | -7,11% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 59 | 0,00% | 0,00 | -7,80% | -6,31% | ALTA |
| RSI 25 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 21 | 0,00% | 0,00 | -7,80% | -5,76% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 15 | 20,00% | 0,18 | -5,11% | -3,61% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -3,90% | -3,55% | ALTA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 19 | 0,00% | 0,00 | -3,20% | -3,48% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -4,05% | -3,35% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 10 | 20,00% | 0,23 | -4,80% | -3,31% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 59 | 0,00% | 0,00 | -3,90% | -3,15% | ALTA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 10 | 30,00% | 0,31 | -3,76% | -3,07% | MEDIA |
| RSI 25 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 21 | 0,00% | 0,00 | -3,90% | -2,88% | ALTA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 46 | 0,00% | 0,00 | -3,20% | -2,60% | ALTA |
| RSI 20 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 10 | 0,00% | 0,00 | -7,80% | -2,50% | MEDIA |
| RSI 25 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 19 | 0,00% | 0,00 | -3,20% | -2,27% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 18 | 27,78% | 0,36 | -3,63% | -2,14% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 15 | 20,00% | 0,18 | -2,55% | -1,81% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -2,03% | -1,68% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 10 | 20,00% | 0,23 | -2,40% | -1,65% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 10 | 30,00% | 0,31 | -1,88% | -1,53% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 24 | 37,50% | 0,55 | -2,17% | -1,48% | ALTA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,51 | -1,02% | -1,30% | MEDIA |
| RSI 20 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 10 | 0,00% | 0,00 | -3,90% | -1,25% | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 5–6 | 10 | 0,00% | 0,00 | -1,03R | -1,10R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | MEDIA | 10 | 0,00% | 0,00 | -1,03R | -1,10R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,07R | -1,07R | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 18 | 27,78% | 0,36 | -1,82% | -1,07% | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -1,05R | MEDIA |
| Forza relativa 1H V2 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 10 | 10,00% | 0,23 | -0,71R | -1,04R | MEDIA |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 8 | 0,00% | 0,00 | -1,09R | -1,01R | MEDIA |
| Bilanciata 1H V2 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 11 | 9,09% | 0,19 | -0,77R | -0,99R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
