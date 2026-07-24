# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T22:08:45+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **18121**
- Valutazioni prodotte: **5256**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R100 | 217 | 0,281 | 0,358 | 0,169 | 70,5% | 95,0 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 217 | 0,293 | 0,386 | 0,174 | 71,0% | 94,9 | ELIGIBLE_FOR_MUTATION |
| GB30_R100 | 217 | 0,266 | 0,386 | 0,154 | 72,4% | 94,9 | ELIGIBLE_FOR_MUTATION |
| GB20_R050 | 217 | 0,268 | 0,334 | 0,171 | 70,0% | 94,9 | VALIDATING |
| GB40_R100 | 215 | 0,213 | 0,322 | 0,098 | 71,2% | 94,9 | ELIGIBLE_FOR_MUTATION |
| GB30_R050 | 217 | 0,215 | 0,286 | 0,110 | 70,0% | 94,9 | VALIDATING |
| GB40_R050 | 217 | 0,159 | 0,241 | 0,056 | 68,2% | 91,0 | VALIDATING |
| GB50_R100 | 212 | 0,158 | 0,322 | 0,048 | 70,8% | 91,0 | VALIDATING |
| GB50_R050 | 215 | 0,155 | 0,233 | 0,059 | 68,4% | 90,9 | VALIDATING |
| TP_R150 | 196 | 0,160 | 0,125 | 0,027 | 56,6% | 90,2 | ELIGIBLE_FOR_MUTATION |
| TP_R050 | 217 | 0,127 | 0,279 | 0,034 | 69,1% | 89,9 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 650 | 0,102 | 0,000 | 0,039 | 46,0% | 70,0 | VALIDATING |
| TP_R150 | 628 | 0,069 | 0,000 | 0,017 | 28,3% | 69,8 | VALIDATING |
| GB20_R100 | 636 | 0,069 | 0,000 | 0,023 | 37,3% | 69,7 | VALIDATING |
| GB30_R050 | 650 | 0,062 | 0,000 | -0,005 | 44,5% | 69,3 | VALIDATING |
| GB30_R100 | 636 | 0,031 | 0,000 | -0,021 | 36,9% | 61,9 | VALIDATING |
| TP_R100 | 636 | 0,036 | 0,000 | -0,018 | 35,1% | 60,2 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 611 | 0,032 | 0,000 | -0,036 | 34,5% | 56,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
