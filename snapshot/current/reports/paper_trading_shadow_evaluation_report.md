# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T16:53:44+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **17049**
- Valutazioni prodotte: **4989**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 169 | 0,378 | 0,335 | 0,260 | 74,6% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB30_R050 | 169 | 0,323 | 0,287 | 0,221 | 74,6% | 98,5 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 168 | 0,375 | 0,326 | 0,253 | 73,2% | 94,8 | VALIDATING |
| TP_R100 | 168 | 0,342 | 0,287 | 0,220 | 72,6% | 94,8 | VALIDATING |
| GB30_R100 | 168 | 0,328 | 0,288 | 0,214 | 75,0% | 94,8 | VALIDATING |
| GB40_R100 | 167 | 0,273 | 0,287 | 0,160 | 73,1% | 94,7 | VALIDATING |
| GB40_R050 | 169 | 0,264 | 0,243 | 0,159 | 72,8% | 94,7 | VALIDATING |
| GB50_R100 | 164 | 0,228 | 0,302 | 0,124 | 72,6% | 94,7 | VALIDATING |
| GB50_R050 | 168 | 0,253 | 0,243 | 0,162 | 72,0% | 94,5 | VALIDATING |
| TP_R050 | 169 | 0,207 | 0,287 | 0,106 | 72,8% | 93,3 | VALIDATING |
| TP_R150 | 147 | 0,112 | 0,053 | -0,029 | 55,8% | 81,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 642 | 0,096 | 0,000 | 0,032 | 45,3% | 70,0 | VALIDATING |
| TP_R150 | 626 | 0,065 | 0,000 | 0,015 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 636 | 0,069 | 0,000 | 0,023 | 37,3% | 69,7 | VALIDATING |
| GB30_R050 | 642 | 0,056 | 0,000 | -0,010 | 43,8% | 68,5 | VALIDATING |
| GB30_R100 | 636 | 0,031 | 0,000 | -0,021 | 36,9% | 61,9 | VALIDATING |
| TP_R100 | 636 | 0,036 | 0,000 | -0,018 | 35,1% | 60,2 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TIME_12H | 645 | 0,034 | 0,000 | -0,045 | 43,6% | 58,5 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
