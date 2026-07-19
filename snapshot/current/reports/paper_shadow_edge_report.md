# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-19T00:20:14+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **250**
- Trade Shadow/Research chiusi: **526**
- Eventi Shadow già presi dai Paper: **173**
- Eventi Shadow saltati dai Paper: **353**
- Profili con filtro Paper utile: **3**
- Profili in cui il Paper potrebbe scartare edge: **0**
- Profili con campione ancora insufficiente: **54**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 | 33 | 81 | 19 | 62 | -0,09R | -0,05R | -0,04R | 0,15R | +0,25R | NESSUN EDGE CHIARO |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 10 | 72 | 1 | 71 | -1,01R | -0,05R | -0,96R | 0,15R | +1,16R | CAMPIONE INSUFFICIENTE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 7 | 46 | 2 | 44 | -1,02R | 0,05R | -1,07R | 0,26R | +1,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 4 | 31 | 2 | 29 | -1,06R | 0,06R | -1,11R | 0,16R | +1,21R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive | 12 | 30 | 9 | 21 | 0,28R | 0,37R | -0,09R | 0,50R | +0,22R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 14 | 26 | 9 | 17 | 0,30R | 0,00R | +0,30R | 0,50R | +0,20R | SELEZIONE POSITIVA |
| SHADOW_COMBO_TREND | Combo Trend | 8 | 25 | 6 | 19 | 0,54R | -0,03R | +0,57R | 0,42R | -0,12R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 12 | 21 | 9 | 12 | 0,74R | -0,25R | +0,99R | 0,54R | -0,20R | FILTRO PAPER UTILE |
| MAIN | Principale 4H | 15 | 20 | 11 | 9 | 0,06R | -0,36R | +0,42R | -0,06R | -0,12R | FILTRO PAPER UTILE |
| SHADOW_COMBO_SCANNER | Combo Scanner | 10 | 19 | 7 | 12 | -0,12R | 0,29R | -0,41R | 0,11R | +0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_4H_WIDE | Ampia 4H | 9 | 18 | 8 | 10 | 0,40R | -0,26R | +0,67R | 0,36R | -0,05R | FILTRO PAPER UTILE |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 9 | 15 | 9 | 6 | 0,03R | -0,24R | +0,27R | 0,01R | -0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 8 | 12 | 7 | 5 | -0,05R | -0,37R | +0,32R | 0,37R | +0,42R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 5 | 11 | 4 | 7 | -0,31R | 0,20R | -0,51R | 0,12R | +0,43R | CAMPIONE INSUFFICIENTE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 8 | 9 | 4 | 5 | 1,39R | -0,39R | +1,78R | 0,03R | -1,35R | CAMPIONE INSUFFICIENTE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 11 | 8 | 5 | 3 | 0,17R | 0,96R | -0,79R | -0,02R | -0,19R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 2 | 5 | 2 | 3 | 1,49R | 0,69R | +0,81R | 1,50R | +0,01R | CAMPIONE INSUFFICIENTE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 3 | 4 | 3 | 1 | -1,04R | 1,99R | -3,02R | -1,03R | +0,00R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 3 | 4 | 3 | 1 | -0,07R | -1,40R | +1,33R | -0,21R | -0,13R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered | 7 | 4 | 3 | 1 | 0,65R | -1,01R | +1,67R | -0,15R | -0,80R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 2 | 2 | 2 | 0 | 0,11R | 0,00R | +0,11R | 0,63R | +0,52R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive MFE Trail | 4 | 2 | 2 | 0 | -1,01R | 0,00R | -1,01R | -0,35R | +0,66R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,18R | -0,57R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,09R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 1 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -1,09R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 1 | 1 | 1 | 0 | 1,37R | 0,00R | +1,37R | 1,37R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 1 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -1,10R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 1 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -1,09R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 1 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -1,10R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 1 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -1,10R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 3 | 1 | 1 | 0 | -1,10R | 0,00R | -1,10R | -0,47R | +0,63R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,02R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_4H | Btc Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_4H | Btc Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_4H | Btc Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_4H | Btc Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_BOLLINGER_1H | Doge Bollinger 1H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 1 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,52R | +0,52R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 2 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,14R | -0,14R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_BOLLINGER_1H | Eth Bollinger 1H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_4H | Eth Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_4H | Sol Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_4H | Sol Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 1 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,09R | -0,09R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_4H | Sol Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_4H | Sol Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 10 | 15 | 9 | 6 | -0,57% | -0,93% | +0,36% | -0,15% | +0,42% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 10 | 15 | 9 | 6 | -1,13% | -1,85% | +0,72% | -0,30% | +0,83% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 2 | 5 | 2 | 3 | -3,20% | -2,31% | -0,89% | -3,20% | 0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 4 | 4 | 4 | 0 | -3,90% | 0,00% | -3,90% | -3,90% | -0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 4 | 4 | 4 | 0 | -7,80% | 0,00% | -7,80% | -7,80% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 2 | 2 | 2 | 0 | -0,11% | 0,00% | -0,11% | -0,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 2 | 2 | 2 | 0 | -0,22% | 0,00% | -0,22% | -0,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 2 | 2 | 2 | 0 | -3,20% | 0,00% | -3,20% | -3,20% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -7,80% | -6,38% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -3,90% | -3,19% | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 10 | 0,00% | 0,00 | -1,10R | -1,03R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 10 | 0,00% | 0,00 | -1,10R | -1,03R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 9 | 0,00% | 0,00 | -1,08R | -1,02R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 9 | 0,00% | 0,00 | -1,08R | -1,02R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 10 | 10,00% | 0,20 | -0,79R | -0,89R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 12 | 8,33% | 0,17 | -0,79R | -0,73R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 11 | 18,18% | 0,39 | -0,54R | -0,65R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 8 | 12,50% | 0,31 | -0,62R | -0,62R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 12 | 16,67% | 0,43 | -0,49R | -0,49R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 8 | 25,00% | 0,65 | -0,28R | -0,46R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 17 | 17,65% | 0,40 | -0,51R | -0,45R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 8 | 25,00% | 0,69 | -0,25R | -0,43R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 12 | 25,00% | 0,62 | -0,31R | -0,41R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 19 | 26,32% | 0,49 | -0,40R | -0,33R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | <5 | 9 | 22,22% | 0,60 | -0,32R | -0,33R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 17 | 29,41% | 0,57 | -0,33R | -0,27R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | ALT_ROTATION_UP | 8 | 25,00% | 0,68 | -0,26R | -0,26R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 16 | 25,00% | 0,69 | -0,24R | -0,25R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 9 | 22,22% | 0,77 | -0,18R | -0,21R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | TREND_UP | 15 | 26,67% | 0,67 | -0,26R | -0,20R | MEDIA |
| SHADOW_EMA_TREND_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 15 | 26,67% | 0,73 | -0,21R | -0,19R | MEDIA |
| MAIN | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 8 | 25,00% | 0,64 | -0,28R | -0,16R | MEDIA |
| MAIN | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 8 | 25,00% | 0,64 | -0,28R | -0,16R | MEDIA |
| Rapida 1H V1 | PREFERIRE IN CHALLENGER | Asset | AKE | 13 | 84,62% | 8,07 | 1,10R | +1,17R | MEDIA |
| Forza relativa 1H V1 | PREFERIRE IN CHALLENGER | Asset | AKE | 9 | 66,67% | 4,32 | 1,12R | +1,11R | MEDIA |
| Bilanciata 1H V1 | PREFERIRE IN CHALLENGER | Asset | AKE | 8 | 62,50% | 3,27 | 0,86R | +0,92R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | PREFERIRE IN CHALLENGER | Asset | AKE | 8 | 62,50% | 3,27 | 0,86R | +0,76R | MEDIA |
| Forza relativa 1H V1 | PREFERIRE IN CHALLENGER | Regime entrata | TRANSITION | 11 | 54,55% | 2,55 | 0,72R | +0,71R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
