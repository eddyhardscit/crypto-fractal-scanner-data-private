# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T13:23:47+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **20461**
- Valutazioni prodotte: **5771**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB30_R100 | 347 | 0,112 | 0,189 | 0,023 | 59,9% | 89,8 | VALIDATING |
| TP_R200 | 281 | 0,175 | 0,217 | 0,058 | 59,1% | 88,7 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 347 | 0,139 | 0,147 | 0,056 | 57,9% | 87,8 | VALIDATING |
| GB40_R100 | 345 | 0,065 | 0,154 | -0,021 | 58,0% | 84,7 | VALIDATING |
| TP_R100 | 347 | 0,103 | 0,120 | 0,013 | 54,2% | 84,2 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 660 | 0,092 | 0,000 | 0,028 | 46,1% | 70,0 | VALIDATING |
| TP_R150 | 633 | 0,063 | 0,000 | 0,012 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 645 | 0,065 | 0,000 | 0,015 | 37,4% | 69,8 | VALIDATING |
| TP_R150 | 312 | 0,126 | 0,000 | 0,032 | 43,3% | 69,6 | VALIDATING |
| GB30_R050 | 660 | 0,051 | 0,000 | -0,016 | 44,5% | 67,7 | VALIDATING |
| TP_R200 | 623 | 0,050 | 0,000 | -0,013 | 35,2% | 64,0 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 645 | 0,033 | 0,000 | -0,022 | 35,2% | 58,7 | VALIDATING |
| GB30_R100 | 645 | 0,026 | 0,000 | -0,029 | 37,1% | 55,2 | VALIDATING |
| GB20_R050 | 351 | 0,006 | 0,104 | -0,083 | 55,0% | 55,1 | VALIDATING |
| GB50_R100 | 336 | -0,003 | 0,074 | -0,081 | 55,1% | 53,8 | VALIDATING |
| TP_R050 | 660 | 0,013 | 0,000 | -0,054 | 43,5% | 51,5 | VALIDATING |
| TIME_12H | 663 | 0,022 | 0,000 | -0,048 | 42,5% | 50,5 | VALIDATING |
| GB30_R050 | 351 | -0,029 | 0,093 | -0,128 | 54,1% | 49,8 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
