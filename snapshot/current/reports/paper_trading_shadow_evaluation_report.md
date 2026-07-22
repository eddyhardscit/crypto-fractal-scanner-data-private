# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T09:08:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **8307**
- Valutazioni prodotte: **3241**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 356 | 0,175 | 0,039 | 0,099 | 52,5% | 85,2 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 380 | 0,134 | 0,000 | 0,051 | 46,1% | 73,9 | VALIDATING |
| GB30_R050 | 380 | 0,169 | 0,000 | 0,088 | 46,8% | 73,9 | VALIDATING |
| GB40_R050 | 380 | 0,131 | 0,000 | 0,053 | 46,6% | 73,8 | VALIDATING |
| GB20_R050 | 380 | 0,208 | 0,000 | 0,124 | 48,4% | 73,8 | VALIDATING |
| TIME_6H | 371 | 0,033 | 0,043 | -0,047 | 55,0% | 73,7 | VALIDATING |
| GB50_R050 | 380 | 0,090 | 0,000 | 0,012 | 45,8% | 73,6 | VALIDATING |
| TP_R200 | 338 | 0,112 | 0,000 | 0,044 | 35,5% | 72,8 | VALIDATING |
| GB20_R100 | 371 | 0,066 | 0,000 | 0,006 | 36,4% | 65,8 | VALIDATING |
| GB30_R100 | 371 | 0,050 | 0,000 | -0,008 | 35,6% | 64,5 | VALIDATING |
| TP_R100 | 371 | 0,038 | 0,000 | -0,021 | 34,2% | 60,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB40_R100 | 352 | 0,011 | 0,000 | -0,043 | 34,7% | 51,6 | VALIDATING |
| GB50_R100 | 348 | 0,004 | 0,000 | -0,045 | 31,6% | 49,0 | VALIDATING |
| TP_R150 | 355 | 0,014 | 0,000 | -0,043 | 27,6% | 48,6 | VALIDATING |
| ATR15_R100 | 342 | -0,062 | 0,000 | -0,103 | 24,9% | 35,2 | UNDERPERFORMING |
| BE_R100 | 303 | -0,192 | 0,000 | -0,273 | 22,4% | 34,5 | UNDERPERFORMING |
| BE_R050 | 342 | -0,059 | 0,000 | -0,141 | 32,5% | 32,0 | VALIDATING |
| ATR20_R100 | 336 | -0,127 | 0,000 | -0,180 | 21,7% | 31,4 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
