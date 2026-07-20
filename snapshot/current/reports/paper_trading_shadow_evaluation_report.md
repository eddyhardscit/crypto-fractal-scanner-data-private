# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T08:23:45+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **1233**
- Valutazioni prodotte: **1686**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 29 | 0,608 | 0,406 | 0,340 | 62,1% | 82,0 | INSUFFICIENT_DATA |
| GB30_R050 | 29 | 0,560 | 0,349 | 0,306 | 62,1% | 82,0 | INSUFFICIENT_DATA |
| GB40_R050 | 29 | 0,511 | 0,291 | 0,272 | 62,1% | 81,9 | INSUFFICIENT_DATA |
| TP_R050 | 29 | 0,529 | 0,428 | 0,312 | 62,1% | 81,9 | INSUFFICIENT_DATA |
| GB50_R050 | 29 | 0,493 | 0,233 | 0,258 | 62,1% | 81,9 | INSUFFICIENT_DATA |
| GB20_R100 | 29 | 0,341 | 0,033 | 0,109 | 55,2% | 70,6 | INSUFFICIENT_DATA |
| GB30_R100 | 29 | 0,291 | 0,033 | 0,088 | 55,2% | 70,5 | INSUFFICIENT_DATA |
| GB40_R100 | 29 | 0,241 | 0,033 | 0,047 | 55,2% | 70,4 | INSUFFICIENT_DATA |
| TP_R100 | 29 | 0,287 | 0,033 | 0,083 | 55,2% | 70,2 | INSUFFICIENT_DATA |
| GB50_R100 | 29 | 0,192 | 0,033 | -0,001 | 55,2% | 70,0 | INSUFFICIENT_DATA |
| BE_R050 | 28 | 0,280 | 0,000 | 0,113 | 39,3% | 55,6 | INSUFFICIENT_DATA |
| TP_R150 | 28 | 0,062 | 0,000 | -0,148 | 39,3% | 39,2 | INSUFFICIENT_DATA |
| ATR15_R100 | 28 | 0,029 | 0,000 | -0,083 | 46,4% | 30,1 | INSUFFICIENT_DATA |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| BE_R100 | 25 | 0,029 | 0,000 | -0,093 | 40,0% | 28,4 | INSUFFICIENT_DATA |
| TP_R200 | 4 | 0,075 | 0,000 | -0,150 | 25,0% | 28,3 | INSUFFICIENT_DATA |
| ATR30_R100 | 25 | 0,029 | 0,000 | -0,098 | 40,0% | 27,6 | INSUFFICIENT_DATA |
| ATR20_R100 | 25 | 0,029 | 0,000 | -0,107 | 40,0% | 27,3 | INSUFFICIENT_DATA |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| TIME_6H | 28 | -0,016 | 0,000 | -0,197 | 42,9% | 20,5 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
