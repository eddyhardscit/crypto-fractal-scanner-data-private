# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T11:03:08+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **15753**
- Valutazioni prodotte: **4372**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 124 | 0,481 | 0,359 | 0,346 | 80,6% | 98,7 | ELIGIBLE_FOR_MUTATION |
| GB30_R050 | 124 | 0,428 | 0,294 | 0,309 | 80,6% | 98,7 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 121 | 0,492 | 0,394 | 0,370 | 79,3% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB30_R100 | 121 | 0,454 | 0,322 | 0,341 | 81,8% | 98,6 | ELIGIBLE_FOR_MUTATION |
| TP_R100 | 121 | 0,451 | 0,322 | 0,338 | 78,5% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB40_R050 | 124 | 0,369 | 0,283 | 0,250 | 78,2% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB40_R100 | 120 | 0,394 | 0,305 | 0,294 | 78,3% | 98,5 | ELIGIBLE_FOR_MUTATION |
| GB50_R050 | 124 | 0,359 | 0,287 | 0,260 | 77,4% | 98,4 | ELIGIBLE_FOR_MUTATION |
| GB50_R100 | 120 | 0,342 | 0,322 | 0,247 | 76,7% | 98,3 | ELIGIBLE_FOR_MUTATION |
| TP_R050 | 124 | 0,278 | 0,287 | 0,165 | 78,2% | 96,8 | ELIGIBLE_FOR_MUTATION |
| ATR15_R100 | 120 | 0,044 | 0,116 | -0,048 | 62,5% | 84,0 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 622 | 0,102 | 0,000 | 0,034 | 45,2% | 70,0 | VALIDATING |
| GB20_R100 | 610 | 0,062 | 0,000 | 0,013 | 36,6% | 69,7 | VALIDATING |
| GB30_R050 | 622 | 0,062 | 0,000 | -0,002 | 43,6% | 69,7 | VALIDATING |
| TP_R150 | 599 | 0,058 | 0,000 | 0,009 | 27,4% | 69,7 | VALIDATING |
| TIME_12H | 625 | 0,039 | 0,000 | -0,038 | 43,7% | 61,2 | VALIDATING |
| GB30_R100 | 610 | 0,024 | 0,000 | -0,024 | 36,1% | 59,0 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 610 | 0,030 | 0,000 | -0,022 | 34,1% | 57,8 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
