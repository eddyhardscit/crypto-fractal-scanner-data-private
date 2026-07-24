# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-24T19:18:32+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **1389**
- Trade Shadow/Research chiusi: **2890**
- Eventi Shadow già presi dai Paper: **875**
- Eventi Shadow saltati dai Paper: **2015**
- Profili con filtro Paper utile: **12**
- Profili in cui il Paper potrebbe scartare edge: **6**
- Profili con campione ancora insufficiente: **67**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 — madre | 68 | 186 | 33 | 153 | -0,33R | 0,03R | -0,36R | -0,01R | +0,31R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 37 | 155 | 10 | 145 | -0,26R | 0,03R | -0,29R | 0,18R | +0,44R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 24 | 108 | 6 | 102 | -0,72R | 0,05R | -0,76R | -0,06R | +0,65R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 22 | 102 | 12 | 90 | 0,19R | 0,09R | +0,11R | 0,24R | +0,05R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 60 | 95 | 34 | 61 | 0,19R | -0,06R | +0,25R | 0,06R | -0,13R | FILTRO PAPER UTILE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 18 | 81 | 7 | 74 | -0,31R | 0,03R | -0,34R | -0,06R | +0,25R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_TREND | Combo Trend | 27 | 75 | 11 | 64 | -0,17R | 0,05R | -0,23R | -0,02R | +0,15R | SELEZIONE DA RIVEDERE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 30 | 73 | 16 | 57 | 0,14R | 0,22R | -0,08R | 0,41R | +0,27R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 27 | 69 | 12 | 57 | -0,55R | 0,15R | -0,71R | -0,24R | +0,32R | PAPER SCARTA EDGE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 34 | 62 | 19 | 43 | 0,21R | 0,13R | +0,08R | 0,23R | +0,02R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 24 | 61 | 12 | 49 | 0,12R | 0,33R | -0,21R | 0,10R | -0,02R | PAPER SCARTA EDGE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 22 | 60 | 13 | 47 | 0,26R | 0,25R | +0,01R | 0,34R | +0,08R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 28 | 53 | 14 | 39 | -0,00R | -0,04R | +0,04R | 0,09R | +0,09R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 32 | 51 | 22 | 29 | 0,17R | -0,20R | +0,37R | 0,03R | -0,14R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 33 | 50 | 24 | 26 | 0,17R | -0,20R | +0,37R | 0,01R | -0,16R | FILTRO PAPER UTILE |
| MAIN | Principale 4H | 18 | 49 | 14 | 35 | 0,04R | -0,08R | +0,12R | -0,05R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 32 | 49 | 18 | 31 | 0,16R | -0,01R | +0,17R | 0,09R | -0,07R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 28 | 45 | 13 | 32 | 0,30R | -0,40R | +0,70R | -0,06R | -0,36R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 12 | 45 | 6 | 39 | -0,06R | -0,14R | +0,08R | -0,23R | -0,17R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 27 | 44 | 17 | 27 | 0,23R | -0,13R | +0,36R | 0,14R | -0,09R | FILTRO PAPER UTILE |
| SHADOW_4H_WIDE | Ampia 4H | 14 | 42 | 9 | 33 | 0,25R | -0,10R | +0,35R | -0,02R | -0,27R | FILTRO PAPER UTILE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 18 | 41 | 11 | 30 | 0,53R | -0,25R | +0,78R | 0,20R | -0,34R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 23 | 40 | 15 | 25 | -0,39R | 0,23R | -0,62R | -0,19R | +0,20R | PAPER SCARTA EDGE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 33 | 39 | 19 | 20 | 0,32R | 0,40R | -0,08R | 0,10R | -0,22R | NESSUN EDGE CHIARO |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 28 | 38 | 25 | 13 | 0,12R | -0,30R | +0,42R | 0,05R | -0,07R | FILTRO PAPER UTILE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 26 | 36 | 16 | 20 | 0,14R | 0,59R | -0,46R | 0,08R | -0,05R | PAPER SCARTA EDGE |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 33 | 36 | 23 | 13 | 0,43R | -0,28R | +0,71R | 0,18R | -0,26R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 25% a 3R | 14 | 30 | 6 | 24 | -0,41R | -0,57R | +0,16R | -0,10R | +0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 10 | 30 | 5 | 25 | -0,28R | -0,59R | +0,31R | -0,02R | +0,26R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 24 | 28 | 17 | 11 | -0,17R | -0,37R | +0,20R | -0,19R | -0,02R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 5 | 26 | 3 | 23 | -0,05R | -0,27R | +0,22R | -0,53R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 10 | 25 | 8 | 17 | 0,06R | -0,90R | +0,95R | -0,04R | -0,10R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 21 | 23 | 18 | 5 | -0,08R | -0,05R | -0,03R | -0,19R | -0,11R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 21 | 23 | 18 | 5 | -0,08R | -0,05R | -0,03R | -0,16R | -0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 12 | 22 | 5 | 17 | -0,43R | -0,10R | -0,33R | -0,39R | +0,04R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 7 | 21 | 5 | 16 | -0,49R | -0,28R | -0,21R | -0,65R | -0,16R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 31 | 21 | 8 | 13 | -1,04R | -0,12R | -0,92R | -0,17R | +0,87R | SELEZIONE DA RIVEDERE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 5 | 21 | 3 | 18 | -1,08R | -0,37R | -0,71R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 14 | 21 | 10 | 11 | -0,75R | -0,22R | -0,52R | -0,52R | +0,22R | SELEZIONE DA RIVEDERE |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 5 | 21 | 3 | 18 | -1,08R | -0,37R | -0,71R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 4 | 19 | 3 | 16 | -0,02R | -0,23R | +0,21R | -0,15R | -0,13R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 17 | 17 | 8 | 9 | -0,24R | -0,31R | +0,07R | -0,37R | -0,13R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 7 | 17 | 6 | 11 | -0,52R | -0,15R | -0,37R | -0,47R | +0,05R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 14 | 16 | 12 | 4 | -0,22R | 0,23R | -0,45R | -0,01R | +0,21R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 5 | 15 | 3 | 12 | -1,08R | -0,38R | -0,70R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_MFE_V1 | Top 5 + BTC — Guard + BTC≤3 + MFE | 14 | 14 | 4 | 10 | 0,59R | -0,38R | +0,97R | -0,29R | -0,88R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_V1 | Top 5 + BTC — Guard + BTC≤3 | 4 | 14 | 2 | 12 | 0,59R | -0,22R | +0,81R | -0,00R | -0,59R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 8 | 14 | 4 | 10 | 0,93R | -1,06R | +1,99R | 0,24R | -0,69R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 8 | 14 | 4 | 10 | 0,93R | -1,06R | +1,99R | 0,36R | -0,58R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 10 | 12 | 7 | 5 | 0,06R | 0,43R | -0,38R | -0,17R | -0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 3 | 10 | 3 | 7 | -0,02R | -0,14R | +0,12R | -0,33R | -0,31R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 5 | 8 | 4 | 4 | -0,15R | -0,98R | +0,83R | -0,46R | -0,31R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 8 | 8 | 8 | 0 | -0,50R | 0,00R | -0,50R | 0,20R | +0,70R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 6 | 7 | 6 | 1 | -0,04R | -1,40R | +1,36R | -0,59R | -0,54R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_V1 | Combo Adaptive — Quality7 | 7 | 7 | 5 | 2 | 0,14R | -1,02R | +1,16R | 0,11R | -0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 4 | 4 | 4 | 0 | -1,12R | 0,00R | -1,12R | -0,09R | +1,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 5 | 4 | 4 | 0 | -0,36R | 0,00R | -0,36R | -0,13R | +0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_PARTIAL_1R_V1 | Combo Adaptive — Quality7 + Regime + parziale 1R | 4 | 4 | 4 | 0 | -0,32R | 0,00R | -0,32R | -0,55R | -0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_V1 | Combo Adaptive — Quality7 + Regime | 4 | 4 | 4 | 0 | -0,32R | 0,00R | -0,32R | -0,66R | -0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 4 | 4 | 2 | 2 | 0,39R | -1,11R | +1,50R | -0,46R | -0,85R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 6 | 4 | 2 | 2 | 0,39R | -1,11R | +1,49R | -0,55R | -0,94R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 5 | 4 | 3 | 1 | -0,11R | -1,11R | +1,00R | -0,44R | -0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 3 | 3 | 3 | 0 | -1,11R | 0,00R | -1,11R | 0,09R | +1,20R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 7 | 3 | 3 | 0 | 0,89R | 0,00R | +0,89R | 0,42R | -0,46R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 3 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | -0,11R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 8 | 3 | 2 | 1 | 0,16R | 2,40R | -2,24R | -0,38R | -0,53R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 3 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | 0,61R | +0,73R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 3 | 3 | 3 | 0 | -0,11R | 0,00R | -0,11R | -0,42R | -0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 2 | 2 | 2 | 0 | 1,37R | 0,00R | +1,37R | 1,00R | -0,37R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_BOLLINGER_1H | Doge Bollinger 1H | 2 | 2 | 1 | 1 | -1,13R | -1,11R | -0,02R | -1,11R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 4 | 2 | 2 | 0 | 0,38R | 0,00R | +0,38R | -0,01R | -0,38R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 3 | 2 | 2 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,02R | CAMPIONE INSUFFICIENTE |
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
| SHADOW_1H_BALANCED_LONG_NO_RHV_V1 | Bilanciata 1H — LONG senza Range High Vol | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_BALANCED_SHORT_TREND_DOWN_STRICT_V1 | Bilanciata 1H — SHORT Trend Down stretto | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_COST_AWARE_V1 | Rapida score 6–7,5 — Cost Aware | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_NO_TREND_UP_V1 | Rapida score 6–7,5 — senza Trend Up | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_RANGE_ONLY_V1 | Rapida score 6–7,5 — Range Only | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_LONG_ONLY_V1 | Rapida V3 senza ESPORTS — Long Only | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_MFE_LOCK_V1 | Rapida V3 senza ESPORTS — MFE Lock | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_STRESS_GUARD_V1 | Rapida V3 senza ESPORTS — Stress Guard | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 48 | 99 | 41 | 58 | -0,91% | -0,47% | -0,44% | -0,72% | +0,19% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 48 | 99 | 41 | 58 | -1,82% | -0,94% | -0,88% | -1,44% | +0,38% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 32 | 76 | 23 | 53 | 0,05% | -0,90% | +0,96% | -0,32% | -0,37% | FILTRO PAPER UTILE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 25 | 46 | 23 | 23 | -1,29% | 0,42% | -1,71% | -1,20% | +0,09% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 25 | 46 | 23 | 23 | -2,58% | 0,84% | -3,43% | -2,40% | +0,18% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 19 | 41 | 16 | 25 | 0,45% | 0,16% | +0,28% | 0,14% | -0,30% | SELEZIONE POSITIVA |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 6 | 32 | 6 | 26 | 1,11% | -1,30% | +2,41% | 1,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 6 | 32 | 6 | 26 | 2,22% | -2,61% | +4,83% | 2,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 3 | 30 | 3 | 27 | 2,33% | -1,15% | +3,49% | 2,33% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 7 | 12 | 6 | 6 | -1,40% | -3,90% | +2,50% | -1,76% | -0,36% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 7 | 12 | 6 | 6 | -2,80% | -7,80% | +5,00% | -3,51% | -0,71% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 6 | 12 | 5 | 7 | -3,20% | -2,77% | -0,43% | -3,20% | +0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -7,80% | -6,94% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 56 | 0,00% | 0,00 | -7,80% | -6,50% | ALTA |
| RSI 25 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 19 | 0,00% | 0,00 | -7,80% | -6,09% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 15 | 20,00% | 0,18 | -5,11% | -3,81% | MEDIA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 19 | 0,00% | 0,00 | -3,20% | -3,48% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -3,90% | -3,47% | ALTA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 56 | 0,00% | 0,00 | -3,90% | -3,25% | ALTA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -4,05% | -3,18% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 9 | 22,22% | 0,26 | -4,47% | -3,16% | MEDIA |
| RSI 25 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 19 | 0,00% | 0,00 | -3,90% | -3,05% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 10 | 30,00% | 0,31 | -3,76% | -2,89% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 46 | 0,00% | 0,00 | -3,20% | -2,59% | ALTA |
| RSI 20 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 10 | 0,00% | 0,00 | -7,80% | -2,50% | MEDIA |
| RSI 25 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 17 | 0,00% | 0,00 | -3,20% | -2,40% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 18 | 27,78% | 0,36 | -3,63% | -2,33% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 15 | 20,00% | 0,18 | -2,55% | -1,90% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -2,03% | -1,59% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 9 | 22,22% | 0,26 | -2,23% | -1,58% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 10 | 30,00% | 0,31 | -1,88% | -1,45% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 24 | 37,50% | 0,55 | -2,17% | -1,31% | ALTA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,51 | -1,02% | -1,30% | MEDIA |
| RSI 20 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 10 | 0,00% | 0,00 | -3,90% | -1,25% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 18 | 27,78% | 0,36 | -1,82% | -1,16% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,07R | -1,08R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -1,05R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 5–6 | 8 | 0,00% | 0,00 | -1,03R | -1,01R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | MEDIA | 8 | 0,00% | 0,00 | -1,03R | -1,01R | MEDIA |
| SHADOW_1H_FAST_SCORE_6_75_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 12,50% | 0,18 | -0,76R | -0,94R | MEDIA |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 0,00% | 0,00 | -1,07R | -0,94R | MEDIA |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | ALT_ROTATION_DOWN | 8 | 0,00% | 0,00 | -1,03R | -0,78R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
