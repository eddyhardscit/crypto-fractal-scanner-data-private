# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-24T09:14:21+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **1291**
- Trade Shadow/Research chiusi: **2586**
- Eventi Shadow già presi dai Paper: **802**
- Eventi Shadow saltati dai Paper: **1784**
- Profili con filtro Paper utile: **11**
- Profili in cui il Paper potrebbe scartare edge: **4**
- Profili con campione ancora insufficiente: **62**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 — madre | 65 | 174 | 32 | 142 | -0,31R | -0,01R | -0,30R | -0,04R | +0,26R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 37 | 149 | 10 | 139 | -0,26R | -0,01R | -0,25R | 0,18R | +0,44R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 23 | 105 | 6 | 99 | -0,72R | 0,02R | -0,73R | -0,06R | +0,65R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 21 | 89 | 12 | 77 | 0,19R | 0,12R | +0,08R | 0,25R | +0,05R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 57 | 83 | 33 | 50 | 0,23R | -0,18R | +0,41R | 0,03R | -0,20R | FILTRO PAPER UTILE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 17 | 77 | 7 | 70 | -0,31R | 0,05R | -0,36R | -0,06R | +0,25R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_TREND | Combo Trend | 25 | 70 | 11 | 59 | -0,17R | 0,09R | -0,27R | -0,11R | +0,06R | SELEZIONE DA RIVEDERE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 30 | 70 | 16 | 54 | 0,14R | 0,23R | -0,09R | 0,41R | +0,27R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 23 | 58 | 12 | 46 | 0,12R | 0,35R | -0,22R | 0,11R | -0,02R | PAPER SCARTA EDGE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 27 | 57 | 12 | 45 | -0,55R | 0,21R | -0,77R | -0,24R | +0,32R | PAPER SCARTA EDGE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 22 | 57 | 13 | 44 | 0,26R | 0,27R | -0,01R | 0,34R | +0,08R | NESSUN EDGE CHIARO |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 31 | 55 | 19 | 36 | 0,21R | 0,03R | +0,18R | 0,16R | -0,05R | NESSUN EDGE CHIARO |
| MAIN | Principale 4H | 18 | 45 | 14 | 31 | 0,04R | -0,05R | +0,10R | -0,05R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_4H_WIDE | Ampia 4H | 13 | 42 | 9 | 33 | 0,25R | -0,10R | +0,35R | 0,06R | -0,19R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 25 | 41 | 12 | 29 | -0,04R | -0,20R | +0,15R | 0,02R | +0,07R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 29 | 39 | 18 | 21 | 0,17R | -0,46R | +0,62R | -0,01R | -0,17R | FILTRO PAPER UTILE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 18 | 39 | 11 | 28 | 0,53R | -0,19R | +0,72R | 0,20R | -0,34R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 28 | 38 | 16 | 22 | 0,16R | -0,25R | +0,41R | -0,00R | -0,16R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 30 | 38 | 20 | 18 | 0,17R | -0,49R | +0,66R | -0,02R | -0,19R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 26 | 37 | 10 | 27 | 0,40R | -0,50R | +0,90R | -0,06R | -0,46R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 22 | 37 | 15 | 22 | -0,39R | 0,00R | -0,39R | -0,20R | +0,19R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 31 | 36 | 18 | 18 | 0,39R | 0,21R | +0,18R | 0,14R | -0,25R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 23 | 34 | 15 | 19 | 0,24R | -0,39R | +0,63R | 0,05R | -0,19R | FILTRO PAPER UTILE |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 25 | 34 | 24 | 10 | 0,17R | -0,32R | +0,49R | 0,19R | +0,02R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 11 | 34 | 6 | 28 | -0,06R | -0,21R | +0,15R | -0,25R | -0,19R | CAMPIONE INSUFFICIENTE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 24 | 32 | 15 | 17 | 0,22R | 0,36R | -0,14R | 0,07R | -0,14R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 27 | 28 | 16 | 12 | 0,31R | -0,42R | +0,73R | 0,09R | -0,23R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 3R | 13 | 25 | 6 | 19 | -0,41R | -0,43R | +0,02R | -0,10R | +0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 9 | 25 | 5 | 20 | -0,28R | -0,46R | +0,18R | -0,01R | +0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 9 | 24 | 7 | 17 | -0,21R | -0,90R | +0,69R | -0,12R | +0,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 23 | 23 | 15 | 8 | -0,23R | -0,44R | +0,21R | -0,15R | +0,08R | SELEZIONE POSITIVA |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 5 | 23 | 3 | 20 | -0,05R | -0,31R | +0,26R | -0,53R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 18 | 19 | 14 | 5 | -0,17R | -0,05R | -0,12R | -0,19R | -0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 18 | 19 | 14 | 5 | -0,17R | -0,05R | -0,12R | -0,16R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 11 | 19 | 4 | 15 | -0,28R | -0,19R | -0,09R | -0,48R | -0,19R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 7 | 18 | 5 | 13 | -0,49R | -0,35R | -0,15R | -0,65R | -0,16R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 27 | 18 | 6 | 12 | -1,05R | -0,30R | -0,75R | -0,27R | +0,78R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 5 | 18 | 3 | 15 | -1,08R | -0,44R | -0,64R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 13 | 18 | 8 | 10 | -1,05R | -0,14R | -0,91R | -0,72R | +0,34R | SELEZIONE DA RIVEDERE |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 5 | 18 | 3 | 15 | -1,08R | -0,44R | -0,64R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 4 | 16 | 3 | 13 | -0,02R | -0,30R | +0,28R | -0,15R | -0,13R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 12 | 14 | 11 | 3 | -0,13R | 0,69R | -0,82R | 0,09R | +0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 5 | 14 | 3 | 11 | -1,08R | -0,69R | -0,40R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 16 | 14 | 7 | 7 | -0,59R | -0,11R | -0,48R | -0,44R | +0,15R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 7 | 14 | 6 | 8 | -0,52R | -0,22R | -0,29R | -0,47R | +0,05R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 8 | 14 | 4 | 10 | 0,93R | -1,06R | +1,99R | 0,24R | -0,69R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 8 | 14 | 4 | 10 | 0,93R | -1,06R | +1,99R | 0,36R | -0,58R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_MFE_V1 | Top 5 + BTC — Guard + BTC≤3 + MFE | 13 | 11 | 3 | 8 | 0,05R | -0,22R | +0,28R | -0,36R | -0,42R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_V1 | Top 5 + BTC — Guard + BTC≤3 | 4 | 11 | 2 | 9 | 0,59R | -0,31R | +0,90R | -0,00R | -0,59R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 3 | 10 | 3 | 7 | -0,02R | -0,14R | +0,12R | -0,33R | -0,31R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 4 | 8 | 4 | 4 | -0,15R | -0,98R | +0,83R | -0,50R | -0,35R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 7 | 8 | 3 | 5 | -0,18R | 0,43R | -0,62R | -0,16R | +0,02R | CAMPIONE INSUFFICIENTE |
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
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 48 | 99 | 41 | 58 | -0,91% | -0,47% | -0,44% | -0,72% | +0,19% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 48 | 99 | 41 | 58 | -1,82% | -0,94% | -0,88% | -1,44% | +0,38% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 31 | 74 | 22 | 52 | -0,14% | -1,00% | +0,87% | -0,47% | -0,33% | SELEZIONE POSITIVA |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 25 | 46 | 23 | 23 | -1,29% | 0,42% | -1,71% | -1,20% | +0,09% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 25 | 46 | 23 | 23 | -2,58% | 0,84% | -3,43% | -2,40% | +0,18% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 18 | 37 | 15 | 22 | 0,19% | -0,40% | +0,59% | -0,09% | -0,27% | FILTRO PAPER UTILE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 6 | 27 | 6 | 21 | 1,11% | -1,04% | +2,15% | 1,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 6 | 27 | 6 | 21 | 2,22% | -2,09% | +4,31% | 2,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 3 | 25 | 3 | 22 | 2,33% | -0,69% | +3,02% | 2,33% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 6 | 9 | 5 | 4 | -2,40% | -3,90% | +1,50% | -2,65% | -0,25% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 6 | 9 | 5 | 4 | -4,80% | -7,80% | +3,00% | -5,30% | -0,50% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 5 | 9 | 4 | 5 | -3,20% | -2,59% | -0,61% | -3,20% | +0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -7,80% | -6,94% | ALTA |
| RSI 25 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 15 | 0,00% | 0,00 | -7,80% | -6,67% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 56 | 0,00% | 0,00 | -7,80% | -6,50% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 15 | 20,00% | 0,18 | -5,11% | -3,81% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -3,90% | -3,47% | ALTA |
| RSI 25 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 15 | 0,00% | 0,00 | -3,90% | -3,33% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 56 | 0,00% | 0,00 | -3,90% | -3,25% | ALTA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -4,05% | -3,18% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 9 | 22,22% | 0,26 | -4,47% | -3,16% | MEDIA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 19 | 0,00% | 0,00 | -3,20% | -3,04% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 10 | 30,00% | 0,31 | -3,76% | -2,89% | MEDIA |
| RSI 25 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 12 | 0,00% | 0,00 | -3,20% | -2,87% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 46 | 0,00% | 0,00 | -3,20% | -2,45% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 18 | 27,78% | 0,36 | -3,63% | -2,33% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 15 | 20,00% | 0,18 | -2,55% | -1,90% | MEDIA |
| RSI 20 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -7,80% | -1,67% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -2,03% | -1,59% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 9 | 22,22% | 0,26 | -2,23% | -1,58% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 10 | 30,00% | 0,31 | -1,88% | -1,45% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 24 | 37,50% | 0,55 | -2,17% | -1,31% | ALTA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 18 | 27,78% | 0,36 | -1,82% | -1,16% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,07R | -1,05R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -1,03R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 5–6 | 8 | 0,00% | 0,00 | -1,03R | -1,01R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | MEDIA | 8 | 0,00% | 0,00 | -1,03R | -1,01R | MEDIA |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 0,00% | 0,00 | -1,07R | -0,89R | MEDIA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,51 | -1,02% | -0,86% | MEDIA |
| RSI 20 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -3,90% | -0,83% | MEDIA |
| SHADOW_1H_FAST_SCORE_6_75_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 12,50% | 0,18 | -0,76R | -0,77R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 26 | 11,54% | 0,23 | -0,73R | -0,70R | ALTA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
