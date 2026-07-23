# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-23T01:01:57+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **999**
- Trade Shadow/Research chiusi: **1888**
- Eventi Shadow già presi dai Paper: **652**
- Eventi Shadow saltati dai Paper: **1236**
- Profili con filtro Paper utile: **9**
- Profili in cui il Paper potrebbe scartare edge: **7**
- Profili con campione ancora insufficiente: **68**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 — madre | 54 | 152 | 31 | 121 | -0,28R | -0,03R | -0,25R | -0,08R | +0,20R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 31 | 132 | 9 | 123 | -0,49R | -0,00R | -0,49R | 0,14R | +0,63R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 22 | 93 | 6 | 87 | -0,72R | 0,01R | -0,73R | -0,06R | +0,65R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 20 | 73 | 12 | 61 | 0,19R | 0,18R | +0,02R | 0,24R | +0,04R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 47 | 64 | 30 | 34 | 0,11R | -0,12R | +0,22R | -0,00R | -0,11R | FILTRO PAPER UTILE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 15 | 64 | 7 | 57 | -0,31R | 0,08R | -0,38R | -0,07R | +0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 28 | 58 | 14 | 44 | 0,09R | 0,38R | -0,29R | 0,36R | +0,27R | PAPER SCARTA EDGE |
| SHADOW_COMBO_TREND | Combo Trend | 17 | 57 | 8 | 49 | 0,14R | 0,07R | +0,08R | -0,06R | -0,20R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 20 | 45 | 13 | 32 | 0,26R | 0,46R | -0,20R | 0,41R | +0,15R | PAPER SCARTA EDGE |
| SHADOW_COMBO_SCANNER | Combo Scanner | 21 | 44 | 10 | 34 | -0,27R | 0,56R | -0,83R | -0,09R | +0,18R | PAPER SCARTA EDGE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 29 | 41 | 18 | 23 | 0,28R | -0,01R | +0,29R | 0,20R | -0,09R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 27 | 41 | 11 | 30 | -0,50R | 0,35R | -0,85R | -0,24R | +0,27R | PAPER SCARTA EDGE |
| MAIN | Principale 4H | 17 | 39 | 13 | 26 | -0,10R | -0,10R | -0,01R | -0,17R | -0,07R | NESSUN EDGE CHIARO |
| SHADOW_4H_WIDE | Ampia 4H | 12 | 38 | 9 | 29 | 0,25R | -0,23R | +0,48R | 0,15R | -0,09R | FILTRO PAPER UTILE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 17 | 33 | 11 | 22 | 0,53R | -0,28R | +0,81R | 0,19R | -0,34R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 19 | 32 | 12 | 20 | -0,71R | -0,08R | -0,63R | -0,30R | +0,41R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 23 | 30 | 16 | 14 | 0,37R | 0,10R | +0,26R | 0,11R | -0,26R | SELEZIONE POSITIVA |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 20 | 29 | 20 | 9 | 0,17R | -0,24R | +0,41R | 0,12R | -0,05R | FILTRO PAPER UTILE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 20 | 23 | 13 | 10 | 0,18R | 0,44R | -0,26R | 0,01R | -0,17R | PAPER SCARTA EDGE |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 21 | 22 | 12 | 10 | 0,15R | -0,81R | +0,96R | -0,13R | -0,28R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 16 | 22 | 6 | 16 | 0,14R | -0,44R | +0,59R | -0,13R | -0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 20 | 22 | 15 | 7 | 0,08R | -1,06R | +1,14R | -0,18R | -0,26R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 19 | 22 | 12 | 10 | 0,16R | -0,81R | +0,97R | -0,16R | -0,32R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 15 | 21 | 6 | 15 | -0,11R | -0,67R | +0,56R | -0,18R | -0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 18 | 21 | 12 | 9 | 0,16R | -0,78R | +0,94R | -0,11R | -0,27R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 10 | 19 | 6 | 13 | -0,06R | -0,39R | +0,33R | -0,38R | -0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 8 | 16 | 7 | 9 | -0,21R | -0,73R | +0,53R | -0,21R | +0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 19 | 15 | 12 | 3 | 0,16R | -1,06R | +1,21R | -0,11R | -0,26R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 3R | 8 | 13 | 4 | 9 | -0,07R | -0,62R | +0,54R | -0,22R | -0,15R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 8 | 13 | 4 | 9 | -0,07R | -0,62R | +0,54R | -0,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 5 | 11 | 3 | 8 | -0,05R | -0,34R | +0,28R | -0,53R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 10 | 10 | 7 | 3 | -0,38R | -1,11R | +0,73R | -0,20R | +0,18R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 9 | 10 | 8 | 2 | -0,10R | 1,54R | -1,64R | 0,20R | +0,30R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 9 | 9 | 8 | 1 | -0,48R | -1,09R | +0,61R | -0,56R | -0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 9 | 9 | 8 | 1 | -0,48R | -1,09R | +0,61R | -0,33R | +0,14R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 5 | 8 | 2 | 6 | 0,49R | -0,52R | +1,01R | -0,14R | -0,63R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 6 | 7 | 6 | 1 | -0,04R | -1,40R | +1,36R | -0,59R | -0,54R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 6 | 7 | 5 | 2 | -0,49R | -1,05R | +0,55R | -0,58R | -0,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 10 | 6 | 3 | 3 | -1,08R | -1,07R | -0,01R | -0,62R | +0,47R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 4 | 6 | 3 | 3 | -1,08R | -1,07R | -0,02R | -1,08R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 4 | 6 | 3 | 3 | -1,08R | -1,07R | -0,01R | -1,08R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 4 | 6 | 3 | 3 | -1,08R | -1,05R | -0,04R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 4 | 6 | 3 | 3 | -1,08R | -1,07R | -0,01R | -1,08R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 6 | 6 | 5 | 1 | -1,06R | -1,08R | +0,02R | -0,81R | +0,25R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 5 | 6 | 5 | 1 | -1,06R | -1,08R | +0,02R | -1,13R | -0,07R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 6 | 6 | 2 | 4 | 0,93R | -1,05R | +1,98R | -0,05R | -0,98R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 6 | 6 | 2 | 4 | 0,93R | -1,05R | +1,98R | -0,05R | -0,98R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 2 | 5 | 2 | 3 | 0,53R | -1,04R | +1,57R | 0,04R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 2 | 5 | 2 | 3 | 0,53R | -1,04R | +1,57R | 0,04R | -0,48R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 5 | 4 | 4 | 0 | -0,51R | 0,00R | -0,51R | -0,22R | +0,29R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 4 | 4 | 4 | 0 | -0,36R | 0,00R | -0,36R | -0,32R | +0,04R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 3 | 3 | 1 | 2 | -1,02R | 0,15R | -1,17R | -0,41R | +0,61R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_PARTIAL_1R_V1 | Combo Adaptive — Quality7 + Regime + parziale 1R | 3 | 3 | 3 | 0 | -1,07R | 0,00R | -1,07R | -1,07R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_V1 | Combo Adaptive — Quality7 + Regime | 3 | 3 | 3 | 0 | -1,07R | 0,00R | -1,07R | -1,07R | -0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_V1 | Combo Adaptive — Quality7 | 3 | 3 | 3 | 0 | -1,07R | 0,00R | -1,07R | -0,68R | +0,39R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 3 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | -0,11R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_MFE_V1 | Top 5 + BTC — Guard + BTC≤3 + MFE | 3 | 3 | 1 | 2 | -1,01R | -1,05R | +0,03R | -0,85R | +0,16R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_V1 | Top 5 + BTC — Guard + BTC≤3 | 2 | 3 | 1 | 2 | -1,01R | -1,05R | +0,03R | -1,19R | -0,17R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 2 | 2 | 2 | 0 | 0,97R | 0,00R | +0,97R | 0,26R | -0,71R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 2 | 2 | 2 | 0 | 1,37R | 0,00R | +1,37R | 1,00R | -0,37R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 3 | 2 | 2 | 0 | -1,12R | 0,00R | -1,12R | -0,41R | +0,71R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 3 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,25R | -0,64R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 5 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,44R | -0,83R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,18R | -0,57R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,09R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 2 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,12R | +1,00R | CAMPIONE INSUFFICIENTE |
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
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 42 | 86 | 35 | 51 | -1,47% | -0,44% | -1,03% | -1,16% | +0,31% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 42 | 86 | 35 | 51 | -2,94% | -0,88% | -2,06% | -2,32% | +0,62% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 26 | 61 | 17 | 44 | -0,61% | -1,28% | +0,67% | -0,84% | -0,23% | SELEZIONE POSITIVA |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 23 | 41 | 21 | 20 | -1,40% | 0,32% | -1,72% | -1,29% | +0,11% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 23 | 41 | 21 | 20 | -2,80% | 0,64% | -3,44% | -2,58% | +0,22% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 17 | 36 | 14 | 22 | 0,43% | -0,40% | +0,83% | 0,10% | -0,33% | FILTRO PAPER UTILE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 6 | 16 | 6 | 10 | 1,11% | -0,90% | +2,01% | 1,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 6 | 16 | 6 | 10 | 2,22% | -1,80% | +4,02% | 2,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 3 | 14 | 3 | 11 | 2,33% | -0,03% | +2,36% | 2,33% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 4 | 4 | 4 | 0 | -2,02% | 0,00% | -2,02% | -2,02% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 4 | 4 | 4 | 0 | -4,05% | 0,00% | -4,05% | -4,05% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 3 | 4 | 3 | 1 | -3,20% | -0,17% | -3,03% | -3,20% | 0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| RSI 25 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -7,80% | -7,50% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 24 | 0,00% | 0,00 | -7,80% | -6,68% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 51 | 0,00% | 0,00 | -7,80% | -6,09% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 13 | 15,38% | 0,11 | -5,85% | -4,13% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -4,98% | -3,86% | MEDIA |
| RSI 25 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -3,90% | -3,75% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 24 | 0,00% | 0,00 | -3,90% | -3,34% | ALTA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 18 | 0,00% | 0,00 | -3,20% | -3,12% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 51 | 0,00% | 0,00 | -3,90% | -3,04% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 16 | 25,00% | 0,31 | -4,05% | -2,33% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 8 | 25,00% | 0,31 | -4,05% | -2,33% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 41 | 0,00% | 0,00 | -3,20% | -2,11% | ALTA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 13 | 15,38% | 0,11 | -2,93% | -2,07% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -2,49% | -1,93% | MEDIA |
| RSI 25 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 8 | 37,50% | 0,55 | -2,18% | -1,88% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 16 | 25,00% | 0,31 | -2,03% | -1,17% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 8 | 25,00% | 0,31 | -2,03% | -1,17% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 10 | 0,00% | 0,00 | -1,07R | -1,04R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -1,01R | MEDIA |
| RSI 25 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 8 | 37,50% | 0,55 | -1,09% | -0,94% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 23 | 39,13% | 0,59 | -1,93% | -0,81% | ALTA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | PEPE | 10 | 10,00% | 0,14 | -0,85R | -0,77R | MEDIA |
| Bilanciata 1H V3 Filtered | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 14 | 14,29% | 0,30 | -0,63R | -0,75R | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 11 | 18,18% | 0,30 | -1,84% | -0,74% | MEDIA |
| SHADOW_COMBO_TREND | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 8 | 12,50% | 0,29 | -0,67R | -0,74R | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 25 | 16,00% | 0,27 | -1,79% | -0,69% | ALTA |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 12 | 16,67% | 0,36 | -0,56R | -0,68R | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 18 | 27,78% | 0,62 | -0,30R | -0,67R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 23 | 13,04% | 0,27 | -0,68R | -0,65R | ALTA |
| SHADOW_DONCHIAN_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 8 | 12,50% | 0,32 | -0,64R | -0,63R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
