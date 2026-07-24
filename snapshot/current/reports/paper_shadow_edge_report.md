# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-24T02:13:11+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **1205**
- Trade Shadow/Research chiusi: **2434**
- Eventi Shadow già presi dai Paper: **770**
- Eventi Shadow saltati dai Paper: **1664**
- Profili con filtro Paper utile: **13**
- Profili in cui il Paper potrebbe scartare edge: **6**
- Profili con campione ancora insufficiente: **63**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 — madre | 61 | 171 | 32 | 139 | -0,31R | 0,01R | -0,32R | 0,00R | +0,31R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 36 | 146 | 10 | 136 | -0,26R | 0,01R | -0,27R | 0,18R | +0,43R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 22 | 103 | 6 | 97 | -0,72R | 0,04R | -0,75R | -0,06R | +0,65R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 21 | 86 | 12 | 74 | 0,19R | 0,16R | +0,03R | 0,25R | +0,05R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 53 | 79 | 33 | 46 | 0,23R | -0,10R | +0,33R | 0,09R | -0,14R | FILTRO PAPER UTILE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 15 | 74 | 7 | 67 | -0,31R | 0,10R | -0,41R | -0,07R | +0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_TREND | Combo Trend | 23 | 67 | 9 | 58 | 0,01R | 0,11R | -0,10R | -0,01R | -0,03R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 29 | 67 | 16 | 51 | 0,14R | 0,30R | -0,16R | 0,42R | +0,28R | PAPER SCARTA EDGE |
| SHADOW_COMBO_SCANNER | Combo Scanner | 23 | 55 | 12 | 43 | 0,12R | 0,44R | -0,32R | 0,11R | -0,02R | PAPER SCARTA EDGE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 27 | 54 | 12 | 42 | -0,55R | 0,30R | -0,86R | -0,24R | +0,32R | PAPER SCARTA EDGE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 21 | 54 | 13 | 41 | 0,26R | 0,36R | -0,10R | 0,34R | +0,08R | NESSUN EDGE CHIARO |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 31 | 53 | 19 | 34 | 0,21R | 0,09R | +0,12R | 0,16R | -0,05R | NESSUN EDGE CHIARO |
| MAIN | Principale 4H | 18 | 44 | 14 | 30 | 0,04R | -0,02R | +0,06R | -0,05R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_4H_WIDE | Ampia 4H | 13 | 40 | 9 | 31 | 0,25R | -0,16R | +0,41R | 0,06R | -0,19R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 22 | 38 | 11 | 27 | 0,04R | -0,14R | +0,18R | 0,09R | +0,05R | FILTRO PAPER UTILE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 17 | 38 | 11 | 27 | 0,53R | -0,16R | +0,69R | 0,19R | -0,34R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 22 | 37 | 15 | 22 | -0,39R | 0,00R | -0,39R | -0,20R | +0,19R | SELEZIONE DA RIVEDERE |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 28 | 36 | 15 | 21 | 0,24R | -0,22R | +0,46R | -0,00R | -0,24R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 25 | 35 | 17 | 18 | 0,24R | -0,36R | +0,60R | 0,06R | -0,17R | FILTRO PAPER UTILE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 28 | 34 | 18 | 16 | 0,39R | 0,36R | +0,03R | 0,24R | -0,15R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 26 | 34 | 19 | 15 | 0,23R | -0,39R | +0,62R | 0,04R | -0,20R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 22 | 33 | 10 | 23 | 0,40R | -0,41R | +0,81R | 0,01R | -0,39R | FILTRO PAPER UTILE |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 24 | 33 | 23 | 10 | 0,11R | -0,32R | +0,44R | 0,13R | +0,02R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 22 | 32 | 15 | 17 | 0,24R | -0,31R | +0,55R | 0,10R | -0,14R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 11 | 31 | 6 | 25 | -0,06R | -0,11R | +0,05R | -0,25R | -0,19R | CAMPIONE INSUFFICIENTE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 23 | 29 | 15 | 14 | 0,22R | 0,66R | -0,44R | 0,06R | -0,16R | PAPER SCARTA EDGE |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 25 | 26 | 16 | 10 | 0,31R | -0,29R | +0,61R | 0,15R | -0,16R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 9 | 24 | 7 | 17 | -0,21R | -0,90R | +0,69R | -0,12R | +0,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 3R | 12 | 24 | 6 | 18 | -0,41R | -0,40R | -0,02R | -0,13R | +0,28R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 9 | 24 | 5 | 19 | -0,28R | -0,43R | +0,15R | -0,01R | +0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 18 | 20 | 12 | 8 | -0,03R | -0,44R | +0,41R | 0,02R | +0,05R | SELEZIONE POSITIVA |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 5 | 20 | 3 | 17 | -0,05R | -0,18R | +0,13R | -0,53R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 16 | 18 | 13 | 5 | -0,11R | -0,05R | -0,05R | -0,13R | -0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 16 | 18 | 13 | 5 | -0,11R | -0,05R | -0,05R | -0,09R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 9 | 16 | 3 | 13 | -0,04R | -0,06R | +0,02R | -0,30R | -0,26R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 7 | 15 | 5 | 10 | -0,49R | -0,15R | -0,35R | -0,65R | -0,16R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 23 | 15 | 4 | 11 | -1,07R | -0,23R | -0,83R | -0,25R | +0,82R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 5 | 15 | 3 | 12 | -1,08R | -0,30R | -0,79R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 10 | 15 | 7 | 8 | -1,06R | 0,07R | -1,13R | -0,55R | +0,51R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 5 | 15 | 3 | 12 | -1,08R | -0,30R | -0,78R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 11 | 13 | 10 | 3 | -0,31R | 0,69R | -0,99R | -0,04R | +0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 5 | 13 | 3 | 10 | -1,08R | -0,66R | -0,43R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 3 | 13 | 3 | 10 | -0,02R | -0,08R | +0,06R | -0,33R | -0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 7 | 13 | 4 | 9 | 0,93R | -1,06R | +1,99R | 0,25R | -0,69R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 7 | 13 | 4 | 9 | 0,93R | -1,06R | +1,99R | 0,38R | -0,55R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 13 | 11 | 6 | 5 | -0,52R | 0,25R | -0,77R | -0,32R | +0,20R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 6 | 11 | 6 | 5 | -0,52R | 0,25R | -0,77R | -0,58R | -0,06R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 3 | 10 | 3 | 7 | -0,02R | -0,14R | +0,12R | -0,33R | -0,31R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 4 | 8 | 4 | 4 | -0,15R | -0,98R | +0,83R | -0,50R | -0,35R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 6 | 8 | 3 | 5 | -0,18R | 0,43R | -0,62R | -0,15R | +0,04R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_MFE_V1 | Top 5 + BTC — Guard + BTC≤3 + MFE | 10 | 8 | 2 | 6 | 0,59R | 0,04R | +0,55R | -0,19R | -0,77R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_V1 | Top 5 + BTC — Guard + BTC≤3 | 3 | 8 | 2 | 6 | 0,59R | 0,04R | +0,55R | -0,06R | -0,65R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 6 | 7 | 6 | 1 | -0,04R | -1,40R | +1,36R | -0,59R | -0,54R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 6 | 6 | 6 | 0 | -0,29R | 0,00R | -0,29R | -0,07R | +0,22R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_V1 | Combo Adaptive — Quality7 | 5 | 5 | 4 | 1 | -0,31R | -1,02R | +0,71R | 0,10R | +0,41R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 4 | 4 | 4 | 0 | -0,36R | 0,00R | -0,36R | -0,32R | +0,04R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_PARTIAL_1R_V1 | Combo Adaptive — Quality7 + Regime + parziale 1R | 4 | 3 | 3 | 0 | -1,07R | 0,00R | -1,07R | -0,55R | +0,52R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_V1 | Combo Adaptive — Quality7 + Regime | 4 | 3 | 3 | 0 | -1,07R | 0,00R | -1,07R | -0,66R | +0,41R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 6 | 3 | 3 | 0 | 0,89R | 0,00R | +0,89R | 0,46R | -0,43R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 4 | 3 | 2 | 1 | 0,39R | -1,11R | +1,50R | -0,46R | -0,85R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 3 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | -0,11R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 6 | 3 | 2 | 1 | 0,39R | -1,10R | +1,49R | -0,55R | -0,94R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 8 | 3 | 2 | 1 | 0,16R | 2,40R | -2,24R | -0,38R | -0,53R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 3 | 3 | 3 | 0 | -0,11R | 0,00R | -0,11R | -0,48R | -0,37R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 3 | 3 | 3 | 0 | -0,11R | 0,00R | -0,11R | -0,42R | -0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 2 | 2 | 2 | 0 | 1,37R | 0,00R | +1,37R | 1,00R | -0,37R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 3 | 2 | 2 | 0 | -1,12R | 0,00R | -1,12R | -0,41R | +0,71R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 3 | 2 | 2 | 0 | 0,38R | 0,00R | +0,38R | -0,02R | -0,39R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 2 | 2 | 2 | 0 | -1,12R | 0,00R | -1,12R | -0,03R | +1,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 2 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,12R | +1,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_BOLLINGER_1H | Doge Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_BOLLINGER_1H | Eth Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | 0,31R | +1,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_4H | Eth Ema 4H | 1 | 1 | 1 | 0 | -1,06R | 0,00R | -1,06R | -1,06R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_4H | Sol Adaptive 4H | 1 | 1 | 1 | 0 | -1,05R | 0,00R | -1,05R | -1,04R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_4H | Sol Donchian 4H | 1 | 1 | 1 | 0 | -1,06R | 0,00R | -1,06R | -1,04R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_4H | Sol Ema 4H | 1 | 1 | 1 | 0 | -1,06R | 0,00R | -1,06R | -1,04R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_4H | Btc Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_4H | Btc Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_4H | Btc Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_4H | Btc Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_4H | Sol Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 45 | 92 | 38 | 54 | -1,07% | -0,35% | -0,72% | -0,84% | +0,23% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 45 | 92 | 38 | 54 | -2,14% | -0,71% | -1,43% | -1,69% | +0,45% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 29 | 68 | 20 | 48 | 0,04% | -0,82% | +0,86% | -0,37% | -0,40% | FILTRO PAPER UTILE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 23 | 41 | 21 | 20 | -1,40% | 0,32% | -1,72% | -1,29% | +0,11% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 23 | 41 | 21 | 20 | -2,80% | 0,64% | -3,44% | -2,58% | +0,22% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 17 | 36 | 14 | 22 | 0,43% | -0,40% | +0,83% | 0,10% | -0,33% | FILTRO PAPER UTILE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 6 | 27 | 6 | 21 | 1,11% | -1,04% | +2,15% | 1,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 6 | 27 | 6 | 21 | 2,22% | -2,09% | +4,31% | 2,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 3 | 21 | 3 | 18 | 2,33% | -1,26% | +3,59% | 2,33% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 6 | 9 | 5 | 4 | -2,40% | -3,90% | +1,50% | -2,65% | -0,25% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 6 | 9 | 5 | 4 | -4,80% | -7,80% | +3,00% | -5,30% | -0,50% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 5 | 9 | 4 | 5 | -3,20% | -2,59% | -0,61% | -3,20% | +0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 24 | 0,00% | 0,00 | -7,80% | -6,68% | ALTA |
| RSI 25 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 15 | 0,00% | 0,00 | -7,80% | -6,67% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 52 | 0,00% | 0,00 | -7,80% | -6,50% | ALTA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -4,98% | -3,86% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 14 | 21,43% | 0,20 | -4,92% | -3,62% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 24 | 0,00% | 0,00 | -3,90% | -3,34% | ALTA |
| RSI 25 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 15 | 0,00% | 0,00 | -3,90% | -3,33% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 52 | 0,00% | 0,00 | -3,90% | -3,25% | ALTA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 18 | 0,00% | 0,00 | -3,20% | -3,12% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 8 | 25,00% | 0,31 | -4,05% | -2,75% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 41 | 0,00% | 0,00 | -3,20% | -2,63% | ALTA |
| RSI 25 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 11 | 0,00% | 0,00 | -3,20% | -2,45% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 17 | 29,41% | 0,38 | -3,39% | -2,09% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -2,49% | -1,93% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 14 | 21,43% | 0,20 | -2,46% | -1,81% | MEDIA |
| RSI 20 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -7,80% | -1,67% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 8 | 25,00% | 0,31 | -2,03% | -1,38% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,07R | -1,07R | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 17 | 29,41% | 0,38 | -1,69% | -1,04% | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -1,04R | MEDIA |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 0,00% | 0,00 | -1,07R | -0,97R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 5–6 | 8 | 0,00% | 0,00 | -1,03R | -0,96R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | MEDIA | 8 | 0,00% | 0,00 | -1,03R | -0,96R | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 18 | 38,89% | 0,53 | -2,22% | -0,92% | MEDIA |
| SHADOW_1H_FAST_SCORE_6_75_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 12,50% | 0,18 | -0,76R | -0,85R | MEDIA |
| RSI 20 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -3,90% | -0,83% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 23 | 39,13% | 0,59 | -1,93% | -0,81% | ALTA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 26 | 11,54% | 0,23 | -0,73R | -0,72R | ALTA |
| Forza relativa 1H V2 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 9 | 22,22% | 0,60 | -0,32R | -0,70R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 18 | 22,22% | 0,59 | -0,32R | -0,66R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
