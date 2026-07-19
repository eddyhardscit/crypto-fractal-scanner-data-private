# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-19T18:28:21+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **326**
- Trade Shadow/Research chiusi: **725**
- Eventi Shadow già presi dai Paper: **223**
- Eventi Shadow saltati dai Paper: **502**
- Profili con filtro Paper utile: **1**
- Profili in cui il Paper potrebbe scartare edge: **3**
- Profili con campione ancora insufficiente: **50**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 | 37 | 94 | 19 | 75 | -0,09R | 0,02R | -0,11R | 0,07R | +0,17R | NESSUN EDGE CHIARO |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 13 | 88 | 4 | 84 | 0,22R | 0,05R | +0,17R | 0,26R | +0,04R | CAMPIONE INSUFFICIENTE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 9 | 55 | 2 | 53 | -1,02R | 0,17R | -1,19R | 0,19R | +1,21R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive | 14 | 42 | 10 | 32 | 0,15R | 0,55R | -0,39R | 0,36R | +0,20R | PAPER SCARTA EDGE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 15 | 40 | 10 | 30 | 0,26R | 0,36R | -0,09R | 0,47R | +0,20R | NESSUN EDGE CHIARO |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 4 | 38 | 2 | 36 | -1,06R | 0,20R | -1,26R | 0,16R | +1,21R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_TREND | Combo Trend | 8 | 32 | 6 | 26 | 0,54R | 0,20R | +0,34R | 0,42R | -0,12R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 12 | 30 | 9 | 21 | 0,74R | 0,34R | +0,41R | 0,54R | -0,20R | SELEZIONE POSITIVA |
| SHADOW_COMBO_SCANNER | Combo Scanner | 10 | 28 | 7 | 21 | -0,12R | 0,64R | -0,77R | 0,11R | +0,24R | CAMPIONE INSUFFICIENTE |
| MAIN | Principale 4H | 15 | 23 | 11 | 12 | 0,06R | -0,02R | +0,09R | -0,06R | -0,12R | NESSUN EDGE CHIARO |
| SHADOW_4H_WIDE | Ampia 4H | 10 | 21 | 8 | 13 | 0,40R | 0,15R | +0,26R | 0,32R | -0,09R | SELEZIONE POSITIVA |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 10 | 18 | 10 | 8 | 0,18R | -0,44R | +0,61R | 0,16R | -0,02R | FILTRO PAPER UTILE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 14 | 17 | 11 | 6 | 0,33R | 0,46R | -0,13R | 0,05R | -0,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 11 | 17 | 8 | 9 | -0,18R | -0,28R | +0,10R | 0,43R | +0,61R | NESSUN EDGE CHIARO |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 12 | 15 | 8 | 7 | 0,99R | 0,35R | +0,64R | 0,30R | -0,69R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered | 20 | 14 | 8 | 6 | 0,55R | 0,19R | +0,36R | -0,07R | -0,62R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 6 | 13 | 5 | 8 | -0,25R | 0,04R | -0,29R | 0,10R | +0,35R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive MFE Trail | 12 | 12 | 5 | 7 | -1,01R | 1,54R | -2,56R | -0,41R | +0,60R | CAMPIONE INSUFFICIENTE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 13 | 10 | 7 | 3 | 0,24R | 0,96R | -0,72R | 0,05R | -0,19R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 4 | 6 | 3 | 3 | 0,66R | 0,69R | -0,03R | 0,89R | +0,24R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 4 | 5 | 4 | 1 | -0,34R | -1,40R | +1,06R | -0,45R | -0,10R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 2 | 2 | 2 | 0 | 0,11R | 0,00R | +0,11R | 0,63R | +0,52R | CAMPIONE INSUFFICIENTE |
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
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 1 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -0,09R | +1,04R | CAMPIONE INSUFFICIENTE |
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
| SHADOW_SOL_DONCHIAN_4H | Sol Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_4H | Sol Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 12 | 24 | 11 | 13 | -1,17% | 0,44% | -1,61% | -0,77% | +0,40% | PAPER SCARTA EDGE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 12 | 24 | 11 | 13 | -2,35% | 0,88% | -3,23% | -1,55% | +0,80% | PAPER SCARTA EDGE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 6 | 14 | 6 | 8 | -0,11% | -0,62% | +0,52% | -0,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 6 | 8 | 6 | 2 | -3,90% | 2,45% | -6,35% | -3,90% | -0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 6 | 8 | 6 | 2 | -7,80% | 4,90% | -12,70% | -7,80% | -0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 4 | 7 | 4 | 3 | -2,60% | -2,74% | +0,14% | -2,60% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 3 | 3 | 3 | 0 | -1,37% | 0,00% | -1,37% | -1,37% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 3 | 3 | 3 | 0 | -2,75% | 0,00% | -2,75% | -2,75% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 1 | 1 | 1 | 0 | -0,32% | 0,00% | -0,32% | -0,32% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 11 | 0,00% | 0,00 | -7,80% | -7,21% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 11 | 0,00% | 0,00 | -3,90% | -3,60% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 9 | 0,00% | 0,00 | -1,08R | -1,14R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 9 | 0,00% | 0,00 | -1,08R | -1,14R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 10 | 0,00% | 0,00 | -1,10R | -1,09R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 10 | 0,00% | 0,00 | -1,10R | -1,09R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 12 | 16,67% | 0,39 | -0,50R | -0,84R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 8 | 25,00% | 0,65 | -0,28R | -0,74R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 14 | 14,29% | 0,32 | -0,61R | -0,67R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 13 | 23,08% | 0,58 | -0,32R | -0,65R | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 11 | 36,36% | 0,68 | -1,21% | -0,62% | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | <5 | 10 | 20,00% | 0,53 | -0,39R | -0,52R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 10 | 20,00% | 0,53 | -0,39R | -0,51R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 9 | 22,22% | 0,77 | -0,18R | -0,43R | MEDIA |
| MAIN | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 9 | 22,22% | 0,55 | -0,37R | -0,38R | MEDIA |
| MAIN | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 9 | 22,22% | 0,55 | -0,37R | -0,38R | MEDIA |
| SHADOW_DONCHIAN_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 8 | 12,50% | 0,34 | -0,61R | -0,38R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 16 | 25,00% | 0,69 | -0,24R | -0,37R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 16 | 25,00% | 0,71 | -0,22R | -0,35R | MEDIA |
| SHADOW_BOLLINGER_MR_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 8 | 25,00% | 0,46 | -0,43R | -0,33R | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 11 | 36,36% | 0,68 | -0,61% | -0,31% | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 20 | 30,00% | 0,59 | -0,30R | -0,30R | ALTA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 5–6 | 30 | 30,00% | 0,76 | -0,18R | -0,24R | ALTA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | MEDIA | 30 | 30,00% | 0,76 | -0,18R | -0,24R | ALTA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 21 | 28,57% | 0,76 | -0,18R | -0,24R | ALTA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 5–6 | 27 | 33,33% | 0,68 | -0,22R | -0,22R | ALTA |
| SHADOW_DONCHIAN_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | LONG | 11 | 18,18% | 0,52 | -0,42R | -0,18R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 40 | 35,00% | 0,74 | -0,18R | -0,17R | ALTA |
| SHORT RSI 70 · leva 20× | PREFERIRE IN CHALLENGER | Motivo uscita | TARGET | 10 | 100,00% | ∞ | 7,21% | +7,80% | MEDIA |
| SHORT RSI 70 · leva 10× | PREFERIRE IN CHALLENGER | Motivo uscita | TARGET | 10 | 100,00% | ∞ | 3,60% | +3,90% | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
