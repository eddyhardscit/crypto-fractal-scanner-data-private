# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T07:08:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **7741**
- Valutazioni prodotte: **3158**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 351 | 0,203 | 0,000 | 0,117 | 47,9% | 73,8 | VALIDATING |
| TP_R200 | 316 | 0,110 | 0,000 | 0,037 | 34,8% | 73,0 | VALIDATING |
| TIME_12H | 333 | 0,153 | 0,000 | 0,081 | 49,8% | 72,6 | VALIDATING |
| TP_R050 | 351 | 0,130 | 0,000 | 0,040 | 45,3% | 70,2 | VALIDATING |
| GB30_R050 | 351 | 0,164 | 0,000 | 0,079 | 46,2% | 70,0 | VALIDATING |
| GB40_R050 | 351 | 0,126 | 0,000 | 0,039 | 45,9% | 70,0 | VALIDATING |
| GB50_R050 | 351 | 0,085 | 0,000 | 0,005 | 45,0% | 69,9 | VALIDATING |
| GB20_R100 | 348 | 0,062 | 0,000 | -0,001 | 35,9% | 65,5 | VALIDATING |
| GB30_R100 | 341 | 0,040 | 0,000 | -0,018 | 34,3% | 61,5 | VALIDATING |
| TP_R100 | 349 | 0,036 | 0,000 | -0,023 | 33,8% | 59,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TIME_6H | 351 | 0,005 | 0,036 | -0,086 | 53,0% | 56,4 | VALIDATING |
| GB40_R100 | 329 | 0,007 | 0,000 | -0,051 | 34,0% | 48,9 | VALIDATING |
| TP_R150 | 333 | 0,009 | 0,000 | -0,054 | 27,0% | 45,0 | VALIDATING |
| GB50_R100 | 327 | 0,002 | 0,000 | -0,050 | 31,2% | 43,7 | VALIDATING |
| BE_R050 | 315 | -0,074 | 0,000 | -0,167 | 32,4% | 35,8 | VALIDATING |
| ATR20_R100 | 316 | -0,142 | 0,000 | -0,197 | 20,6% | 31,7 | UNDERPERFORMING |
| ATR15_R100 | 323 | -0,073 | 0,000 | -0,114 | 23,8% | 31,2 | UNDERPERFORMING |
| BE_R100 | 283 | -0,212 | 0,000 | -0,295 | 21,2% | 30,3 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
