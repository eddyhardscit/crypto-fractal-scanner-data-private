# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T13:08:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **8616**
- Valutazioni prodotte: **3263**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 378 | 0,174 | 0,043 | 0,106 | 52,9% | 85,7 | VALIDATING |
| TIME_6H | 385 | 0,046 | 0,054 | -0,036 | 56,4% | 80,7 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 388 | 0,204 | 0,000 | 0,124 | 48,7% | 73,8 | VALIDATING |
| TP_R050 | 388 | 0,131 | 0,000 | 0,049 | 46,4% | 73,8 | VALIDATING |
| GB30_R050 | 388 | 0,166 | 0,000 | 0,089 | 47,2% | 73,8 | VALIDATING |
| GB40_R050 | 388 | 0,128 | 0,000 | 0,052 | 46,9% | 73,7 | VALIDATING |
| GB50_R050 | 388 | 0,088 | 0,000 | 0,012 | 46,1% | 73,5 | VALIDATING |
| TP_R200 | 345 | 0,113 | 0,000 | 0,042 | 36,2% | 72,8 | VALIDATING |
| GB20_R100 | 379 | 0,067 | 0,000 | 0,008 | 36,9% | 69,4 | VALIDATING |
| GB30_R100 | 379 | 0,054 | 0,000 | -0,002 | 36,4% | 65,5 | VALIDATING |
| GB40_R100 | 379 | 0,042 | 0,000 | -0,012 | 36,4% | 63,1 | VALIDATING |
| TP_R100 | 379 | 0,040 | 0,000 | -0,018 | 34,8% | 61,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 365 | 0,025 | 0,000 | -0,034 | 28,8% | 57,1 | VALIDATING |
| GB50_R100 | 355 | 0,008 | 0,000 | -0,039 | 32,4% | 51,2 | VALIDATING |
| TIME_24H | 333 | -0,108 | 0,000 | -0,206 | 29,1% | 33,6 | UNDERPERFORMING |
| ATR15_R100 | 374 | -0,037 | 0,000 | -0,086 | 27,5% | 33,4 | VALIDATING |
| BE_R050 | 351 | -0,065 | 0,000 | -0,152 | 32,8% | 32,0 | VALIDATING |
| BE_R100 | 312 | -0,194 | 0,000 | -0,273 | 23,1% | 30,3 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
