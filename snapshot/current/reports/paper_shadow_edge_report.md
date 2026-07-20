# Paper vs Shadow — selezione, trade saltati e filtri candidati

Generato: 2026-07-20T17:37:15+00:00

> Report esclusivamente osservativo. Non modifica strategie, rischio, capitale o ordini. Qualsiasi filtro candidato deve essere provato in un nuovo conto challenger e validato su dati futuri.

## Lettura rapida

- Trade Paper chiusi nei conti confrontati: **480**
- Trade Shadow/Research chiusi: **1020**
- Eventi Shadow già presi dai Paper: **318**
- Eventi Shadow saltati dai Paper: **702**
- Profili con filtro Paper utile: **2**
- Profili in cui il Paper potrebbe scartare edge: **5**
- Profili con campione ancora insufficiente: **40**

**Δ selezione** = expectancy dei segnali presi meno expectancy dei segnali saltati. Positivo significa che la selezione Paper sta privilegiando segnali migliori.
**Δ gestione** = risultato effettivo Paper meno risultato Research degli stessi eventi. Positivo suggerisce che trailing, size, costi o gestione dell’uscita stanno migliorando l’esecuzione.

## Conti Paper principali vs Research All Signals

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| Rapida 1H V1 | Rapida 1H V1 | 43 | 117 | 25 | 92 | -0,29R | 0,02R | -0,31R | 0,02R | +0,31R | SELEZIONE DA RIVEDERE |
| Bilanciata 1H V1 | Bilanciata 1H V1 | 20 | 106 | 6 | 100 | -0,20R | -0,01R | -0,19R | 0,08R | +0,28R | CAMPIONE INSUFFICIENTE |
| Forza relativa 1H V1 | Forza relativa 1H V1 | 16 | 65 | 3 | 62 | -1,03R | 0,20R | -1,23R | 0,13R | +1,16R | CAMPIONE INSUFFICIENTE |
| SHADOW_COMBO_ADAPTIVE | Combo Adaptive | 16 | 53 | 11 | 42 | 0,04R | 0,45R | -0,41R | 0,30R | +0,26R | PAPER SCARTA EDGE |
| SHADOW_EMA_TREND_1H | Benchmark trend following EMA 1H | 8 | 48 | 3 | 45 | -1,04R | 0,16R | -1,21R | -0,04R | +1,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SCANNER_TOP5_LONG | Scanner Top 5 Long 1H | 22 | 46 | 12 | 34 | 0,04R | 0,55R | -0,50R | 0,29R | +0,25R | PAPER SCARTA EDGE |
| SHADOW_COMBO_TREND | Combo Trend | 15 | 43 | 8 | 35 | 0,14R | 0,15R | -0,01R | 0,08R | -0,06R | NESSUN EDGE CHIARO |
| SHADOW_SCANNER_TOP5_BTC | Scanner Top 5 + forza BTC 1H | 17 | 37 | 11 | 26 | 0,51R | 0,56R | -0,06R | 0,45R | -0,05R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_SCANNER | Combo Scanner | 17 | 34 | 8 | 26 | -0,24R | 0,81R | -1,05R | 0,02R | +0,27R | PAPER SCARTA EDGE |
| Rapida 1H V3 Filtered | Rapida 1H V3 Filtered | 34 | 31 | 22 | 9 | 0,09R | 0,32R | -0,23R | -0,06R | -0,14R | PAPER SCARTA EDGE |
| MAIN | Principale 4H | 16 | 30 | 12 | 18 | -0,03R | -0,02R | -0,00R | -0,12R | -0,09R | NESSUN EDGE CHIARO |
| SHADOW_4H_WIDE | Ampia 4H | 11 | 28 | 9 | 19 | 0,25R | -0,02R | +0,27R | 0,26R | +0,01R | FILTRO PAPER UTILE |
| Bilanciata 1H V3 Filtered | Bilanciata 1H V3 Filtered | 22 | 25 | 15 | 10 | 0,35R | 0,16R | +0,19R | 0,17R | -0,19R | NESSUN EDGE CHIARO |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | Combo Adaptive MFE Trail | 21 | 24 | 9 | 15 | -0,71R | 0,96R | -1,67R | -0,29R | +0,42R | PAPER SCARTA EDGE |
| SHADOW_DONCHIAN_1H | Benchmark Donchian breakout 1H | 13 | 23 | 9 | 14 | 0,12R | -0,33R | +0,44R | 0,27R | +0,16R | FILTRO PAPER UTILE |
| SHADOW_BOLLINGER_MR_1H | Benchmark Bollinger mean reversion 1H | 14 | 22 | 14 | 8 | -0,01R | -0,44R | +0,44R | 0,23R | +0,24R | SELEZIONE POSITIVA |
| Forza relativa 1H V2 | Forza relativa 1H V2 | 17 | 21 | 13 | 8 | 0,70R | 0,17R | +0,52R | 0,27R | -0,42R | SELEZIONE POSITIVA |
| SHADOW_SCANNER_BOTTOM5_SHORT | Scanner Bottom 5 Short 1H | 11 | 21 | 8 | 13 | -0,55R | -0,17R | -0,38R | -0,24R | +0,31R | SELEZIONE DA RIVEDERE |
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
| SHADOW_DOGE_DONCHIAN_1H | Doge Donchian 1H | 2 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -0,31R | +0,82R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_ADAPTIVE_1H | Eth Adaptive 1H | 2 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,52R | +0,59R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_BOLLINGER_1H | Eth Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | 0,31R | +1,44R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_1H | Eth Ema 1H | 4 | 1 | 1 | 0 | -1,11R | 0,00R | -1,11R | -0,78R | +0,33R | CAMPIONE INSUFFICIENTE |
| SHADOW_GLOBAL_PURE | Global Confluence puro 1H | 6 | 1 | 1 | 0 | -1,10R | 0,00R | -1,10R | -0,58R | +0,52R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_1H | Sol Bollinger 1H | 1 | 1 | 1 | 0 | -1,13R | 0,00R | -1,13R | -1,12R | +0,02R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_1H | Sol Donchian 1H | 1 | 1 | 1 | 0 | -1,12R | 0,00R | -1,12R | -0,09R | +1,04R | CAMPIONE INSUFFICIENTE |
| RSI_EXTREME_LONG_15M | Scalp RSI Long 25 · prudente · 5x | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_ADAPTIVE_4H | Btc Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_BOLLINGER_4H | Btc Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_DONCHIAN_4H | Btc Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_BTC_EMA_4H | Btc Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_BOLLINGER_1H | Doge Bollinger 1H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_DOGE_EMA_1H | Doge Ema 1H | 4 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | -0,26R | -0,26R | CAMPIONE INSUFFICIENTE |
| SHADOW_ETH_EMA_4H | Eth Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_ADAPTIVE_4H | Sol Adaptive 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_BOLLINGER_4H | Sol Bollinger 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_DONCHIAN_4H | Sol Donchian 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |
| SHADOW_SOL_EMA_4H | Sol Ema 4H | 0 | 0 | 0 | 0 | 0,00R | 0,00R | 0,00R | 0,00R | 0,00R | CAMPIONE INSUFFICIENTE |

## Conti RSI 5m vs Shadow

| Strategia / conto | Paper rif. | Paper chiuse | Shadow chiuse | Presi | Saltati | Exp. presi | Exp. saltati | Δ selezione | Exp. Paper | Δ gestione | Stato |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| SHORT RSI 70 · leva 10× | SHORT RSI 70 · leva 10× | 17 | 47 | 16 | 31 | -0,46% | -0,63% | +0,17% | -0,22% | +0,24% | NESSUN EDGE CHIARO |
| SHORT RSI 70 · leva 20× | SHORT RSI 70 · leva 20× | 17 | 47 | 16 | 31 | -0,92% | -1,26% | +0,34% | -0,44% | +0,48% | SELEZIONE POSITIVA |
| SHORT RSI 70 · leva 5× · Wide | SHORT RSI 70 · leva 5× · Wide | 12 | 33 | 10 | 23 | -1,35% | -1,06% | -0,28% | -0,40% | +0,94% | SELEZIONE DA RIVEDERE |
| SHORT RSI 75 · leva 10× | SHORT RSI 75 · leva 10× | 11 | 20 | 10 | 10 | -3,15% | 0,04% | -3,19% | -2,54% | +0,61% | SELEZIONE DA RIVEDERE |
| SHORT RSI 75 · leva 20× | SHORT RSI 75 · leva 20× | 11 | 20 | 10 | 10 | -6,30% | 0,08% | -6,38% | -5,07% | +1,23% | SELEZIONE DA RIVEDERE |
| SHORT RSI 75 · leva 5× · Wide | SHORT RSI 75 · leva 5× · Wide | 6 | 15 | 6 | 9 | -0,30% | -0,98% | +0,69% | -0,30% | -0,00% | CAMPIONE INSUFFICIENTE |
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
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -7,80% | -6,66% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 8 | 12,50% | 0,05 | -6,51% | -5,36% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 15 | 0,00% | 0,00 | -7,80% | -4,69% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 26 | 0,00% | 0,00 | -3,90% | -3,33% | ALTA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -4,05% | -2,91% | MEDIA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | BTC | 8 | 12,50% | 0,05 | -3,25% | -2,68% | MEDIA |
| SHORT RSI 75 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 8 | 0,00% | 0,00 | -3,20% | -2,49% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 15 | 0,00% | 0,00 | -3,90% | -2,35% | MEDIA |
| SHORT RSI 75 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 12 | 16,67% | 0,18 | -5,30% | -2,19% | MEDIA |
| SHORT RSI 70 · leva 5× · Wide | RIDURRE / ESCLUDERE IN CHALLENGER | Motivo uscita | STOP | 22 | 0,00% | 0,00 | -3,20% | -2,05% | ALTA |
| SHORT RSI 70 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ETH | 8 | 25,00% | 0,31 | -2,03% | -1,46% | MEDIA |
| SHORT RSI 70 · leva 20× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | ≥3 punti | 10 | 40,00% | 0,52 | -2,26% | -1,12% | MEDIA |
| SHORT RSI 75 · leva 10× | RIDURRE / ESCLUDERE IN CHALLENGER | Profondità RSI | 1–3 punti | 12 | 16,67% | 0,18 | -2,65% | -1,10% | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 9 | 0,00% | 0,00 | -1,08R | -1,06R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE_HIGH_VOL | 10 | 0,00% | 0,00 | -1,10R | -1,05R | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 10 | 20,00% | 0,48 | -0,45R | -1,01R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 11 | 18,18% | 0,48 | -0,41R | -0,95R | MEDIA |
| SHADOW_COMBO_SCANNER | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 9 | 22,22% | 0,55 | -0,38R | -0,95R | MEDIA |
| Rapida 1H V3 Filtered | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 8 | 12,50% | 0,19 | -0,77R | -0,93R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 17 | 5,88% | 0,11 | -0,90R | -0,88R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Volatilità entrata | HIGH | 22 | 9,09% | 0,13 | -0,87R | -0,82R | ALTA |
| SHADOW_COMBO_TREND | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 8 | 12,50% | 0,29 | -0,67R | -0,81R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | 6–7 | 14 | 21,43% | 0,52 | -0,37R | -0,78R | MEDIA |
| Rapida 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | PEPE | 9 | 11,11% | 0,15 | -0,82R | -0,78R | MEDIA |
| SHADOW_SCANNER_TOP5_BTC | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 12 | 25,00% | 0,73 | -0,20R | -0,75R | MEDIA |
| SHADOW_EMA_TREND_1H | RIDURRE / ESCLUDERE IN CHALLENGER | Regime entrata | RANGE | 8 | 12,50% | 0,29 | -0,66R | -0,74R | MEDIA |
| Bilanciata 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ADA | 8 | 12,50% | 0,25 | -0,72R | -0,70R | MEDIA |
| Forza relativa 1H V1 | RIDURRE / ESCLUDERE IN CHALLENGER | Fascia score | <5 | 13 | 15,38% | 0,38 | -0,54R | -0,69R | MEDIA |
| SHADOW_SCANNER_TOP5_LONG | RIDURRE / ESCLUDERE IN CHALLENGER | Confidenza segnale | BUONA | 16 | 25,00% | 0,64 | -0,27R | -0,69R | MEDIA |
| SHADOW_COMBO_ADAPTIVE_MFE_TRAIL | RIDURRE / ESCLUDERE IN CHALLENGER | Asset | ESPORTS | 9 | 22,22% | 0,56 | -0,35R | -0,68R | MEDIA |

## Metodo di promozione

1. Lo Shadow individua un contesto candidato; 2. si crea un conto Paper challenger separato; 3. il challenger raccoglie almeno 30 eventi futuri; 4. si promuove soltanto se migliora PF, expectancy e drawdown senza dipendere da un singolo asset o regime.

I contatori Paper e Shadow non vengono sommati: molti trade Paper sono un sottoinsieme degli eventi Shadow.
