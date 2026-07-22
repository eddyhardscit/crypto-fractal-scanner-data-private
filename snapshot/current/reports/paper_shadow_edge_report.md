# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-22T06:53:11+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **838**
- Trade Shadow/Research chiusi: **1599**
- Eventi Shadow già presi dai Paper: **545**
- Eventi Shadow saltati dai Paper: **1054**
- Profili con filtro Paper utile: **6**
- Profili in cui il Paper potrebbe scartare edge: **4**
- Profili con campione ancora insufficiente: **70**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 — madre | 51 | 143 | 29 | 114 | -0,31R | -0,01R | -0,30R | -0,06R | +0,25R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 27 | 123 | 8 | 115 | -0,42R | 0,02R | -0,43R | 0,16R | +0,58R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 20 | 82 | 6 | 76 | -0,72R | -0,01R | -0,70R | -0,01R | +0,70R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 18 | 65 | 12 | 53 | 0,19R | 0,31R | -0,11R | 0,32R | +0,12R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 44 | 57 | 28 | 29 | 0,10R | -0,13R | +0,23R | 0,03R | -0,08R | FILTRO PAPER UTILE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 12 | 57 | 5 | 52 | -0,64R | 0,12R | -0,76R | 0,05R | +0,69R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 28 | 55 | 14 | 41 | 0,09R | 0,49R | -0,40R | 0,36R | +0,27R | PAPER SCARTA EDGE |
| SHADOW_COMBO_TREND | Combo Trend | 16 | 52 | 8 | 44 | 0,14R | 0,12R | +0,02R | 0,01R | -0,13R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 20 | 42 | 12 | 30 | 0,38R | 0,45R | -0,08R | 0,41R | +0,04R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 20 | 39 | 8 | 31 | -0,24R | 0,61R | -0,86R | -0,03R | +0,21R | PAPER SCARTA EDGE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 28 | 37 | 17 | 20 | 0,36R | 0,00R | +0,36R | 0,24R | -0,12R | SELEZIONE POSITIVA |
| MAIN | Principale 4H | 17 | 36 | 12 | 24 | -0,03R | -0,15R | +0,12R | -0,17R | -0,15R | NESSUN EDGE CHIARO |
| SHADOW_4H_WIDE | Ampia 4H | 12 | 36 | 9 | 27 | 0,25R | -0,32R | +0,56R | 0,15R | -0,09R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 26 | 35 | 10 | 25 | -0,45R | 0,51R | -0,95R | -0,24R | +0,20R | PAPER SCARTA EDGE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 17 | 31 | 11 | 20 | 0,53R | -0,37R | +0,91R | 0,19R | -0,34R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 16 | 27 | 11 | 16 | -0,68R | -0,02R | -0,66R | -0,31R | +0,38R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 19 | 26 | 14 | 12 | 0,57R | -0,23R | +0,80R | 0,12R | -0,45R | FILTRO PAPER UTILE |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 18 | 26 | 17 | 9 | 0,10R | -0,24R | +0,34R | 0,12R | +0,02R | FILTRO PAPER UTILE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 17 | 21 | 12 | 9 | 0,03R | 0,61R | -0,58R | -0,06R | -0,09R | PAPER SCARTA EDGE |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 13 | 16 | 11 | 5 | -0,17R | -1,07R | +0,90R | -0,21R | -0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 12 | 16 | 8 | 8 | -0,15R | -0,76R | +0,62R | -0,18R | -0,03R | SELEZIONE POSITIVA |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 12 | 15 | 8 | 7 | -0,15R | -0,71R | +0,57R | -0,18R | -0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 14 | 14 | 7 | 7 | -0,01R | -0,72R | +0,71R | -0,26R | -0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 10 | 14 | 6 | 8 | 0,14R | -0,75R | +0,89R | 0,02R | -0,12R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 9 | 14 | 5 | 9 | 0,09R | -0,74R | +0,83R | 0,09R | +0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 8 | 11 | 5 | 6 | -0,46R | -0,08R | -0,37R | -0,20R | +0,25R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 13 | 10 | 8 | 2 | -0,15R | -1,08R | +0,93R | -0,16R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 7 | 10 | 5 | 5 | -0,46R | -0,48R | +0,02R | -0,26R | +0,20R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 4 | 8 | 3 | 5 | -0,05R | -0,48R | +0,43R | -0,40R | -0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 7 | 8 | 6 | 2 | 0,23R | 1,54R | -1,31R | 0,56R | +0,34R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 6 | 7 | 6 | 1 | -0,04R | -1,40R | +1,36R | -0,59R | -0,54R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 7 | 7 | 4 | 3 | -0,49R | -1,11R | +0,62R | -0,16R | +0,33R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 3R | 6 | 7 | 4 | 3 | -0,07R | -1,05R | +0,97R | 0,06R | +0,13R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 5 | 7 | 4 | 3 | -0,07R | -1,05R | +0,97R | -0,30R | -0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 6 | 6 | 5 | 1 | -0,62R | -1,09R | +0,47R | -0,48R | +0,14R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 6 | 6 | 5 | 1 | -0,62R | -1,09R | +0,47R | -0,34R | +0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 4 | 5 | 1 | 4 | 2,09R | -1,05R | +3,14R | -0,13R | -2,22R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 3 | 4 | 3 | 1 | -1,08R | -1,01R | -0,07R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 6 | 4 | 3 | 1 | -1,08R | -1,01R | -0,07R | -0,73R | +0,35R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 3 | 4 | 3 | 1 | -1,08R | -1,01R | -0,07R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 3 | 4 | 3 | 1 | -1,08R | -1,01R | -0,07R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 3 | 4 | 2 | 2 | -1,09R | -1,06R | -0,02R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 3 | 4 | 3 | 1 | -1,08R | -1,01R | -0,07R | -1,09R | -0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 5 | 4 | 4 | 0 | -1,04R | 0,00R | -1,04R | -0,93R | +0,11R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 5 | 4 | 4 | 0 | -1,04R | 0,00R | -1,04R | -1,13R | -0,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 6 | 4 | 1 | 3 | -1,07R | -1,05R | -0,02R | -0,05R | +1,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 6 | 4 | 1 | 3 | -1,07R | -1,05R | -0,02R | -0,05R | +1,01R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 3 | 3 | 3 | 0 | -0,31R | 0,00R | -0,31R | 0,03R | +0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 3 | 3 | 3 | 0 | -0,11R | 0,00R | -0,11R | -0,08R | +0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 3 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | -0,11R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 2 | 3 | 1 | 2 | -1,07R | -1,01R | -0,05R | 0,04R | +1,11R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 2 | 3 | 1 | 2 | -1,07R | -1,01R | -0,05R | 0,04R | +1,11R | CAMPIONE INSUFFICIENTE |
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
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 1 | 1 | 1 | 0 | 0,66R | 0,00R | +0,66R | 0,58R | -0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 2 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,12R | +1,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 1 | 1 | 1 | 0 | 1,37R | 0,00R | +1,37R | 1,37R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 2 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -0,31R | +0,82R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 4 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,26R | +0,85R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_BOLLINGER_1H | Eth Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | 0,31R | +1,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 7 | 1 | 1 | 0 | -1,10R | 0,00R | -1,10R | -0,65R | +0,45R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 2 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -0,03R | +1,10R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
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
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 33 | 74 | 28 | 46 | -1,40% | -0,55% | -0,84% | -0,87% | +0,53% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 33 | 74 | 28 | 46 | -2,80% | -1,11% | -1,69% | -1,74% | +1,06% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 21 | 54 | 13 | 41 | -0,39% | -1,14% | +0,75% | -0,63% | -0,24% | SELEZIONE POSITIVA |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 19 | 34 | 17 | 17 | -1,69% | -0,26% | -1,44% | -1,53% | +0,16% | SELEZIONE DA RIVEDERE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 19 | 34 | 17 | 17 | -3,39% | -0,52% | -2,87% | -3,06% | +0,33% | SELEZIONE DA RIVEDERE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 13 | 30 | 10 | 20 | 0,38% | -0,87% | +1,25% | -0,04% | -0,42% | FILTRO PAPER UTILE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 6 | 13 | 6 | 7 | 1,11% | -1,76% | +2,87% | 1,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 6 | 13 | 6 | 7 | 2,22% | -3,51% | +5,74% | 2,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 3 | 10 | 3 | 7 | 2,33% | 0,30% | +2,03% | 2,33% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 3 | 3 | 3 | 0 | -3,90% | 0,00% | -3,90% | -3,90% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 3 | 3 | 3 | 0 | -7,80% | 0,00% | -7,80% | -7,80% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 2 | 2 | 2 | 0 | -3,20% | 0,00% | -3,20% | -3,20% | 0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 44 | 0,00% | 0,00 | -7,80% | -6,06% | ALTA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 22 | 0,00% | 0,00 | -7,80% | -5,85% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 12 | 16,67% | 0,13 | -5,69% | -3,94% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 13 | 15,38% | 0,17 | -5,49% | -3,75% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 44 | 0,00% | 0,00 | -3,90% | -3,03% | ALTA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -4,98% | -3,03% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 22 | 0,00% | 0,00 | -3,90% | -2,93% | ALTA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 16 | 0,00% | 0,00 | -3,20% | -2,75% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 35 | 0,00% | 0,00 | -3,20% | -2,24% | ALTA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 12 | 16,67% | 0,13 | -2,84% | -1,97% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 13 | 15,38% | 0,17 | -2,75% | -1,87% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 9 | 22,22% | 0,18 | -2,49% | -1,51% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 10 | 0,00% | 0,00 | -1,07R | -1,06R | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 17 | 35,29% | 0,45 | -2,78% | -1,03% | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -1,02R | MEDIA |
| Bilanciata 1H V3 Filtered | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 11 | 9,09% | 0,18 | -0,79R | -0,96R | MEDIA |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 8 | 12,50% | 0,26 | -0,68R | -0,92R | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 21 | 33,33% | 0,46 | -2,80% | -0,85% | ALTA |
| SHADOW_COMBO_TREND | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 8 | 12,50% | 0,29 | -0,67R | -0,79R | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 13 | 23,08% | 0,58 | -0,35R | -0,79R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | PEPE | 10 | 10,00% | 0,14 | -0,85R | -0,78R | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 10 | 20,00% | 0,34 | -1,70% | -0,74% | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 12 | 8,33% | 0,19 | -0,77R | -0,71R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 13 | 23,08% | 0,64 | -0,27R | -0,70R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 23 | 13,04% | 0,27 | -0,68R | -0,67R | ALTA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 11 | 27,27% | 0,72 | -0,22R | -0,66R | MEDIA |
| SHADOW_EMA_TREND_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 9 | 11,11% | 0,29 | -0,59R | -0,64R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | <5 | 22 | 9,09% | 0,22 | -0,70R | -0,64R | ALTA |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP_HIGH_VOL | 9 | 22,22% | 0,52 | -0,39R | -0,63R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 15 | 26,67% | 0,78 | -0,16R | -0,59R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
