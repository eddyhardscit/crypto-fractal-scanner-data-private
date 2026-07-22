# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T10:08:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **8415**
- Valutazioni prodotte: **3241**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 358 | 0,178 | 0,041 | 0,107 | 52,8% | 85,5 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 381 | 0,134 | 0,000 | 0,051 | 46,2% | 73,9 | VALIDATING |
| GB40_R050 | 381 | 0,132 | 0,000 | 0,052 | 46,7% | 73,8 | VALIDATING |
| GB20_R050 | 381 | 0,209 | 0,000 | 0,127 | 48,6% | 73,8 | VALIDATING |
| GB30_R050 | 381 | 0,170 | 0,000 | 0,089 | 47,0% | 73,8 | VALIDATING |
| TIME_6H | 371 | 0,033 | 0,043 | -0,047 | 55,0% | 73,7 | VALIDATING |
| GB50_R050 | 381 | 0,091 | 0,000 | 0,014 | 45,9% | 73,6 | VALIDATING |
| TP_R200 | 338 | 0,112 | 0,000 | 0,044 | 35,5% | 72,8 | VALIDATING |
| GB20_R100 | 372 | 0,068 | 0,000 | 0,010 | 36,6% | 65,8 | VALIDATING |
| GB30_R100 | 372 | 0,052 | 0,000 | -0,007 | 35,8% | 64,8 | VALIDATING |
| TP_R100 | 372 | 0,040 | 0,000 | -0,018 | 34,4% | 61,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 356 | 0,018 | 0,000 | -0,039 | 27,8% | 53,9 | VALIDATING |
| GB40_R100 | 353 | 0,013 | 0,000 | -0,043 | 34,8% | 52,2 | VALIDATING |
| GB50_R100 | 349 | 0,006 | 0,000 | -0,041 | 31,8% | 50,2 | VALIDATING |
| BE_R050 | 345 | -0,068 | 0,000 | -0,156 | 32,2% | 32,0 | VALIDATING |
| ATR15_R100 | 345 | -0,071 | 0,000 | -0,111 | 24,6% | 31,4 | UNDERPERFORMING |
| ATR20_R100 | 339 | -0,136 | 0,000 | -0,189 | 21,5% | 31,4 | UNDERPERFORMING |
| BE_R100 | 306 | -0,200 | 0,000 | -0,281 | 22,2% | 30,7 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
