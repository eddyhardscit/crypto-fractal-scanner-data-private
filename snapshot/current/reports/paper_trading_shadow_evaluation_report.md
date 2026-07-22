# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T23:23:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **10314**
- Valutazioni prodotte: **3284**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 466 | 0,124 | 0,000 | 0,048 | 46,6% | 73,8 | VALIDATING |
| GB40_R050 | 466 | 0,124 | 0,000 | 0,055 | 46,6% | 73,8 | VALIDATING |
| GB20_R050 | 466 | 0,198 | 0,000 | 0,122 | 48,3% | 73,8 | VALIDATING |
| GB30_R050 | 466 | 0,164 | 0,000 | 0,097 | 47,0% | 73,7 | VALIDATING |
| GB20_R100 | 459 | 0,108 | 0,000 | 0,059 | 37,5% | 73,5 | VALIDATING |
| TP_R100 | 459 | 0,076 | 0,000 | 0,021 | 35,7% | 73,5 | VALIDATING |
| GB30_R100 | 459 | 0,082 | 0,000 | 0,034 | 37,0% | 73,5 | VALIDATING |
| GB40_R100 | 458 | 0,060 | 0,000 | 0,010 | 37,1% | 73,3 | VALIDATING |
| GB50_R100 | 456 | 0,045 | 0,000 | -0,002 | 34,9% | 72,6 | VALIDATING |
| GB50_R050 | 466 | 0,081 | 0,000 | 0,015 | 45,9% | 69,9 | VALIDATING |
| TP_R150 | 435 | 0,048 | 0,000 | -0,010 | 27,6% | 67,8 | VALIDATING |
| TIME_6H | 465 | 0,022 | 0,036 | -0,057 | 53,1% | 66,6 | VALIDATING |
| TIME_12H | 461 | 0,041 | 0,000 | -0,028 | 44,7% | 63,1 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 411 | -0,024 | 0,000 | -0,101 | 30,7% | 39,1 | VALIDATING |
| TIME_24H | 441 | -0,068 | 0,000 | -0,166 | 29,0% | 34,7 | VALIDATING |
| ATR15_R100 | 450 | -0,040 | 0,000 | -0,083 | 28,7% | 33,6 | VALIDATING |
| BE_R050 | 423 | -0,079 | 0,000 | -0,156 | 29,6% | 32,1 | UNDERPERFORMING |
| ATR30_R100 | 438 | -0,112 | 0,000 | -0,181 | 23,3% | 31,0 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
