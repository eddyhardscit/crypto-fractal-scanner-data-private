# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T16:23:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **8908**
- Valutazioni prodotte: **3266**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 384 | 0,156 | 0,039 | 0,087 | 52,1% | 84,9 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 405 | 0,181 | 0,000 | 0,100 | 48,1% | 73,8 | VALIDATING |
| TP_R050 | 405 | 0,111 | 0,000 | 0,029 | 45,9% | 73,8 | VALIDATING |
| GB30_R050 | 405 | 0,149 | 0,000 | 0,076 | 46,7% | 73,8 | VALIDATING |
| GB40_R050 | 405 | 0,111 | 0,000 | 0,037 | 46,4% | 73,7 | VALIDATING |
| GB50_R050 | 405 | 0,069 | 0,000 | -0,007 | 45,7% | 72,4 | VALIDATING |
| TIME_6H | 398 | 0,028 | 0,049 | -0,054 | 55,5% | 71,6 | VALIDATING |
| TP_R100 | 403 | 0,058 | 0,000 | 0,001 | 36,0% | 69,6 | VALIDATING |
| GB20_R100 | 391 | 0,057 | 0,000 | 0,002 | 36,3% | 69,4 | VALIDATING |
| TP_R150 | 387 | 0,065 | 0,000 | 0,007 | 30,0% | 69,2 | VALIDATING |
| TP_R200 | 353 | 0,090 | 0,000 | 0,014 | 35,4% | 69,1 | VALIDATING |
| GB30_R100 | 391 | 0,041 | 0,000 | -0,013 | 35,8% | 66,3 | VALIDATING |
| GB40_R100 | 390 | 0,027 | 0,000 | -0,026 | 35,6% | 59,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R100 | 368 | -0,008 | 0,000 | -0,053 | 31,8% | 42,7 | VALIDATING |
| ATR15_R100 | 380 | -0,034 | 0,000 | -0,081 | 27,9% | 34,2 | VALIDATING |
| BE_R050 | 361 | -0,068 | 0,000 | -0,148 | 31,9% | 32,1 | VALIDATING |
| ATR20_R100 | 349 | -0,130 | 0,000 | -0,182 | 22,1% | 31,5 | UNDERPERFORMING |
| TIME_24H | 351 | -0,039 | 0,000 | -0,141 | 30,8% | 30,6 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
