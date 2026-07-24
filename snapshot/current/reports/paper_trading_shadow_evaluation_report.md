# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T19:08:47+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **17426**
- Valutazioni prodotte: **5045**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R100 | 192 | 0,244 | 0,269 | 0,121 | 67,7% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 192 | 0,262 | 0,273 | 0,143 | 68,2% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB20_R050 | 192 | 0,253 | 0,256 | 0,138 | 67,7% | 94,9 | VALIDATING |
| GB30_R100 | 192 | 0,225 | 0,273 | 0,109 | 69,8% | 94,9 | VALIDATING |
| GB30_R050 | 192 | 0,196 | 0,243 | 0,082 | 67,7% | 94,8 | VALIDATING |
| GB40_R100 | 191 | 0,165 | 0,243 | 0,051 | 68,1% | 94,8 | VALIDATING |
| GB40_R050 | 192 | 0,135 | 0,211 | 0,030 | 65,6% | 94,7 | VALIDATING |
| GB50_R050 | 191 | 0,121 | 0,156 | 0,018 | 65,4% | 94,5 | VALIDATING |
| GB50_R100 | 188 | 0,108 | 0,243 | -0,007 | 67,6% | 93,5 | VALIDATING |
| TP_R050 | 192 | 0,093 | 0,254 | -0,002 | 66,1% | 93,2 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 144 | 0,090 | 0,104 | -0,092 | 58,3% | 73,8 | VALIDATING |
| TP_R150 | 169 | 0,093 | 0,039 | -0,052 | 52,1% | 70,3 | VALIDATING |
| GB20_R050 | 642 | 0,096 | 0,000 | 0,032 | 45,3% | 70,0 | VALIDATING |
| TP_R150 | 626 | 0,065 | 0,000 | 0,015 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 636 | 0,069 | 0,000 | 0,023 | 37,3% | 69,7 | VALIDATING |
| GB30_R050 | 642 | 0,056 | 0,000 | -0,010 | 43,8% | 68,5 | VALIDATING |
| GB30_R100 | 636 | 0,031 | 0,000 | -0,021 | 36,9% | 61,9 | VALIDATING |
| TP_R100 | 636 | 0,036 | 0,000 | -0,018 | 35,1% | 60,2 | VALIDATING |
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
