# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T03:08:34+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **583**
- Valutazioni prodotte: **1028**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| BE_R050 | 7 | 0,953 | 1,034 | 0,777 | 100,0% | 79,8 | INSUFFICIENT_DATA |
| TP_R050 | 7 | 1,382 | 1,535 | 1,063 | 100,0% | 79,8 | INSUFFICIENT_DATA |
| GB50_R050 | 7 | 1,243 | 1,363 | 0,969 | 100,0% | 79,8 | INSUFFICIENT_DATA |
| GB30_R050 | 7 | 1,359 | 1,494 | 1,046 | 100,0% | 79,8 | INSUFFICIENT_DATA |
| GB40_R050 | 7 | 1,301 | 1,429 | 1,008 | 100,0% | 79,8 | INSUFFICIENT_DATA |
| GB20_R050 | 7 | 1,417 | 1,560 | 1,084 | 100,0% | 79,8 | INSUFFICIENT_DATA |
| ATR15_R100 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| ATR20_R100 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| ATR30_R100 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| BE_R100 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| GB20_R100 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| GB30_R100 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| GB40_R100 | 7 | 0,096 | 0,033 | 0,033 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| GB50_R100 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| TIME_12H | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| TIME_24H | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| TIME_6H | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| TP_R100 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| TP_R150 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |
| TP_R200 | 7 | 0,096 | 0,033 | 0,036 | 100,0% | 76,4 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
