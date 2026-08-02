# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-08-02T08:38:46+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **3302**
- Trade Shadow/Research chiusi: **10106**
- Eventi Shadow già presi dai Paper: **1580**
- Eventi Shadow saltati dai Paper: **8526**
- Profili con filtro Paper utile: **19**
- Profili in cui il Paper potrebbe scartare edge: **4**
- Profili con campione ancora insufficiente: **74**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 74 | 317 | 19 | 298 | 0,08R | -0,04R | +0,13R | 0,04R | -0,04R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 103 | 291 | 55 | 236 | 0,01R | -0,08R | +0,09R | 0,05R | +0,05R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 72 | 263 | 34 | 229 | -0,06R | -0,12R | +0,06R | 0,12R | +0,18R | NESSUN EDGE CHIARO |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 50 | 250 | 15 | 235 | -0,16R | -0,09R | -0,07R | -0,24R | -0,08R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 79 | 245 | 34 | 211 | 0,28R | -0,16R | +0,44R | -0,02R | -0,30R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 77 | 244 | 43 | 201 | -0,05R | -0,12R | +0,07R | 0,02R | +0,07R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 39 | 243 | 16 | 227 | 0,43R | -0,01R | +0,44R | 0,19R | -0,24R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 50 | 230 | 19 | 211 | -0,29R | 0,04R | -0,33R | -0,28R | +0,01R | SELEZIONE DA RIVEDERE |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 62 | 213 | 33 | 180 | 0,05R | -0,08R | +0,13R | 0,03R | -0,01R | NESSUN EDGE CHIARO |
| Rapida 1H V1 | Rapida 1H V1 — madre | 78 | 208 | 36 | 172 | -0,32R | 0,01R | -0,33R | 0,01R | +0,33R | SELEZIONE DA RIVEDERE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 45 | 204 | 14 | 190 | -0,42R | -0,03R | -0,38R | -0,17R | +0,25R | SELEZIONE DA RIVEDERE |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 68 | 198 | 45 | 153 | -0,08R | -0,02R | -0,06R | 0,05R | +0,13R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_TREND | Combo Trend | 60 | 197 | 17 | 180 | 0,14R | -0,07R | +0,21R | -0,17R | -0,31R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 64 | 195 | 35 | 160 | 0,20R | -0,03R | +0,23R | 0,17R | -0,03R | FILTRO PAPER UTILE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 66 | 186 | 30 | 156 | 0,08R | -0,05R | +0,12R | 0,08R | +0,01R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 41 | 184 | 16 | 168 | 0,39R | -0,08R | +0,47R | -0,23R | -0,62R | FILTRO PAPER UTILE |
| EVO_CAND_SHADOW_1H_FAST_V3_NO_ESPORTS_MFE_LOCK_TP_R200_6b7c560f | n/a | 0 | 170 | 0 | 170 | 0,00R | -0,06R | +0,06R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 75 | 166 | 52 | 114 | 0,01R | -0,01R | +0,02R | 0,09R | +0,08R | NESSUN EDGE CHIARO |
| EVO_CAND_SHADOW_1H_FAST_V3_TP_R200_3ee5afb4 | n/a | 0 | 154 | 0 | 154 | 0,00R | -0,13R | +0,13R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 54 | 151 | 12 | 139 | -0,70R | 0,16R | -0,86R | -0,14R | +0,56R | PAPER SCARTA EDGE |
| EVO_CAND_SHADOW_1H_FAST_V3_NO_ESPORTS_V1_TP_R200_68f866e1 | n/a | 0 | 150 | 0 | 150 | 0,00R | -0,13R | +0,13R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 50 | 141 | 25 | 116 | 0,27R | 0,10R | +0,17R | 0,14R | -0,14R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 50 | 131 | 21 | 110 | 0,33R | 0,14R | +0,19R | -0,14R | -0,47R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_NOHIGH_CAP75_SHORT_ONLY_V1 | FAST NoHigh <7,5 · SHORT only | 28 | 128 | 15 | 113 | -0,01R | -0,01R | +0,00R | 0,19R | +0,20R | NESSUN EDGE CHIARO |
| EVO_CAND_SHADOW_1H_FAST_V3_TP_R250_6b45fc13 | n/a | 0 | 127 | 0 | 127 | 0,00R | -0,27R | +0,27R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 41 | 125 | 24 | 101 | 0,19R | 0,16R | +0,03R | 0,06R | -0,13R | NESSUN EDGE CHIARO |
| MAIN | Principale 4H | 29 | 123 | 22 | 101 | -0,02R | -0,12R | +0,10R | -0,24R | -0,22R | NESSUN EDGE CHIARO |
| EVO_CAND_SHADOW_1H_FAST_V3_NOHIGH_V1_TP_R200_8346046b | n/a | 0 | 122 | 0 | 122 | 0,00R | -0,10R | +0,10R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_CAP75_V1_TP_R200_86882aa9 | n/a | 0 | 121 | 0 | 121 | 0,00R | -0,08R | +0,08R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 56 | 120 | 31 | 89 | -0,06R | 0,05R | -0,10R | -0,21R | -0,16R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 47 | 117 | 26 | 91 | -0,12R | -0,09R | -0,03R | -0,08R | +0,03R | NESSUN EDGE CHIARO |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 41 | 112 | 24 | 88 | 0,16R | 0,07R | +0,09R | 0,14R | -0,02R | NESSUN EDGE CHIARO |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 55 | 112 | 31 | 81 | 0,13R | 0,07R | +0,06R | -0,02R | -0,14R | NESSUN EDGE CHIARO |
| SHADOW_1H_BALANCED_V3_LONG_ONLY_V1 | Bilanciata V3 · LONG only | 22 | 107 | 14 | 93 | -0,49R | -0,13R | -0,36R | -0,07R | +0,42R | SELEZIONE DA RIVEDERE |
| SHADOW_4H_WIDE | Ampia 4H | 25 | 106 | 15 | 91 | 0,06R | -0,18R | +0,24R | -0,10R | -0,16R | FILTRO PAPER UTILE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 38 | 105 | 30 | 75 | 0,57R | -0,46R | +1,03R | 0,25R | -0,32R | FILTRO PAPER UTILE |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 22 | 99 | 11 | 88 | 0,20R | -0,05R | +0,25R | -0,10R | -0,30R | FILTRO PAPER UTILE |
| EVO_CAND_SHADOW_1H_FAST_V3_NOHIGH_V1_TP_R250_c467005a | n/a | 0 | 97 | 0 | 97 | 0,00R | -0,28R | +0,28R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 34 | 97 | 14 | 83 | -0,21R | 0,15R | -0,37R | -0,27R | -0,06R | PAPER SCARTA EDGE |
| EVO_CAND_SHADOW_1H_FAST_V3_CAP75_V1_TP_R250_3b03ece1 | n/a | 0 | 96 | 0 | 96 | 0,00R | -0,24R | +0,24R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 50 | 96 | 41 | 55 | 0,12R | 0,10R | +0,02R | -0,10R | -0,22R | NESSUN EDGE CHIARO |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 19 | 96 | 8 | 88 | -0,06R | -0,05R | -0,01R | -0,26R | -0,21R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 20 | 94 | 9 | 85 | 0,41R | -0,08R | +0,49R | -0,05R | -0,46R | FILTRO PAPER UTILE |
| EVO_CAND_SHADOW_1H_FAST_V3_NOHIGH_REGIME_GUARD_TP_R200_934590ed | n/a | 0 | 91 | 0 | 91 | 0,00R | -0,21R | +0,21R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 19 | 90 | 7 | 83 | 0,09R | -0,06R | +0,15R | -0,26R | -0,35R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 44 | 89 | 33 | 56 | 0,00R | 0,14R | -0,14R | -0,07R | -0,08R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 49 | 88 | 33 | 55 | 0,00R | 0,12R | -0,12R | -0,09R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_BOTTOM5_SHORT_MFE_TRAIL_V1 | Scanner Bottom5 Short Mfe Trail V1 | 19 | 88 | 9 | 79 | 0,14R | -0,15R | +0,29R | 0,00R | -0,14R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 41 | 85 | 19 | 66 | 0,09R | 0,16R | -0,07R | -0,25R | -0,34R | NESSUN EDGE CHIARO |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 21 | 84 | 9 | 75 | 0,06R | -0,07R | +0,13R | -0,19R | -0,25R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_BOTTOM10_SHORT | Scanner Bottom10 Short | 25 | 82 | 11 | 71 | 0,09R | -0,37R | +0,46R | -0,03R | -0,12R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM15_SHORT | Scanner Bottom15 Short | 25 | 82 | 11 | 71 | 0,09R | -0,37R | +0,46R | -0,03R | -0,12R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM20_SHORT | Scanner Bottom20 Short | 25 | 82 | 11 | 71 | 0,09R | -0,37R | +0,46R | -0,03R | -0,12R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 22 | 81 | 12 | 69 | 0,27R | -0,06R | +0,32R | -0,24R | -0,51R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_MFE_V1 | Top 5 + BTC — Guard + BTC≤3 + MFE | 34 | 80 | 13 | 67 | 0,20R | 0,14R | +0,05R | -0,19R | -0,39R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 30 | 77 | 11 | 66 | 0,59R | -0,05R | +0,64R | -0,24R | -0,83R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 24 | 75 | 12 | 63 | 0,02R | 0,08R | -0,07R | -0,34R | -0,36R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 26 | 75 | 9 | 66 | 0,07R | 0,08R | -0,01R | -0,25R | -0,31R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_BOTTOM5_SHORT_PROFIT_LOCK_V1 | Scanner Bottom5 Short Profit Lock V1 | 20 | 74 | 10 | 64 | 0,01R | -0,13R | +0,14R | -0,03R | -0,04R | NESSUN EDGE CHIARO |
| EVO_CAND_SHADOW_1H_FAST_V3_LONG_ONLY_V1_TP_R200_751e55c4 | n/a | 0 | 71 | 0 | 71 | 0,00R | -0,01R | +0,01R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_NO_ESPORTS_LONG_ONL_TP_R200_7bbb9481 | n/a | 0 | 71 | 0 | 71 | 0,00R | 0,07R | -0,07R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_V1 | Top 5 + BTC — Guard + BTC≤3 | 19 | 70 | 8 | 62 | 0,02R | 0,10R | -0,08R | -0,20R | -0,23R | NESSUN EDGE CHIARO |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 27 | 67 | 16 | 51 | -0,23R | -0,07R | -0,16R | -0,49R | -0,26R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 22 | 61 | 16 | 45 | 0,12R | -0,39R | +0,50R | -0,05R | -0,17R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_TOP15_LONG | Scanner Top15 Long | 22 | 61 | 8 | 53 | 0,60R | -0,07R | +0,66R | -0,38R | -0,98R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_TOP20_LONG | Scanner Top20 Long | 22 | 61 | 8 | 53 | 0,60R | -0,07R | +0,66R | -0,38R | -0,98R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_TOP10_LONG | Scanner Top10 Long | 22 | 60 | 8 | 52 | 0,60R | -0,05R | +0,64R | -0,38R | -0,98R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_V1 | Combo Adaptive — Quality7 | 26 | 55 | 15 | 40 | -0,11R | 0,02R | -0,13R | -0,01R | +0,11R | NESSUN EDGE CHIARO |
| EVO_CAND_SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V_TP_R200_051501d0 | n/a | 0 | 52 | 0 | 52 | 0,00R | 0,01R | -0,01R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_L_TP_R200_903364ad | n/a | 0 | 51 | 0 | 51 | 0,00R | -0,01R | +0,01R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_LONG_ONLY_V1_TP_R250_bfc04ed6 | n/a | 0 | 50 | 0 | 50 | 0,00R | -0,16R | +0,16R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 25% a 3R | 42 | 47 | 6 | 41 | -0,41R | -0,16R | -0,25R | 0,03R | +0,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 24 | 47 | 5 | 42 | -0,28R | -0,19R | -0,10R | -0,11R | +0,17R | CAMPIONE INSUFFICIENTE |
| EVO_CAND_SHADOW_1H_FAST_V3_NOHIGH_RANGE_ONLY_V_TP_R200_52488eb5 | n/a | 0 | 45 | 0 | 45 | 0,00R | 0,01R | -0,01R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 20 | 45 | 19 | 26 | -0,06R | 0,05R | -0,11R | -0,17R | -0,11R | NESSUN EDGE CHIARO |
| EVO_CAND_SHADOW_1H_FAST_V3_NO_ESPORTS_STRESS_G_TP_R200_89ab3f19 | n/a | 0 | 43 | 0 | 43 | 0,00R | -0,33R | +0,33R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 25 | 40 | 21 | 19 | 0,18R | 0,25R | -0,07R | -0,05R | -0,22R | NESSUN EDGE CHIARO |
| SHADOW_DONCHIAN_1H_GB20_120R_V1 | Donchian 1H Gb20 120R V1 | 7 | 37 | 5 | 32 | 1,72R | -0,62R | +2,33R | 0,75R | -0,96R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 10 | 29 | 9 | 20 | -0,47R | -0,01R | -0,47R | -0,05R | +0,42R | SELEZIONE DA RIVEDERE |
| Rapida 1H V2 | Rapida 1H V2 | 17 | 24 | 17 | 7 | -0,26R | 0,12R | -0,38R | -0,03R | +0,23R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 12 | 16 | 11 | 5 | -0,09R | -0,65R | +0,55R | -0,39R | -0,29R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_PARTIAL_1R_V1 | Combo Adaptive — Quality7 + Regime + parziale 1R | 11 | 15 | 10 | 5 | -0,35R | 0,30R | -0,65R | -0,14R | +0,21R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_V1 | Combo Adaptive — Quality7 + Regime | 11 | 15 | 10 | 5 | -0,35R | 0,18R | -0,53R | -0,37R | -0,02R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 9 | 14 | 9 | 5 | -0,25R | -1,06R | +0,81R | -0,53R | -0,28R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 10 | 14 | 4 | 10 | 0,39R | -0,57R | +0,96R | 0,19R | -0,20R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 7 | 14 | 4 | 10 | -0,36R | -0,66R | +0,30R | -0,63R | -0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 7 | 12 | 6 | 6 | -0,11R | -0,60R | +0,50R | -0,38R | -0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 8 | 11 | 4 | 7 | -0,36R | -0,59R | +0,23R | -0,69R | -0,33R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 5 | 9 | 5 | 4 | -1,12R | -0,30R | -0,82R | -0,01R | +1,11R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 6 | 9 | 4 | 5 | -0,36R | -0,77R | +0,41R | -0,67R | -0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 4 | 9 | 4 | 5 | -0,37R | -0,21R | -0,16R | 0,57R | +0,94R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 7 | 8 | 5 | 3 | 0,09R | -0,02R | +0,11R | -0,40R | -0,49R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 6 | 7 | 4 | 3 | 0,38R | -1,12R | +1,50R | 0,13R | -0,25R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 5 | 7 | 5 | 2 | -0,52R | -0,23R | -0,29R | -0,51R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 13 | 7 | 3 | 4 | 0,91R | 0,06R | +0,85R | -0,33R | -1,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 5 | 7 | 3 | 4 | -0,68R | 0,50R | -1,17R | -0,12R | +0,56R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 4 | 6 | 4 | 2 | -0,83R | -0,21R | -0,62R | -0,20R | +0,63R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 4 | 6 | 4 | 2 | 1,12R | 0,12R | +1,00R | 0,56R | -0,56R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_BOLLINGER_1H | Doge Bollinger 1H | 4 | 6 | 2 | 4 | -1,13R | 0,43R | -1,56R | -0,49R | +0,64R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_BOLLINGER_1H | Eth Bollinger 1H | 2 | 5 | 2 | 3 | 0,12R | 0,11R | +0,00R | -0,40R | -0,52R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_4H | Btc Donchian 4H | 2 | 2 | 2 | 0 | -1,07R | 0,00R | -1,07R | -1,02R | +0,05R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_4H | Eth Ema 4H | 2 | 2 | 2 | 0 | -1,06R | 0,00R | -1,06R | -1,06R | +0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_4H | Sol Ema 4H | 2 | 2 | 2 | 0 | -1,06R | 0,00R | -1,06R | -1,04R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_4H | Btc Adaptive 4H | 1 | 1 | 1 | 0 | -1,07R | 0,00R | -1,07R | -1,01R | +0,06R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_4H | Btc Bollinger 4H | 1 | 1 | 1 | 0 | 1,72R | 0,00R | +1,72R | 1,68R | -0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_4H | Btc Ema 4H | 1 | 1 | 1 | 0 | -1,07R | 0,00R | -1,07R | -0,99R | +0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_4H | Sol Adaptive 4H | 2 | 1 | 1 | 0 | -1,05R | 0,00R | -1,05R | -0,18R | +0,87R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_4H | Sol Bollinger 4H | 1 | 1 | 1 | 0 | 1,74R | 0,00R | +1,74R | 1,74R | +0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_4H | Sol Donchian 4H | 2 | 1 | 1 | 0 | -1,06R | 0,00R | -1,06R | -0,15R | +0,91R | CAMPIONE INSUFFICIENTE |
| MAIN_DYNAMIC_ASSET_SELECTOR_V1 | MAIN — Dynamic Asset Selector | 11 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,42R | +0,42R | CAMPIONE INSUFFICIENTE |
| MAIN_SIDE_REGIME_GUARD_V1 | MAIN — Side × Regime Guard | 13 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,33R | +0,33R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_BALANCED_LONG_NO_RHV_V1 | Bilanciata 1H — LONG senza Range High Vol | 19 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,34R | -0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_BALANCED_SHORT_TREND_DOWN_STRICT_V1 | Bilanciata 1H — SHORT Trend Down stretto | 2 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,57R | -0,57R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_COST_AWARE_V1 | Rapida score 6–7,5 — Cost Aware | 36 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,20R | +0,20R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_NO_TREND_UP_V1 | Rapida score 6–7,5 — senza Trend Up | 33 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,17R | +0,17R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_RANGE_ONLY_V1 | Rapida score 6–7,5 — Range Only | 13 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,34R | +0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NOHIGH_RANGE_ONLY_V1 | Rapida V3 NoHigh — Range Only | 12 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,49R | +0,49R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NOHIGH_REGIME_GUARD_V1 | Rapida V3 NoHigh — Regime Guard | 20 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,45R | +0,45R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_LONG_ONLY_V1 | Rapida V3 senza ESPORTS — Long Only | 36 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,04R | -0,04R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_MFE_LOCK_V1 | Rapida V3 senza ESPORTS — MFE Lock | 59 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,09R | +0,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_STRESS_GUARD_V1 | Rapida V3 senza ESPORTS — Stress Guard | 20 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,08R | +0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_SIDE_REGIME_GUARD_V1 | Combo Adaptive — Side × Regime Guard | 33 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,24R | +0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_TREND_SIDE_REGIME_GUARD_V1 | Combo Trend — Side × Regime Guard | 29 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,14R | +0,14R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_BE_V1 | Master Adaptive GB20 — Breakeven 0,5R | 22 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,23R | -0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_LOSS_CAP_V1 | Master Adaptive GB20 — Loss Cap 0,75R | 19 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,48R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_PARTIAL_V1 | Master Adaptive GB20 — 50% a 0,75R | 17 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,31R | -0,31R | CAMPIONE INSUFFICIENTE |
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
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 18 | 27,78% | 0,36 | -1,82% | -1,07% | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -1,04R | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | ALT_ROTATION_DOWN | 11 | 0,00% | 0,00 | -0,76R | -0,93R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | ALT_ROTATION_DOWN | 10 | 0,00% | 0,00 | -0,72R | -0,89R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP_HIGH_VOL | 8 | 0,00% | 0,00 | -1,03R | -0,88R | MEDIA |
| EVO_CAND_SHADOW_1H_FAST_V3_NO_ESPORTS_LONG_ONL_TP_R200_7bbb9481 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 8 | 0,00% | 0,00 | -0,79R | -0,86R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 15 | 6,67% | 0,13 | -0,86R | -0,83R | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 21 | 38,10% | 0,52 | -2,31% | -0,81% | ALTA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
