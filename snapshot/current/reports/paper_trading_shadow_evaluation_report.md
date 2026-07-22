# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T21:23:40+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **10260**
- Valutazioni prodotte: **3284**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 465 | 0,124 | 0,000 | 0,046 | 46,7% | 73,8 | VALIDATING |
| GB40_R050 | 465 | 0,125 | 0,000 | 0,055 | 46,7% | 73,8 | VALIDATING |
| GB20_R050 | 465 | 0,199 | 0,000 | 0,123 | 48,4% | 73,8 | VALIDATING |
| GB30_R050 | 465 | 0,164 | 0,000 | 0,100 | 47,1% | 73,7 | VALIDATING |
| GB20_R100 | 458 | 0,108 | 0,000 | 0,058 | 37,6% | 73,5 | VALIDATING |
| TP_R100 | 458 | 0,076 | 0,000 | 0,022 | 35,8% | 73,5 | VALIDATING |
| GB30_R100 | 457 | 0,083 | 0,000 | 0,034 | 37,2% | 73,5 | VALIDATING |
| GB40_R100 | 457 | 0,061 | 0,000 | 0,011 | 37,2% | 73,3 | VALIDATING |
| GB50_R100 | 455 | 0,045 | 0,000 | -0,003 | 34,9% | 72,6 | VALIDATING |
| GB50_R050 | 465 | 0,081 | 0,000 | 0,017 | 46,0% | 69,9 | VALIDATING |
| TP_R150 | 434 | 0,048 | 0,000 | -0,009 | 27,6% | 68,0 | VALIDATING |
| TIME_6H | 464 | 0,022 | 0,036 | -0,055 | 53,0% | 66,6 | VALIDATING |
| TIME_12H | 453 | 0,045 | 0,000 | -0,032 | 45,0% | 63,8 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 409 | -0,025 | 0,000 | -0,100 | 30,6% | 39,1 | VALIDATING |
| TIME_24H | 425 | -0,076 | 0,000 | -0,176 | 28,5% | 34,6 | VALIDATING |
| ATR15_R100 | 449 | -0,040 | 0,000 | -0,086 | 28,7% | 33,2 | VALIDATING |
| BE_R050 | 421 | -0,075 | 0,000 | -0,147 | 29,7% | 32,1 | UNDERPERFORMING |
| ATR30_R100 | 429 | -0,103 | 0,000 | -0,176 | 23,8% | 31,0 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
