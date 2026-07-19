# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-19T08:23:11+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **281**
- Trade Shadow/Research chiusi: **602**
- Eventi Shadow già presi dai Paper: **199**
- Eventi Shadow saltati dai Paper: **403**
- Profili con filtro Paper utile: **1**
- Profili in cui il Paper potrebbe scartare edge: **1**
- Profili con campione ancora insufficiente: **52**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 | 33 | 85 | 19 | 66 | -0,09R | -0,00R | -0,09R | 0,15R | +0,25R | NESSUN EDGE CHIARO |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 10 | 77 | 1 | 76 | -1,01R | 0,04R | -1,06R | 0,15R | +1,16R | CAMPIONE INSUFFICIENTE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 7 | 48 | 2 | 46 | -1,02R | 0,14R | -1,16R | 0,26R | +1,27R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive | 14 | 34 | 10 | 24 | 0,15R | 0,57R | -0,42R | 0,36R | +0,20R | PAPER SCARTA EDGE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 4 | 32 | 2 | 30 | -1,06R | 0,13R | -1,18R | 0,16R | +1,21R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 14 | 30 | 9 | 21 | 0,30R | 0,38R | -0,08R | 0,50R | +0,20R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_TREND | Combo Trend | 8 | 26 | 6 | 20 | 0,54R | 0,08R | +0,46R | 0,42R | -0,12R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 12 | 24 | 9 | 15 | 0,74R | 0,24R | +0,51R | 0,54R | -0,20R | SELEZIONE POSITIVA |
| SHADOW_COMBO_SCANNER | Combo Scanner | 10 | 22 | 7 | 15 | -0,12R | 0,67R | -0,79R | 0,11R | +0,24R | CAMPIONE INSUFFICIENTE |
| MAIN | Principale 4H | 15 | 21 | 11 | 10 | 0,06R | -0,13R | +0,19R | -0,06R | -0,12R | FILTRO PAPER UTILE |
| SHADOW_4H_WIDE | Ampia 4H | 9 | 19 | 8 | 11 | 0,40R | 0,01R | +0,39R | 0,36R | -0,05R | SELEZIONE POSITIVA |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 10 | 16 | 10 | 6 | 0,18R | -0,24R | +0,42R | 0,16R | -0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 8 | 13 | 7 | 6 | -0,05R | -0,49R | +0,44R | 0,37R | +0,42R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 5 | 12 | 4 | 8 | -0,31R | 0,04R | -0,35R | 0,12R | +0,43R | CAMPIONE INSUFFICIENTE |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 9 | 11 | 5 | 6 | 1,55R | 0,04R | +1,51R | 0,27R | -1,28R | CAMPIONE INSUFFICIENTE |
| Bilanciata 1H V2 | Bilanciata 1H V2 | 12 | 9 | 6 | 3 | 0,47R | 0,96R | -0,49R | 0,15R | -0,33R | CAMPIONE INSUFFICIENTE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 7 | 8 | 7 | 1 | 0,25R | 1,99R | -1,74R | 0,25R | +0,00R | CAMPIONE INSUFFICIENTE |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered | 12 | 8 | 6 | 2 | 0,65R | -1,08R | +1,73R | -0,17R | -0,82R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_MEAN_REVERSION | Combo Mean Reversion | 4 | 6 | 3 | 3 | 0,66R | 0,69R | -0,03R | 0,89R | +0,24R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive MFE Trail | 7 | 5 | 3 | 2 | -1,01R | 1,99R | -3,00R | -0,31R | +0,70R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_SHORT_15M | Scalp RSI Short 75 · prudente · 5x | 3 | 4 | 3 | 1 | -0,07R | -1,40R | +1,33R | -0,21R | -0,13R | CAMPIONE INSUFFICIENTE |
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
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 12 | 20 | 11 | 9 | -1,17% | -0,96% | -0,21% | -0,77% | +0,40% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 12 | 20 | 11 | 9 | -2,35% | -1,93% | -0,42% | -1,55% | +0,80% | SELEZIONE DA RIVEDERE |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 4 | 10 | 4 | 6 | -2,31% | -2,27% | -0,05% | -2,31% | 0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 6 | 8 | 6 | 2 | -3,90% | 2,45% | -6,35% | -3,90% | -0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 6 | 8 | 6 | 2 | -7,80% | 4,90% | -12,70% | -7,80% | -0,00% | CAMPIONE INSUFFICIENTE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 4 | 7 | 4 | 3 | -2,60% | -2,74% | +0,14% | -2,60% | -0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 10× | RSI 25 · leva 10× | 2 | 2 | 2 | 0 | -0,11% | 0,00% | -0,11% | -0,11% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 20× | RSI 25 · leva 20× | 2 | 2 | 2 | 0 | -0,22% | 0,00% | -0,22% | -0,22% | +0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 10× | RSI 20 · leva 10× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 20× | RSI 20 · leva 20× | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 20 · leva 5× · Wide | RSI 20 · leva 5× · Wide | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |
| RSI 25 · leva 5× · Wide | RSI 25 · leva 5× · Wide | 0 | 0 | 0 | 0 | 0,00% | 0,00% | 0,00% | 0,00% | 0,00% | CAMPIONE INSUFFICIENTE |

## Filtri candidati ricavati dallo Shadow

Vengono mostrati soltanto contesti con almeno **8 eventi** e una differenza materiale rispetto alla media della strategia. Non sono modifiche automatiche.

| Strategia | Azione candidata | Dimensione | Valore | Eventi | WR | PF | Expectancy | Δ vs base | Confidenza |
| --- | --- | --- | --- | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 11 | 0,00% | 0,00 | -7,80% | -5,65% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 11 | 0,00% | 0,00 | -3,90% | -2,82% | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 10 | 10,00% | 0,20 | -0,79R | -1,14R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 9 | 0,00% | 0,00 | -1,08R | -1,11R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 9 | 0,00% | 0,00 | -1,08R | -1,11R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 10 | 0,00% | 0,00 | -1,10R | -1,08R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 10 | 0,00% | 0,00 | -1,10R | -1,08R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 11 | 18,18% | 0,39 | -0,54R | -0,90R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 8 | 25,00% | 0,65 | -0,28R | -0,71R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 13 | 15,38% | 0,34 | -0,58R | -0,61R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | <5 | 9 | 22,22% | 0,60 | -0,32R | -0,42R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 9 | 22,22% | 0,61 | -0,31R | -0,40R | MEDIA |
| SHADOW_4H_WIDE | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 9 | 22,22% | 0,77 | -0,18R | -0,36R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | ALT_ROTATION_UP | 8 | 25,00% | 0,68 | -0,26R | -0,35R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 16 | 25,00% | 0,69 | -0,24R | -0,34R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 20 | 30,00% | 0,59 | -0,30R | -0,28R | ALTA |
| MAIN | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | ≥7 | 8 | 25,00% | 0,64 | -0,28R | -0,26R | MEDIA |
| MAIN | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | ALTA | 8 | 25,00% | 0,64 | -0,28R | -0,26R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Lato | SHORT | 39 | 35,90% | 0,74 | -0,18R | -0,16R | ALTA |
| Rapida 1H V1 | PREFERIRE IN CHALLENGER | Asset | AKE | 13 | 84,62% | 8,07 | 1,10R | +1,12R | MEDIA |
| Forza relativa 1H V1 | PREFERIRE IN CHALLENGER | Asset | AKE | 9 | 66,67% | 4,32 | 1,12R | +1,02R | MEDIA |
| Bilanciata 1H V1 | PREFERIRE IN CHALLENGER | Asset | AKE | 9 | 66,67% | 3,92 | 0,99R | +0,96R | MEDIA |
| SHADOW_EMA_TREND_1H | PREFERIRE IN CHALLENGER | Asset | AKE | 8 | 62,50% | 3,60 | 0,99R | +0,93R | MEDIA |
| SHADOW_COMBO_TREND | PREFERIRE IN CHALLENGER | Asset | AKE | 8 | 62,50% | 3,60 | 0,99R | +0,80R | MEDIA |
| SHADOW_4H_WIDE | PREFERIRE IN CHALLENGER | Fascia score | 6–7 | 8 | 50,00% | 2,74 | 0,88R | +0,71R | MEDIA |
| SHADOW_4H_WIDE | PREFERIRE IN CHALLENGER | Confidenza segnale | BUONA | 8 | 50,00% | 2,74 | 0,88R | +0,71R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | PREFERIRE IN CHALLENGER | Asset | AKE | 9 | 66,67% | 3,92 | 0,99R | +0,63R | MEDIA |
| Forza relativa 1H V1 | PREFERIRE IN CHALLENGER | Regime entrata | TRANSITION | 11 | 54,55% | 2,55 | 0,72R | +0,62R | MEDIA |
| Bilanciata 1H V1 | PREFERIRE IN CHALLENGER | Regime entrata | ALT_ROTATION_UP | 9 | 55,56% | 2,27 | 0,60R | +0,57R | MEDIA |
| SHADOW_COMBO_SCANNER | PREFERIRE IN CHALLENGER | Asset | AKE | 8 | 62,50% | 3,60 | 0,99R | +0,57R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
