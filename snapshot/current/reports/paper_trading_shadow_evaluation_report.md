# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T18:38:45+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **12856**
- Valutazioni prodotte: **3968**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| ATR20_R100 | 22 | 0,339 | 0,411 | 0,208 | 95,5% | 83,1 | INSUFFICIENT_DATA |
| ATR30_R100 | 19 | 0,391 | 0,411 | 0,352 | 100,0% | 83,1 | INSUFFICIENT_DATA |
| BE_R050 | 19 | 0,391 | 0,411 | 0,352 | 100,0% | 83,1 | INSUFFICIENT_DATA |
| BE_R100 | 19 | 0,391 | 0,411 | 0,351 | 100,0% | 83,1 | INSUFFICIENT_DATA |
| GB40_R050 | 23 | 0,588 | 0,477 | 0,338 | 91,3% | 82,8 | INSUFFICIENT_DATA |
| GB30_R050 | 23 | 0,657 | 0,477 | 0,406 | 95,7% | 82,8 | INSUFFICIENT_DATA |
| GB20_R100 | 23 | 0,784 | 0,477 | 0,575 | 100,0% | 82,7 | INSUFFICIENT_DATA |
| GB20_R050 | 23 | 0,727 | 0,477 | 0,453 | 95,7% | 82,7 | INSUFFICIENT_DATA |
| TP_R100 | 23 | 0,606 | 0,477 | 0,377 | 91,3% | 82,7 | INSUFFICIENT_DATA |
| GB40_R100 | 22 | 0,666 | 0,499 | 0,497 | 95,5% | 82,6 | INSUFFICIENT_DATA |
| GB30_R100 | 22 | 0,736 | 0,499 | 0,535 | 100,0% | 82,6 | INSUFFICIENT_DATA |
| ATR15_R100 | 22 | 0,395 | 0,411 | 0,295 | 95,5% | 82,5 | INSUFFICIENT_DATA |
| GB50_R050 | 23 | 0,619 | 0,477 | 0,373 | 95,7% | 82,4 | INSUFFICIENT_DATA |
| GB50_R100 | 22 | 0,702 | 0,499 | 0,522 | 100,0% | 82,2 | INSUFFICIENT_DATA |
| TP_R200 | 23 | 0,260 | 0,322 | 0,014 | 73,9% | 79,0 | INSUFFICIENT_DATA |
| TP_R050 | 23 | 0,389 | 0,477 | 0,171 | 91,3% | 77,9 | INSUFFICIENT_DATA |
| TP_R150 | 23 | 0,173 | 0,287 | -0,026 | 65,2% | 75,2 | INSUFFICIENT_DATA |
| TIME_6H | 555 | 0,036 | 0,043 | -0,036 | 53,2% | 74,6 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB30_R050 | 580 | 0,089 | 0,000 | 0,021 | 44,1% | 70,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
