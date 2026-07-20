# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-20T11:33:57+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **419**
- Trade Shadow/Research chiusi: **893**
- Eventi Shadow già presi dai Paper: **282**
- Eventi Shadow saltati dai Paper: **611**
- Profili con filtro Paper utile: **2**
- Profili in cui il Paper potrebbe scartare edge: **5**
- Profili con campione ancora insufficiente: **45**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 | 40 | 108 | 22 | 86 | -0,22R | 0,06R | -0,28R | 0,08R | +0,30R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 18 | 99 | 6 | 93 | -0,20R | 0,07R | -0,27R | 0,21R | +0,41R | CAMPIONE INSUFFICIENTE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 15 | 62 | 3 | 59 | -1,03R | 0,21R | -1,24R | 0,14R | +1,18R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive | 14 | 51 | 11 | 40 | 0,04R | 0,45R | -0,41R | 0,36R | +0,32R | PAPER SCARTA EDGE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 8 | 46 | 3 | 43 | -1,04R | 0,15R | -1,19R | -0,04R | +1,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 21 | 46 | 12 | 34 | 0,04R | 0,55R | -0,50R | 0,31R | +0,27R | PAPER SCARTA EDGE |
| SHADOW_COMBO_TREND | Combo Trend | 13 | 40 | 8 | 32 | 0,14R | 0,16R | -0,02R | 0,18R | +0,04R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 15 | 35 | 10 | 25 | 0,56R | 0,50R | +0,06R | 0,53R | -0,04R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 14 | 33 | 8 | 25 | -0,24R | 0,76R | -1,00R | 0,20R | +0,44R | PAPER SCARTA EDGE |
| MAIN | Principale 4H | 15 | 27 | 12 | 15 | -0,03R | -0,22R | +0,20R | -0,06R | -0,03R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered | 30 | 27 | 18 | 9 | 0,35R | 0,05R | +0,31R | -0,09R | -0,44R | SELEZIONE POSITIVA |
| SHADOW_4H_WIDE | Ampia 4H | 11 | 24 | 9 | 15 | 0,25R | -0,01R | +0,25R | 0,26R | +0,01R | FILTRO PAPER UTILE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 19 | 23 | 14 | 9 | 0,46R | 0,30R | +0,16R | 0,29R | -0,17R | NESSUN EDGE CHIARO |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 14 | 22 | 14 | 8 | -0,01R | -0,44R | +0,44R | 0,23R | +0,24R | SELEZIONE POSITIVA |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive MFE Trail | 18 | 21 | 7 | 14 | -0,59R | 0,89R | -1,49R | -0,21R | +0,38R | CAMPIONE INSUFFICIENTE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 16 | 20 | 12 | 8 | 0,84R | 0,17R | +0,67R | 0,36R | -0,48R | SELEZIONE POSITIVA |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 12 | 20 | 9 | 11 | 0,12R | -0,11R | +0,23R | 0,39R | +0,27R | FILTRO PAPER UTILE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 8 | 17 | 6 | 11 | -0,38R | 0,01R | -0,38R | -0,06R | +0,32R | CAMPIONE INSUFFICIENTE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 16 | 15 | 10 | 5 | 0,15R | 0,76R | -0,61R | -0,08R | -0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 6 | 7 | 5 | 2 | -0,03R | 1,54R | -1,56R | 0,41R | +0,44R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 4 | 5 | 4 | 1 | -0,34R | -1,40R | +1,06R | -0,45R | -0,10R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 3 | 3 | 3 | 0 | -0,31R | 0,00R | -0,31R | 0,03R | +0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 2 | 2 | 2 | 0 | -1,11R | 0,00R | -1,11R | -1,09R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,18R | -0,57R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,09R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 1 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -1,09R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 1 | 1 | 1 | 0 | 1,37R | 0,00R | +1,37R | 1,37R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 1 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -1,10R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 1 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -1,10R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_BOLLINGER_1H | Eth Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | 0,31R | +1,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 3 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,67R | +0,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 4 | 1 | 1 | 0 | -1,10R | 0,00R | -1,10R | -0,32R | +0,78R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 1 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -0,09R | +1,04R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_4H | Btc Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_4H | Btc Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_4H | Btc Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_4H | Btc Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_BOLLINGER_1H | Doge Bollinger 1H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 2 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,31R | -0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 3 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,03R | +0,03R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_4H | Eth Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_4H | Sol Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_4H | Sol Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_4H | Sol Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_4H | Sol Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 12 | 33 | 11 | 22 | -1,17% | 0,71% | -1,88% | -0,77% | +0,40% | PAPER SCARTA EDGE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 12 | 33 | 11 | 22 | -2,35% | 1,42% | -3,77% | -1,55% | +0,80% | PAPER SCARTA EDGE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 8 | 19 | 7 | 12 | -0,55% | -1,19% | +0,64% | 0,06% | +0,61% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 8 | 10 | 8 | 2 | -2,96% | 2,45% | -5,41% | -2,96% | 0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 8 | 10 | 8 | 2 | -5,93% | 4,90% | -10,83% | -5,93% | -0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 5 | 9 | 5 | 4 | -1,22% | -1,97% | +0,75% | -1,22% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 4 | 5 | 4 | 1 | -0,13% | 3,60% | -3,73% | -0,13% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 4 | 5 | 4 | 1 | -0,26% | 7,19% | -7,46% | -0,26% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 2 | 2 | 2 | 0 | 1,99% | 0,00% | +1,99% | 1,99% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 14 | 0,00% | 0,00 | -7,80% | -7,97% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 14 | 0,00% | 0,00 | -3,90% | -3,99% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 11 | 0,00% | 0,00 | -3,20% | -2,25% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 13 | 38,46% | 0,72 | -1,07% | -1,24% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 9 | 0,00% | 0,00 | -1,08R | -1,14R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 10 | 0,00% | 0,00 | -1,10R | -1,10R | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 8 | 50,00% | 0,78 | -0,88% | -1,04% | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 10 | 20,00% | 0,48 | -0,45R | -0,96R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 10 | 20,00% | 0,49 | -0,44R | -0,96R | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 9 | 22,22% | 0,55 | -0,38R | -0,90R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 12 | 8,33% | 0,17 | -0,82R | -0,87R | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 9 | 11,11% | 0,22 | -1,74% | -0,79% | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | PEPE | 8 | 12,50% | 0,18 | -0,79R | -0,79R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 14 | 21,43% | 0,52 | -0,37R | -0,78R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 16 | 12,50% | 0,19 | -0,78R | -0,77R | MEDIA |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ESPORTS | 9 | 22,22% | 0,56 | -0,35R | -0,75R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 11 | 27,27% | 0,73 | -0,21R | -0,73R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 15 | 13,33% | 0,29 | -0,64R | -0,69R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 16 | 25,00% | 0,64 | -0,27R | -0,69R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | <5 | 12 | 16,67% | 0,42 | -0,50R | -0,65R | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 13 | 38,46% | 0,72 | -0,54% | -0,62% | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 11 | 18,18% | 0,47 | -0,44R | -0,59R | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 8 | 50,00% | 0,78 | -0,44% | -0,52% | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 18 | 22,22% | 0,61 | -0,31R | -0,47R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 17 | 23,53% | 0,64 | -0,29R | -0,44R | MEDIA |
| SHADOW_BOLLINGER_MR_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 10 | 20,00% | 0,35 | -0,56R | -0,40R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BASSA | 8 | 25,00% | 0,71 | -0,22R | -0,37R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 22 | 27,27% | 0,52 | -0,37R | -0,37R | ALTA |
| SHADOW_COMBO_TREND | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 11 | 27,27% | 0,76 | -0,19R | -0,35R | MEDIA |
| SHADOW_DONCHIAN_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 10 | 20,00% | 0,59 | -0,35R | -0,34R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
