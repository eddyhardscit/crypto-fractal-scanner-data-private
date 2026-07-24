# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-24T03:13:31+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **1242**
- Trade Shadow/Research chiusi: **2536**
- Eventi Shadow già presi dai Paper: **787**
- Eventi Shadow saltati dai Paper: **1749**
- Profili con filtro Paper utile: **13**
- Profili in cui il Paper potrebbe scartare edge: **4**
- Profili con campione ancora insufficiente: **62**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 — madre | 62 | 173 | 32 | 141 | -0,31R | -0,00R | -0,30R | -0,02R | +0,29R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 37 | 148 | 10 | 138 | -0,26R | -0,00R | -0,25R | 0,18R | +0,44R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 22 | 104 | 6 | 98 | -0,72R | 0,03R | -0,74R | -0,06R | +0,65R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 21 | 89 | 12 | 77 | 0,19R | 0,12R | +0,08R | 0,25R | +0,05R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 54 | 81 | 33 | 48 | 0,23R | -0,14R | +0,37R | 0,07R | -0,16R | FILTRO PAPER UTILE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 15 | 76 | 7 | 69 | -0,31R | 0,07R | -0,37R | -0,07R | +0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 30 | 70 | 16 | 54 | 0,14R | 0,23R | -0,09R | 0,41R | +0,27R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_TREND | Combo Trend | 24 | 69 | 10 | 59 | -0,09R | 0,09R | -0,18R | -0,07R | +0,02R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 23 | 58 | 12 | 46 | 0,12R | 0,35R | -0,22R | 0,11R | -0,02R | PAPER SCARTA EDGE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 27 | 57 | 12 | 45 | -0,55R | 0,21R | -0,77R | -0,24R | +0,32R | PAPER SCARTA EDGE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 22 | 57 | 13 | 44 | 0,26R | 0,27R | -0,01R | 0,34R | +0,08R | NESSUN EDGE CHIARO |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 31 | 55 | 19 | 36 | 0,21R | 0,03R | +0,18R | 0,16R | -0,05R | NESSUN EDGE CHIARO |
| MAIN | Principale 4H | 18 | 44 | 14 | 30 | 0,04R | -0,02R | +0,06R | -0,05R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 22 | 40 | 11 | 29 | 0,04R | -0,20R | +0,24R | 0,09R | +0,05R | FILTRO PAPER UTILE |
| SHADOW_4H_WIDE | Ampia 4H | 13 | 40 | 9 | 31 | 0,25R | -0,16R | +0,41R | 0,06R | -0,19R | FILTRO PAPER UTILE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 17 | 39 | 11 | 28 | 0,53R | -0,19R | +0,72R | 0,19R | -0,34R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 28 | 38 | 16 | 22 | 0,16R | -0,25R | +0,41R | -0,00R | -0,16R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 26 | 37 | 17 | 20 | 0,24R | -0,43R | +0,66R | 0,01R | -0,22R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 22 | 37 | 15 | 22 | -0,39R | 0,00R | -0,39R | -0,20R | +0,19R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 29 | 36 | 18 | 18 | 0,39R | 0,21R | +0,18R | 0,19R | -0,20R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 23 | 36 | 10 | 26 | 0,40R | -0,48R | +0,88R | -0,04R | -0,44R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 27 | 36 | 19 | 17 | 0,23R | -0,46R | +0,69R | -0,01R | -0,24R | FILTRO PAPER UTILE |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 25 | 34 | 24 | 10 | 0,17R | -0,32R | +0,49R | 0,19R | +0,02R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 11 | 34 | 6 | 28 | -0,06R | -0,21R | +0,15R | -0,25R | -0,19R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 23 | 33 | 15 | 18 | 0,24R | -0,35R | +0,59R | 0,05R | -0,19R | FILTRO PAPER UTILE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 24 | 32 | 15 | 17 | 0,22R | 0,36R | -0,14R | 0,07R | -0,14R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 26 | 27 | 16 | 11 | 0,31R | -0,36R | +0,67R | 0,10R | -0,21R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 3R | 13 | 25 | 6 | 19 | -0,41R | -0,43R | +0,02R | -0,10R | +0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 9 | 25 | 5 | 20 | -0,28R | -0,46R | +0,18R | -0,01R | +0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 9 | 24 | 7 | 17 | -0,21R | -0,90R | +0,69R | -0,12R | +0,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 5 | 23 | 3 | 20 | -0,05R | -0,31R | +0,26R | -0,53R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 21 | 22 | 14 | 8 | -0,17R | -0,44R | +0,27R | -0,15R | +0,02R | SELEZIONE POSITIVA |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 17 | 19 | 14 | 5 | -0,17R | -0,05R | -0,12R | -0,19R | -0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 17 | 19 | 14 | 5 | -0,17R | -0,05R | -0,12R | -0,15R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 10 | 19 | 4 | 15 | -0,28R | -0,19R | -0,09R | -0,41R | -0,13R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 7 | 18 | 5 | 13 | -0,49R | -0,35R | -0,15R | -0,65R | -0,16R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 25 | 18 | 6 | 12 | -1,05R | -0,30R | -0,75R | -0,32R | +0,73R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 5 | 18 | 3 | 15 | -1,08R | -0,44R | -0,64R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 12 | 18 | 8 | 10 | -1,05R | -0,14R | -0,91R | -0,68R | +0,37R | SELEZIONE DA RIVEDERE |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 5 | 18 | 3 | 15 | -1,08R | -0,44R | -0,64R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 4 | 16 | 3 | 13 | -0,02R | -0,30R | +0,28R | -0,15R | -0,13R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 12 | 14 | 11 | 3 | -0,13R | 0,69R | -0,82R | 0,09R | +0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 5 | 14 | 3 | 11 | -1,08R | -0,69R | -0,40R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 14 | 14 | 7 | 7 | -0,59R | -0,11R | -0,48R | -0,40R | +0,19R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 7 | 14 | 6 | 8 | -0,52R | -0,22R | -0,29R | -0,47R | +0,05R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 8 | 14 | 4 | 10 | 0,93R | -1,06R | +1,99R | 0,24R | -0,69R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 8 | 14 | 4 | 10 | 0,93R | -1,06R | +1,99R | 0,36R | -0,58R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_MFE_V1 | Top 5 + BTC — Guard + BTC≤3 + MFE | 11 | 11 | 3 | 8 | 0,05R | -0,22R | +0,28R | -0,30R | -0,35R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_V1 | Top 5 + BTC — Guard + BTC≤3 | 4 | 11 | 2 | 9 | 0,59R | -0,31R | +0,90R | -0,00R | -0,59R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 3 | 10 | 3 | 7 | -0,02R | -0,14R | +0,12R | -0,33R | -0,31R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 4 | 8 | 4 | 4 | -0,15R | -0,98R | +0,83R | -0,50R | -0,35R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 6 | 8 | 3 | 5 | -0,18R | 0,43R | -0,62R | -0,15R | +0,04R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 6 | 7 | 6 | 1 | -0,04R | -1,40R | +1,36R | -0,59R | -0,54R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 6 | 6 | 6 | 0 | -0,29R | 0,00R | -0,29R | -0,07R | +0,22R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_V1 | Combo Adaptive — Quality7 | 6 | 6 | 4 | 2 | -0,31R | -1,02R | +0,71R | 0,12R | +0,43R | CAMPIONE INSUFFICIENTE |
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
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 46 | 93 | 39 | 54 | -0,95% | -0,35% | -0,60% | -0,75% | +0,20% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 46 | 93 | 39 | 54 | -1,90% | -0,71% | -1,19% | -1,49% | +0,41% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 30 | 69 | 21 | 48 | 0,01% | -0,82% | +0,83% | -0,37% | -0,38% | FILTRO PAPER UTILE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 23 | 41 | 21 | 20 | -1,40% | 0,32% | -1,72% | -1,29% | +0,11% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 23 | 41 | 21 | 20 | -2,80% | 0,64% | -3,44% | -2,58% | +0,22% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 17 | 36 | 14 | 22 | 0,43% | -0,40% | +0,83% | 0,10% | -0,33% | FILTRO PAPER UTILE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 6 | 27 | 6 | 21 | 1,11% | -1,04% | +2,15% | 1,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 6 | 27 | 6 | 21 | 2,22% | -2,09% | +4,31% | 2,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 3 | 22 | 3 | 19 | 2,33% | -1,36% | +3,70% | 2,33% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 6 | 9 | 5 | 4 | -2,40% | -3,90% | +1,50% | -2,65% | -0,25% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 6 | 9 | 5 | 4 | -4,80% | -7,80% | +3,00% | -5,30% | -0,50% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 5 | 9 | 4 | 5 | -3,20% | -2,59% | -0,61% | -3,20% | +0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 24 | 0,00% | 0,00 | -7,80% | -6,68% | ALTA |
| RSI 25 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 15 | 0,00% | 0,00 | -7,80% | -6,67% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 52 | 0,00% | 0,00 | -7,80% | -6,60% | ALTA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -4,98% | -3,86% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 14 | 21,43% | 0,20 | -4,92% | -3,71% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 24 | 0,00% | 0,00 | -3,90% | -3,34% | ALTA |
| RSI 25 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 15 | 0,00% | 0,00 | -3,90% | -3,33% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 52 | 0,00% | 0,00 | -3,90% | -3,30% | ALTA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 18 | 0,00% | 0,00 | -3,20% | -3,12% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 8 | 25,00% | 0,31 | -4,05% | -2,84% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 41 | 0,00% | 0,00 | -3,20% | -2,63% | ALTA |
| RSI 25 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 12 | 0,00% | 0,00 | -3,20% | -2,34% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 17 | 29,41% | 0,38 | -3,39% | -2,18% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -2,49% | -1,93% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 14 | 21,43% | 0,20 | -2,46% | -1,85% | MEDIA |
| RSI 20 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -7,80% | -1,67% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 8 | 25,00% | 0,31 | -2,03% | -1,42% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 17 | 29,41% | 0,38 | -1,69% | -1,09% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,07R | -1,05R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -1,03R | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 18 | 38,89% | 0,53 | -2,22% | -1,01% | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 5–6 | 8 | 0,00% | 0,00 | -1,03R | -0,96R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | MEDIA | 8 | 0,00% | 0,00 | -1,03R | -0,96R | MEDIA |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 0,00% | 0,00 | -1,07R | -0,89R | MEDIA |
| RSI 20 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -3,90% | -0,83% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 23 | 39,13% | 0,59 | -1,93% | -0,81% | ALTA |
| SHADOW_1H_FAST_SCORE_6_75_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 12,50% | 0,18 | -0,76R | -0,81R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 26 | 11,54% | 0,23 | -0,73R | -0,71R | ALTA |
| Forza relativa 1H V2 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 10 | 20,00% | 0,53 | -0,39R | -0,69R | MEDIA |
| SHADOW_BOLLINGER_MR_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | LONG | 11 | 18,18% | 0,29 | -0,63R | -0,66R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
