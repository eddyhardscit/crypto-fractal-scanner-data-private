# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-25T03:21:20+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **1467**
- Trade Shadow/Research chiusi: **2996**
- Eventi Shadow già presi dai Paper: **907**
- Eventi Shadow saltati dai Paper: **2089**
- Profili con filtro Paper utile: **11**
- Profili in cui il Paper potrebbe scartare edge: **5**
- Profili con campione ancora insufficiente: **76**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 — madre | 72 | 192 | 35 | 157 | -0,37R | 0,03R | -0,40R | -0,05R | +0,32R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 39 | 157 | 10 | 147 | -0,26R | 0,01R | -0,27R | 0,23R | +0,48R | SELEZIONE DA RIVEDERE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 24 | 110 | 6 | 104 | -0,72R | 0,03R | -0,74R | -0,06R | +0,65R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive — madre | 22 | 105 | 12 | 93 | 0,19R | 0,08R | +0,11R | 0,24R | +0,05R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered — madre | 64 | 99 | 36 | 63 | 0,12R | -0,05R | +0,17R | 0,01R | -0,11R | FILTRO PAPER UTILE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 19 | 83 | 7 | 76 | -0,31R | 0,05R | -0,36R | 0,00R | +0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_TREND | Combo Trend | 29 | 78 | 12 | 66 | -0,24R | 0,07R | -0,31R | 0,00R | +0,25R | SELEZIONE DA RIVEDERE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 31 | 74 | 16 | 58 | 0,14R | 0,20R | -0,06R | 0,46R | +0,32R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive — MFE Trail esistente | 27 | 72 | 12 | 60 | -0,55R | 0,14R | -0,70R | -0,24R | +0,32R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 34 | 62 | 19 | 43 | 0,21R | 0,13R | +0,08R | 0,23R | +0,02R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 24 | 62 | 12 | 50 | 0,12R | 0,30R | -0,18R | 0,10R | -0,02R | PAPER SCARTA EDGE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 23 | 61 | 13 | 48 | 0,26R | 0,23R | +0,03R | 0,42R | +0,16R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_NO_PEPE_V1 | Rapida V1 — senza PEPE | 32 | 59 | 16 | 43 | -0,14R | -0,02R | -0,11R | -0,01R | +0,13R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_V3_NO_ESPORTS_V1 | Rapida V3 — senza ESPORTS | 37 | 55 | 24 | 31 | 0,07R | -0,18R | +0,25R | -0,04R | -0,11R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_NOHIGH_V1 | Rapida V3 — no volatilità HIGH | 38 | 54 | 26 | 28 | 0,08R | -0,17R | +0,25R | -0,05R | -0,13R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_NOHIGH_CAP75_V1 | Rapida V1 — no HIGH + score <7,5 | 33 | 53 | 18 | 35 | 0,16R | 0,01R | +0,15R | 0,08R | -0,08R | NESSUN EDGE CHIARO |
| MAIN | Principale 4H | 18 | 52 | 14 | 38 | 0,04R | 0,00R | +0,04R | -0,05R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_1H_FAST_TP2_V1 | Rapida V1 — target pieno 2R | 33 | 49 | 13 | 36 | 0,30R | -0,31R | +0,61R | -0,09R | -0,38R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | Combo Adaptive — parziale 1R | 12 | 48 | 6 | 42 | -0,06R | -0,14R | +0,08R | -0,23R | -0,17R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_CAP75_V1 | Rapida V3 — score <7,5 | 28 | 46 | 17 | 29 | 0,23R | -0,11R | +0,34R | 0,13R | -0,09R | FILTRO PAPER UTILE |
| SHADOW_4H_WIDE | Ampia 4H | 14 | 43 | 9 | 34 | 0,25R | -0,01R | +0,26R | -0,02R | -0,27R | FILTRO PAPER UTILE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 19 | 43 | 12 | 31 | 0,40R | -0,27R | +0,68R | 0,16R | -0,25R | FILTRO PAPER UTILE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 34 | 41 | 21 | 20 | 0,34R | 0,40R | -0,06R | 0,09R | -0,25R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 23 | 41 | 15 | 26 | -0,39R | 0,18R | -0,57R | -0,19R | +0,20R | PAPER SCARTA EDGE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 27 | 38 | 18 | 20 | 0,17R | 0,59R | -0,42R | 0,07R | -0,10R | PAPER SCARTA EDGE |
| SHADOW_1H_FAST_SCORE_6_75_V1 | Rapida V1 — score 6–7,5 | 34 | 38 | 23 | 15 | 0,43R | -0,22R | +0,66R | 0,17R | -0,26R | FILTRO PAPER UTILE |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 28 | 38 | 25 | 13 | 0,12R | -0,30R | +0,42R | 0,05R | -0,07R | FILTRO PAPER UTILE |
| SHADOW_COMBO_ADAPTIVE_RUNNER25_V1 | Combo Adaptive — 75% a 2R + runner 25% a 3R | 15 | 32 | 6 | 26 | -0,41R | -0,45R | +0,04R | 0,03R | +0,45R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_TP3_V1 | Combo Adaptive — target pieno 3R | 10 | 32 | 5 | 27 | -0,28R | -0,47R | +0,19R | -0,02R | +0,26R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_ONLY_V1 | Rapida V3 — Long Only | 24 | 29 | 17 | 12 | -0,17R | -0,42R | +0,25R | -0,19R | -0,02R | SELEZIONE POSITIVA |
| SHADOW_COMBO_ADAPTIVE_LONG_ONLY_V1 | Combo Adaptive — Long Only | 5 | 27 | 3 | 24 | -0,05R | -0,30R | +0,25R | -0,53R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_REGIME_V1 | Combo Adaptive — Trend/Transition | 10 | 26 | 8 | 18 | 0,06R | -0,90R | +0,96R | -0,04R | -0,10R | FILTRO PAPER UTILE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_LOCK_V1 | Rapida V3 — qualità completa + profit lock | 22 | 23 | 18 | 5 | -0,08R | -0,05R | -0,03R | -0,18R | -0,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_LONG_NOHIGH_CAP75_V1 | Rapida V3 — Long + no HIGH + score <7,5 | 21 | 23 | 18 | 5 | -0,08R | -0,05R | -0,03R | -0,16R | -0,08R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_MFE_V1 | Top 5 + BTC — solo MFE | 14 | 23 | 6 | 17 | -0,53R | -0,10R | -0,43R | -0,41R | +0,11R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_EXPANDED_V1 | Master Adaptive Expanded V1 | 8 | 22 | 5 | 17 | -0,49R | -0,33R | -0,17R | -0,32R | +0,17R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_V1 | Master Adaptive Gb20 V1 | 34 | 22 | 8 | 14 | -1,04R | -0,19R | -0,85R | -0,18R | +0,86R | SELEZIONE DA RIVEDERE |
| SHADOW_MASTER_ADAPTIVE_NO_ALT_V1 | Master Adaptive No Alt V1 | 6 | 22 | 3 | 19 | -1,08R | -0,40R | -0,68R | -0,58R | +0,51R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_STRICT3_V1 | Master Adaptive Strict3 V1 | 15 | 22 | 11 | 11 | -0,77R | -0,22R | -0,55R | -0,59R | +0,18R | SELEZIONE DA RIVEDERE |
| SHADOW_MASTER_ADAPTIVE_V1 | Master Adaptive V1 | 6 | 22 | 3 | 19 | -1,08R | -0,40R | -0,68R | -0,58R | +0,51R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_LE3_V1 | Top 5 + BTC — BTC≤3 | 5 | 20 | 3 | 17 | -0,02R | -0,28R | +0,26R | 0,32R | +0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_MFE_V1 | Top 5 + BTC — Guard + MFE | 19 | 18 | 9 | 9 | -0,33R | -0,31R | -0,02R | -0,41R | -0,08R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC_GUARD_V1 | Top 5 + BTC — Guard | 8 | 18 | 6 | 12 | -0,52R | -0,22R | -0,30R | -0,14R | +0,38R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_RUNNER25_V1 | Master Adaptive Runner25 V1 | 6 | 17 | 3 | 14 | -1,08R | -0,19R | -0,90R | -0,59R | +0,50R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 14 | 16 | 12 | 4 | -0,22R | 0,23R | -0,45R | -0,01R | +0,21R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_MFE_V1 | Top 5 + BTC — Guard + BTC≤3 + MFE | 16 | 15 | 5 | 10 | 0,27R | -0,38R | +0,65R | -0,34R | -0,61R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_GUARD_BTC_LE3_V1 | Top 5 + BTC — Guard + BTC≤3 | 5 | 15 | 2 | 13 | 0,59R | -0,28R | +0,87R | 0,44R | -0,15R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_RUNNER25_V1 | Top 5 + BTC — 75% a 2,2R + runner 3R | 9 | 15 | 4 | 11 | 0,93R | -0,69R | +1,62R | 0,44R | -0,49R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_TP3_V1 | Top 5 + BTC — target pieno 3R | 8 | 15 | 4 | 11 | 0,93R | -0,69R | +1,62R | 0,36R | -0,58R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_LONG_BTC_1_3_CAP75_V1 | Rapida V1 — Long + BTC 1–3 + score <7,5 | 11 | 13 | 8 | 5 | 0,23R | 0,43R | -0,20R | -0,02R | -0,26R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC_BTC_2_3_V1 | Top 5 + BTC — BTC 2–3 | 4 | 11 | 4 | 7 | -0,27R | -0,14R | -0,13R | -0,34R | -0,07R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 10 | 10 | 10 | 0 | -0,61R | 0,00R | -0,61R | -0,10R | +0,51R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 5 | 9 | 5 | 4 | -0,02R | -0,98R | +0,95R | -0,46R | -0,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_V1 | Combo Adaptive — Quality7 | 9 | 9 | 7 | 2 | 0,24R | -1,02R | +1,26R | 0,06R | -0,18R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 6 | 7 | 6 | 1 | -0,04R | -1,40R | +1,36R | -0,59R | -0,54R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_PARTIAL_1R_V1 | Combo Adaptive — Quality7 + Regime + parziale 1R | 5 | 5 | 5 | 0 | -0,46R | 0,00R | -0,46R | -0,33R | +0,13R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_QUALITY7_REGIME_V1 | Combo Adaptive — Quality7 + Regime | 5 | 5 | 5 | 0 | -0,46R | 0,00R | -0,46R | -0,58R | -0,12R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 5 | 5 | 3 | 2 | -0,11R | 0,39R | -0,50R | -0,44R | -0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 4 | 4 | 4 | 0 | -1,12R | 0,00R | -1,12R | -0,09R | +1,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 5 | 4 | 4 | 0 | -0,36R | 0,00R | -0,36R | -0,13R | +0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 4 | 4 | 2 | 2 | 0,39R | -1,11R | +1,50R | -0,46R | -0,85R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 6 | 4 | 2 | 2 | 0,39R | -1,11R | +1,49R | -0,55R | -0,94R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 4 | 4 | 4 | 0 | 0,39R | 0,00R | +0,39R | 0,16R | -0,23R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 3 | 3 | 3 | 0 | -1,11R | 0,00R | -1,11R | 0,09R | +1,20R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 7 | 3 | 3 | 0 | 0,89R | 0,00R | +0,89R | 0,42R | -0,46R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 3 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | -0,11R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 9 | 3 | 2 | 1 | 0,16R | 2,40R | -2,24R | -0,34R | -0,50R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 3 | 3 | 3 | 0 | -0,12R | 0,00R | -0,12R | 0,61R | +0,73R | CAMPIONE INSUFFICIENTE |
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
| MAIN_DYNAMIC_ASSET_SELECTOR_V1 | MAIN — Dynamic Asset Selector | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| MAIN_SIDE_REGIME_GUARD_V1 | MAIN — Side × Regime Guard | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_BALANCED_LONG_NO_RHV_V1 | Bilanciata 1H — LONG senza Range High Vol | 1 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -1,40R | -1,40R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_BALANCED_SHORT_TREND_DOWN_STRICT_V1 | Bilanciata 1H — SHORT Trend Down stretto | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_COST_AWARE_V1 | Rapida score 6–7,5 — Cost Aware | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_NO_TREND_UP_V1 | Rapida score 6–7,5 — senza Trend Up | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_SCORE_6_75_RANGE_ONLY_V1 | Rapida score 6–7,5 — Range Only | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NOHIGH_RANGE_ONLY_V1 | Rapida V3 NoHigh — Range Only | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NOHIGH_REGIME_GUARD_V1 | Rapida V3 NoHigh — Regime Guard | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_LONG_ONLY_V1 | Rapida V3 senza ESPORTS — Long Only | 1 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -1,47R | -1,47R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_MFE_LOCK_V1 | Rapida V3 senza ESPORTS — MFE Lock | 3 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,04R | -0,04R | CAMPIONE INSUFFICIENTE |
| SHADOW_1H_FAST_V3_NO_ESPORTS_STRESS_GUARD_V1 | Rapida V3 senza ESPORTS — Stress Guard | 1 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -1,09R | -1,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_SIDE_REGIME_GUARD_V1 | Combo Adaptive — Side × Regime Guard | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_TREND_SIDE_REGIME_GUARD_V1 | Combo Trend — Side × Regime Guard | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_BE_V1 | Master Adaptive GB20 — Breakeven 0,5R | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_LOSS_CAP_V1 | Master Adaptive GB20 — Loss Cap 0,75R | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_MASTER_ADAPTIVE_GB20_PARTIAL_V1 | Master Adaptive GB20 — 50% a 0,75R | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 49 | 100 | 42 | 58 | -0,98% | -0,47% | -0,51% | -0,79% | +0,20% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 49 | 100 | 42 | 58 | -1,96% | -0,94% | -1,02% | -1,57% | +0,39% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 32 | 76 | 23 | 53 | 0,05% | -0,90% | +0,96% | -0,32% | -0,37% | FILTRO PAPER UTILE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 25 | 46 | 23 | 23 | -1,29% | 0,42% | -1,71% | -1,20% | +0,09% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 25 | 46 | 23 | 23 | -2,58% | 0,84% | -3,43% | -2,40% | +0,18% | PAPER SCARTA EDGE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 19 | 41 | 16 | 25 | 0,45% | 0,16% | +0,28% | 0,14% | -0,30% | SELEZIONE POSITIVA |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 6 | 33 | 6 | 27 | 1,11% | -1,40% | +2,51% | 1,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 6 | 33 | 6 | 27 | 2,22% | -2,80% | +5,02% | 2,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 3 | 31 | 3 | 28 | 2,33% | -1,22% | +3,56% | 2,33% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 7 | 12 | 6 | 6 | -1,40% | -3,90% | +2,50% | -1,76% | -0,36% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 7 | 12 | 6 | 6 | -2,80% | -7,80% | +5,00% | -3,51% | -0,71% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 6 | 12 | 5 | 7 | -3,20% | -2,77% | -0,43% | -3,20% | +0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -7,80% | -6,94% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 57 | 0,00% | 0,00 | -7,80% | -6,43% | ALTA |
| RSI 25 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 20 | 0,00% | 0,00 | -7,80% | -5,91% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 15 | 20,00% | 0,18 | -5,11% | -3,74% | MEDIA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 19 | 0,00% | 0,00 | -3,20% | -3,48% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -3,90% | -3,47% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 10 | 20,00% | 0,23 | -4,80% | -3,43% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 57 | 0,00% | 0,00 | -3,90% | -3,22% | ALTA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -4,05% | -3,18% | MEDIA |
| RSI 25 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 20 | 0,00% | 0,00 | -3,90% | -2,95% | ALTA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 10 | 30,00% | 0,31 | -3,76% | -2,89% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 46 | 0,00% | 0,00 | -3,20% | -2,59% | ALTA |
| RSI 20 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 10 | 0,00% | 0,00 | -7,80% | -2,50% | MEDIA |
| RSI 25 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 18 | 0,00% | 0,00 | -3,20% | -2,32% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 18 | 27,78% | 0,36 | -3,63% | -2,26% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 15 | 20,00% | 0,18 | -2,55% | -1,87% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | DOGE | 10 | 20,00% | 0,23 | -2,40% | -1,72% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -2,03% | -1,59% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 10 | 30,00% | 0,31 | -1,88% | -1,45% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 24 | 37,50% | 0,55 | -2,17% | -1,31% | ALTA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,51 | -1,02% | -1,30% | MEDIA |
| RSI 20 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 10 | 0,00% | 0,00 | -3,90% | -1,25% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 18 | 27,78% | 0,36 | -1,82% | -1,13% | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 5–6 | 8 | 0,00% | 0,00 | -1,03R | -1,07R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | MEDIA | 8 | 0,00% | 0,00 | -1,03R | -1,07R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,07R | -1,07R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 11 | 0,00% | 0,00 | -1,09R | -1,05R | MEDIA |
| SHADOW_COMBO_ADAPTIVE_PARTIAL_1R_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 0,00% | 0,00 | -1,07R | -0,94R | MEDIA |
| SHADOW_1H_FAST_SCORE_6_75_V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 12,50% | 0,18 | -0,76R | -0,94R | MEDIA |
| SHADOW_SCANNER_BOTTOM5_SHORT | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 8 | 0,00% | 0,00 | -0,89R | -0,87R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
