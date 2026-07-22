# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-22T11:55:21+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **883**
- Trade Shadow/Research chiusi: **1696**
- Eventi Shadow già presi dai Paper: **570**
- Eventi Shadow saltati dai Paper: **1126**
- Profili con filtro Paper utile: **5**
- Profili in cui il Paper potrebbe scartare edge: **5**
- Profili con campione ancora insufficiente: **69**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 — madre | 52 | 147 | 29 | 118 | -0,31R | -0,05R | -0,27R | -0,06R | +0,25R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 28 | 128 | 8 | 120 | -0,42R | 0,02R | -0,44R | 0,22R | +0,64R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 20 | 88 | 6 | 82 | -0,72R | -0,01R | -0,71R | -0,01R | +0,70R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 19 | 69 | 12 | 57 | 0,19R | 0,26R | -0,07R | 0,24R | +0,05R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 45 | 60 | 28 | 32 | 0,10R | -0,21R | +0,32R | 0,02R | -0,08R | FILTRO PAPER UTILE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 13 | 60 | 6 | 54 | -0,18R | 0,08R | -0,26R | -0,03R | +0,15R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 28 | 56 | 14 | 42 | 0,09R | 0,45R | -0,36R | 0,36R | +0,27R | PAPER SCARTA EDGE |
| SHADOW_COMBO_TREND | Combo Trend | 16 | 54 | 8 | 46 | 0,14R | 0,07R | +0,07R | 0,01R | -0,13R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 20 | 43 | 13 | 30 | 0,26R | 0,45R | -0,19R | 0,41R | +0,15R | PAPER SCARTA EDGE |
| SHADOW_COMBO_SCANNER | Combo Scanner | 20 | 40 | 8 | 32 | -0,24R | 0,56R | -0,80R | -0,03R | +0,21R | PAPER SCARTA EDGE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 28 | 39 | 17 | 22 | 0,36R | 0,04R | +0,32R | 0,24R | -0,12R | SELEZIONE POSITIVA |
| MAIN | Principale 4H | 17 | 38 | 12 | 26 | -0,03R | -0,10R | +0,07R | -0,17R | -0,15R | NESSUN EDGE CHIARO |
| SHADOW_4H_WIDE | Ampia 4H | 12 | 38 | 9 | 29 | 0,25R | -0,23R | +0,48R | 0,15R | -0,09R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 26 | 37 | 10 | 27 | -0,45R | 0,50R | -0,95R | -0,24R | +0,20R | PAPER SCARTA EDGE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 17 | 31 | 11 | 20 | 0,53R | -0,37R | +0,91R | 0,19R | -0,34R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 17 | 30 | 12 | 18 | -0,71R | 0,03R | -0,74R | -0,35R | +0,36R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 20 | 29 | 15 | 14 | 0,46R | 0,11R | +0,36R | 0,22R | -0,24R | SELEZIONE POSITIVA |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 18 | 26 | 17 | 9 | 0,10R | -0,24R | +0,34R | 0,12R | +0,02R | FILTRO PAPER UTILE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 18 | 22 | 12 | 10 | 0,03R | 0,75R | -0,71R | 0,06R | +0,02R | PAPER SCARTA EDGE |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 11 | 18 | 5 | 13 | 0,09R | -0,60R | +0,69R | -0,15R | -0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 15 | 18 | 11 | 7 | -0,17R | -1,06R | +0,88R | -0,28R | -0,10R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 14 | 18 | 8 | 10 | -0,15R | -0,81R | +0,67R | -0,26R | -0,11R | SELEZIONE POSITIVA |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 15 | 17 | 7 | 10 | -0,01R | -0,81R | +0,80R | -0,25R | -0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 12 | 17 | 6 | 11 | 0,14R | -0,82R | +0,96R | -0,18R | -0,33R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 14 | 17 | 8 | 9 | -0,15R | -0,78R | +0,63R | -0,26R | -0,11R | SELEZIONE POSITIVA |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 9 | 13 | 6 | 7 | -0,06R | -0,22R | +0,15R | -0,30R | -0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 7 | 12 | 6 | 6 | -0,06R | -0,57R | +0,51R | -0,26R | -0,19R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 15 | 11 | 8 | 3 | -0,15R | -1,06R | +0,90R | -0,24R | -0,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 8 | 9 | 7 | 2 | 0,04R | 1,54R | -1,50R | 0,36R | +0,32R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 8 | 8 | 5 | 3 | -0,59R | -1,11R | +0,52R | -0,29R | +0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 5 | 8 | 3 | 5 | -0,05R | -0,48R | +0,43R | -0,53R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 3R | 6 | 8 | 4 | 4 | -0,07R | -1,04R | +0,96R | 0,06R | +0,13R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 6 | 8 | 4 | 4 | -0,07R | -1,04R | +0,96R | 0,00R | +0,08R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 6 | 7 | 6 | 1 | -0,04R | -1,40R | +1,36R | -0,59R | -0,54R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 7 | 7 | 6 | 1 | -0,68R | -1,09R | +0,40R | -0,58R | +0,10R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 7 | 7 | 6 | 1 | -0,68R | -1,09R | +0,40R | -0,46R | +0,22R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 4 | 6 | 2 | 4 | 0,49R | -1,05R | +1,54R | -0,13R | -0,62R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 4 | 5 | 4 | 1 | -1,09R | -1,01R | -0,08R | -1,08R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 7 | 5 | 3 | 2 | -1,08R | -1,06R | -0,02R | -0,78R | +0,30R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 4 | 5 | 3 | 2 | -1,08R | -1,06R | -0,02R | -1,08R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 4 | 5 | 3 | 2 | -1,08R | -1,06R | -0,02R | -1,08R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 4 | 5 | 3 | 2 | -1,08R | -1,06R | -0,02R | -1,08R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 5 | 5 | 5 | 0 | -1,06R | 0,00R | -1,06R | -0,93R | +0,13R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 5 | 5 | 5 | 0 | -1,06R | 0,00R | -1,06R | -1,13R | -0,07R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 4 | 4 | 4 | 0 | -0,36R | 0,00R | -0,36R | -0,32R | +0,04R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 3 | 4 | 2 | 2 | -1,09R | -1,06R | -0,02R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 6 | 4 | 1 | 3 | -1,07R | -1,05R | -0,02R | -0,05R | +1,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 6 | 4 | 1 | 3 | -1,07R | -1,05R | -0,02R | -0,05R | +1,01R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 3 | 3 | 3 | 0 | -0,31R | 0,00R | -0,31R | 0,03R | +0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 3 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | -0,11R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 2 | 3 | 1 | 2 | -1,07R | -1,01R | -0,05R | 0,04R | +1,11R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 2 | 3 | 1 | 2 | -1,07R | -1,01R | -0,05R | 0,04R | +1,11R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 2 | 2 | 2 | 0 | 0,97R | 0,00R | +0,97R | 0,26R | -0,71R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 3 | 2 | 2 | 0 | -1,12R | 0,00R | -1,12R | -0,41R | +0,71R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_PARTIAL_1R_V1 | Combo Adaptive — Quality7 + Regime + parziale 1R | 2 | 2 | 2 | 0 | -1,06R | 0,00R | -1,06R | -1,07R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_V1 | Combo Adaptive — Quality7 + Regime | 2 | 2 | 2 | 0 | -1,06R | 0,00R | -1,06R | -1,07R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_V1 | Combo Adaptive — Quality7 | 2 | 2 | 2 | 0 | -1,06R | 0,00R | -1,06R | -1,07R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 3 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,25R | -0,64R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 5 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,44R | -0,83R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_MFE_V1 | Top 5 + BTC — Guard + BTC≤3 + MFE | 2 | 2 | 1 | 1 | -1,01R | -1,01R | 0,00R | -1,19R | -0,17R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_V1 | Top 5 + BTC — Guard + BTC≤3 | 2 | 2 | 1 | 1 | -1,01R | -1,01R | 0,00R | -1,19R | -0,17R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,18R | -0,57R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,09R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 1 | 1 | 1 | 0 | -1,02R | 0,00R | -1,02R | -1,19R | -0,17R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 2 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,12R | +1,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 2 | 1 | 1 | 0 | 1,37R | 0,00R | +1,37R | 1,00R | -0,37R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 2 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -0,31R | +0,82R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 4 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,26R | +0,85R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_BOLLINGER_1H | Eth Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | 0,31R | +1,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 7 | 1 | 1 | 0 | -1,10R | 0,00R | -1,10R | -0,65R | +0,45R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 2 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -0,03R | +1,10R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_4H | Btc Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_4H | Btc Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_4H | Btc Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_4H | Btc Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_BOLLINGER_1H | Doge Bollinger 1H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_4H | Eth Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_4H | Sol Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_4H | Sol Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_4H | Sol Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_4H | Sol Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 34 | 75 | 29 | 46 | -1,48% | -0,55% | -0,93% | -0,96% | +0,53% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 34 | 75 | 29 | 46 | -2,97% | -1,11% | -1,86% | -1,91% | +1,06% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 22 | 55 | 14 | 41 | -0,59% | -1,14% | +0,55% | -0,75% | -0,16% | SELEZIONE POSITIVA |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 20 | 36 | 18 | 18 | -1,40% | -0,04% | -1,36% | -1,28% | +0,13% | SELEZIONE DA RIVEDERE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 20 | 36 | 18 | 18 | -2,80% | -0,09% | -2,71% | -2,55% | +0,25% | SELEZIONE DA RIVEDERE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 13 | 30 | 10 | 20 | 0,38% | -0,87% | +1,25% | -0,04% | -0,42% | FILTRO PAPER UTILE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 6 | 15 | 6 | 9 | 1,11% | -1,40% | +2,51% | 1,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 6 | 15 | 6 | 9 | 2,22% | -2,80% | +5,02% | 2,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 3 | 10 | 3 | 7 | 2,33% | 0,30% | +2,03% | 2,33% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 4 | 4 | 4 | 0 | -2,02% | 0,00% | -2,02% | -2,02% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 4 | 4 | 4 | 0 | -4,05% | 0,00% | -4,05% | -4,05% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 3 | 3 | 3 | 0 | -3,20% | 0,00% | -3,20% | -3,20% | 0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| RSI 25 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -7,80% | -7,00% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 22 | 0,00% | 0,00 | -7,80% | -6,36% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 45 | 0,00% | 0,00 | -7,80% | -5,98% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 12 | 16,67% | 0,13 | -5,69% | -3,86% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 13 | 15,38% | 0,17 | -5,49% | -3,67% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -4,98% | -3,54% | MEDIA |
| RSI 25 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -3,90% | -3,50% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 22 | 0,00% | 0,00 | -3,90% | -3,18% | ALTA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 45 | 0,00% | 0,00 | -3,90% | -2,99% | ALTA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 16 | 0,00% | 0,00 | -3,20% | -2,75% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 36 | 0,00% | 0,00 | -3,20% | -2,20% | ALTA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 12 | 16,67% | 0,13 | -2,84% | -1,93% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 13 | 15,38% | 0,17 | -2,75% | -1,83% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -2,49% | -1,77% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 21 | 33,33% | 0,46 | -2,80% | -1,36% | ALTA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 10 | 0,00% | 0,00 | -1,07R | -1,07R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -0,99R | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 17 | 35,29% | 0,45 | -2,78% | -0,95% | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 14 | 21,43% | 0,53 | -0,40R | -0,80R | MEDIA |
| Bilanciata 1H V3 Filtered | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 13 | 15,38% | 0,33 | -0,60R | -0,78R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | PEPE | 10 | 10,00% | 0,14 | -0,85R | -0,75R | MEDIA |
| SHADOW_COMBO_TREND | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 8 | 12,50% | 0,29 | -0,67R | -0,75R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 12 | 8,33% | 0,19 | -0,77R | -0,71R | MEDIA |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 10 | 20,00% | 0,45 | -0,46R | -0,71R | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 10 | 20,00% | 0,34 | -1,70% | -0,70% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 23 | 13,04% | 0,27 | -0,68R | -0,68R | ALTA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 21 | 33,33% | 0,46 | -1,40% | -0,68% | ALTA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | <5 | 24 | 8,33% | 0,20 | -0,73R | -0,67R | ALTA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 13 | 23,08% | 0,64 | -0,27R | -0,66R | MEDIA |
| SHADOW_EMA_TREND_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 9 | 11,11% | 0,29 | -0,59R | -0,64R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
