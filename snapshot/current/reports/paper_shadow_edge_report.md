# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-20T14:35:21+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **449**
- Trade Shadow/Research chiusi: **950**
- Eventi Shadow già presi dai Paper: **299**
- Eventi Shadow saltati dai Paper: **651**
- Profili con filtro Paper utile: **3**
- Profili in cui il Paper potrebbe scartare edge: **4**
- Profili con campione ancora insufficiente: **43**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 | 42 | 113 | 24 | 89 | -0,30R | 0,02R | -0,31R | 0,02R | +0,32R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 19 | 102 | 6 | 96 | -0,20R | 0,03R | -0,23R | 0,14R | +0,34R | CAMPIONE INSUFFICIENTE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 15 | 62 | 3 | 59 | -1,03R | 0,21R | -1,24R | 0,14R | +1,18R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive | 15 | 51 | 11 | 40 | 0,04R | 0,45R | -0,41R | 0,33R | +0,29R | PAPER SCARTA EDGE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 8 | 46 | 3 | 43 | -1,04R | 0,15R | -1,19R | -0,04R | +1,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 21 | 46 | 12 | 34 | 0,04R | 0,55R | -0,50R | 0,31R | +0,27R | PAPER SCARTA EDGE |
| SHADOW_COMBO_TREND | Combo Trend | 14 | 40 | 8 | 32 | 0,14R | 0,16R | -0,02R | 0,09R | -0,05R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 16 | 36 | 11 | 25 | 0,51R | 0,50R | +0,01R | 0,49R | -0,02R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 15 | 33 | 8 | 25 | -0,24R | 0,76R | -1,00R | 0,11R | +0,35R | PAPER SCARTA EDGE |
| MAIN | Principale 4H | 15 | 28 | 12 | 16 | -0,03R | -0,09R | +0,06R | -0,06R | -0,03R | NESSUN EDGE CHIARO |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered | 33 | 28 | 20 | 8 | 0,21R | 0,19R | +0,02R | -0,10R | -0,31R | NESSUN EDGE CHIARO |
| SHADOW_4H_WIDE | Ampia 4H | 11 | 26 | 9 | 17 | 0,25R | 0,10R | +0,15R | 0,26R | +0,01R | NESSUN EDGE CHIARO |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 20 | 23 | 14 | 9 | 0,46R | 0,30R | +0,16R | 0,29R | -0,17R | NESSUN EDGE CHIARO |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 14 | 22 | 14 | 8 | -0,01R | -0,44R | +0,44R | 0,23R | +0,24R | SELEZIONE POSITIVA |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive MFE Trail | 19 | 22 | 8 | 14 | -0,66R | 0,89R | -1,55R | -0,26R | +0,40R | PAPER SCARTA EDGE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 12 | 21 | 9 | 12 | 0,12R | -0,20R | +0,31R | 0,39R | +0,27R | FILTRO PAPER UTILE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 16 | 20 | 12 | 8 | 0,84R | 0,17R | +0,67R | 0,36R | -0,48R | SELEZIONE POSITIVA |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 9 | 19 | 6 | 13 | -0,38R | -0,16R | -0,21R | -0,17R | +0,20R | CAMPIONE INSUFFICIENTE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 16 | 16 | 10 | 6 | 0,15R | 0,45R | -0,30R | -0,08R | -0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 7 | 8 | 6 | 2 | 0,23R | 1,54R | -1,31R | 0,56R | +0,34R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 4 | 5 | 4 | 1 | -0,34R | -1,40R | +1,06R | -0,45R | -0,10R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V2 | Rapida 1H V2 | 3 | 3 | 3 | 0 | -0,31R | 0,00R | -0,31R | 0,03R | +0,34R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_1H | Btc Donchian 1H | 2 | 2 | 2 | 0 | -1,12R | 0,00R | -1,12R | -1,11R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_1H | Btc Ema 1H | 2 | 2 | 2 | 0 | -1,11R | 0,00R | -1,11R | -1,09R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_DONCHIAN_1H | Eth Donchian 1H | 2 | 2 | 2 | 0 | -1,13R | 0,00R | -1,13R | -1,11R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_1H | Sol Adaptive 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,18R | -0,57R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_1H | Sol Ema 1H | 2 | 2 | 2 | 0 | 0,39R | 0,00R | +0,39R | -0,09R | -0,48R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_1H | Btc Adaptive 1H | 1 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -1,09R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_1H | Btc Bollinger 1H | 1 | 1 | 1 | 0 | 1,37R | 0,00R | +1,37R | 1,37R | +0,01R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 2 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,52R | +0,59R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_BOLLINGER_1H | Eth Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | 0,31R | +1,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 3 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,67R | +0,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 5 | 1 | 1 | 0 | -1,10R | 0,00R | -1,10R | -0,48R | +0,62R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 1 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -0,09R | +1,04R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_4H | Btc Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_4H | Btc Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_4H | Btc Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_4H | Btc Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_BOLLINGER_1H | Doge Bollinger 1H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 2 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,31R | -0,31R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 4 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,26R | -0,26R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_4H | Eth Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_4H | Sol Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_4H | Sol Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_4H | Sol Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_4H | Sol Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 14 | 40 | 13 | 27 | 0,34% | -0,14% | +0,48% | 0,57% | +0,23% | FILTRO PAPER UTILE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 14 | 40 | 13 | 27 | 0,67% | -0,29% | +0,96% | 1,14% | +0,47% | FILTRO PAPER UTILE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 10 | 26 | 8 | 18 | -0,88% | -0,47% | -0,41% | 0,16% | +1,04% | SELEZIONE DA RIVEDERE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 10 | 15 | 9 | 6 | -3,07% | 1,42% | -4,48% | -2,40% | +0,67% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 10 | 15 | 9 | 6 | -6,14% | 2,83% | -8,97% | -4,80% | +1,33% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 6 | 13 | 6 | 7 | -0,30% | -0,35% | +0,05% | -0,30% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 4 | 5 | 4 | 1 | -0,13% | 3,60% | -3,73% | -0,13% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 4 | 5 | 4 | 1 | -0,26% | 7,19% | -7,46% | -0,26% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 2 | 3 | 2 | 1 | 1,99% | 4,30% | -2,31% | 1,99% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 19 | 0,00% | 0,00 | -7,80% | -7,83% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 11 | 0,00% | 0,00 | -7,80% | -5,26% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 19 | 0,00% | 0,00 | -3,90% | -3,91% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 8 | 12,50% | 0,13 | -5,93% | -3,38% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 11 | 0,00% | 0,00 | -3,90% | -2,63% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 15 | 0,00% | 0,00 | -3,20% | -2,61% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 10 | 40,00% | 0,52 | -2,26% | -2,29% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 8 | 12,50% | 0,13 | -2,96% | -1,69% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 10 | 40,00% | 0,52 | -1,13% | -1,14% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 9 | 0,00% | 0,00 | -1,08R | -1,10R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 10 | 0,00% | 0,00 | -1,10R | -1,05R | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 10 | 20,00% | 0,48 | -0,45R | -0,96R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 11 | 18,18% | 0,48 | -0,41R | -0,91R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 15 | 6,67% | 0,13 | -0,88R | -0,90R | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 9 | 22,22% | 0,55 | -0,38R | -0,90R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 21 | 9,52% | 0,14 | -0,86R | -0,81R | ALTA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 14 | 21,43% | 0,52 | -0,37R | -0,78R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ADA | 8 | 12,50% | 0,25 | -0,72R | -0,74R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | PEPE | 8 | 12,50% | 0,18 | -0,79R | -0,74R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 12 | 25,00% | 0,73 | -0,20R | -0,70R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 16 | 25,00% | 0,64 | -0,27R | -0,69R | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 12 | 16,67% | 0,42 | -1,27% | -0,68% | MEDIA |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ESPORTS | 9 | 22,22% | 0,56 | -0,35R | -0,68R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 15 | 13,33% | 0,29 | -0,64R | -0,66R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | <5 | 12 | 16,67% | 0,42 | -0,50R | -0,65R | MEDIA |
| Rapida 1H V3 Filtered | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 8 | 25,00% | 0,47 | -0,42R | -0,62R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 11 | 18,18% | 0,47 | -0,44R | -0,59R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 18 | 22,22% | 0,61 | -0,31R | -0,47R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 17 | 23,53% | 0,64 | -0,29R | -0,44R | MEDIA |
| SHADOW_BOLLINGER_MR_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 10 | 20,00% | 0,35 | -0,56R | -0,40R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
