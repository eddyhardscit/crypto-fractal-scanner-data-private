# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T20:08:49+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **18019**
- Valutazioni prodotte: **5236**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R100 | 216 | 0,287 | 0,372 | 0,173 | 70,8% | 95,0 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 216 | 0,299 | 0,386 | 0,178 | 71,3% | 94,9 | ELIGIBLE_FOR_MUTATION |
| GB30_R100 | 216 | 0,272 | 0,386 | 0,161 | 72,7% | 94,9 | ELIGIBLE_FOR_MUTATION |
| GB20_R050 | 216 | 0,276 | 0,334 | 0,177 | 70,4% | 94,9 | VALIDATING |
| GB40_R100 | 215 | 0,213 | 0,322 | 0,098 | 71,2% | 94,9 | ELIGIBLE_FOR_MUTATION |
| GB30_R050 | 216 | 0,223 | 0,287 | 0,121 | 70,4% | 94,9 | VALIDATING |
| GB40_R050 | 216 | 0,167 | 0,242 | 0,066 | 68,5% | 91,0 | VALIDATING |
| GB50_R100 | 212 | 0,158 | 0,322 | 0,048 | 70,8% | 91,0 | VALIDATING |
| GB50_R050 | 215 | 0,155 | 0,233 | 0,059 | 68,4% | 90,9 | VALIDATING |
| TP_R150 | 194 | 0,160 | 0,125 | 0,024 | 56,7% | 90,3 | ELIGIBLE_FOR_MUTATION |
| TP_R050 | 216 | 0,134 | 0,279 | 0,043 | 69,4% | 89,9 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 642 | 0,096 | 0,000 | 0,032 | 45,3% | 70,0 | VALIDATING |
| TP_R150 | 626 | 0,065 | 0,000 | 0,015 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 636 | 0,069 | 0,000 | 0,023 | 37,3% | 69,7 | VALIDATING |
| GB30_R050 | 642 | 0,056 | 0,000 | -0,010 | 43,8% | 68,5 | VALIDATING |
| GB30_R100 | 636 | 0,031 | 0,000 | -0,021 | 36,9% | 61,9 | VALIDATING |
| TP_R100 | 636 | 0,036 | 0,000 | -0,018 | 35,1% | 60,2 | VALIDATING |
| TIME_6H | 204 | 0,024 | 0,098 | -0,097 | 55,4% | 59,6 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
