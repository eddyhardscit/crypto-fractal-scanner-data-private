# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T15:38:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **11835**
- Valutazioni prodotte: **3476**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 532 | 0,070 | 0,043 | 0,000 | 53,8% | 83,5 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 546 | 0,189 | 0,000 | 0,124 | 46,9% | 73,8 | VALIDATING |
| TP_R050 | 547 | 0,098 | 0,000 | 0,029 | 44,1% | 73,8 | VALIDATING |
| GB30_R050 | 546 | 0,151 | 0,000 | 0,085 | 45,8% | 73,8 | VALIDATING |
| GB40_R050 | 546 | 0,110 | 0,000 | 0,043 | 45,2% | 73,8 | VALIDATING |
| GB50_R050 | 543 | 0,071 | 0,000 | 0,006 | 43,3% | 73,7 | VALIDATING |
| GB20_R100 | 537 | 0,089 | 0,000 | 0,041 | 35,4% | 73,5 | VALIDATING |
| GB30_R100 | 537 | 0,060 | 0,000 | 0,015 | 35,0% | 69,7 | VALIDATING |
| TP_R100 | 537 | 0,058 | 0,000 | 0,003 | 33,5% | 69,6 | VALIDATING |
| TIME_12H | 520 | 0,067 | 0,000 | 0,008 | 45,0% | 69,0 | VALIDATING |
| GB40_R100 | 537 | 0,034 | 0,000 | -0,015 | 35,0% | 59,9 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 523 | 0,032 | 0,000 | -0,017 | 25,4% | 58,7 | VALIDATING |
| GB50_R100 | 533 | 0,016 | 0,000 | -0,032 | 31,5% | 51,4 | VALIDATING |
| ATR15_R100 | 513 | -0,044 | 0,000 | -0,087 | 27,1% | 33,4 | UNDERPERFORMING |
| BE_R050 | 490 | -0,085 | 0,000 | -0,152 | 28,8% | 32,3 | UNDERPERFORMING |
| TP_R200 | 493 | -0,033 | 0,000 | -0,097 | 28,8% | 32,3 | VALIDATING |
| TIME_24H | 514 | -0,044 | 0,000 | -0,138 | 29,6% | 31,1 | VALIDATING |
| ATR20_R100 | 509 | -0,095 | 0,000 | -0,140 | 22,4% | 30,8 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
