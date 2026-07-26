# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-26T00:39:21+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **26770**
- Valutazioni prodotte: **10245**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB40_R040 | 59 | 0,610 | 0,711 | 0,450 | 72,9% | 90,6 | VALIDATING |
| GB20_R040 | 59 | 0,641 | 0,689 | 0,477 | 78,0% | 90,5 | VALIDATING |
| TP_R100 | 59 | 0,666 | 0,414 | 0,497 | 78,0% | 90,5 | VALIDATING |
| GB30_R040 | 59 | 0,609 | 0,639 | 0,452 | 72,9% | 90,5 | VALIDATING |
| GB20_R100 | 59 | 0,686 | 0,358 | 0,506 | 78,0% | 90,5 | VALIDATING |
| TP_R040 | 59 | 0,594 | 0,685 | 0,419 | 72,9% | 90,5 | VALIDATING |
| GB20_R075 | 59 | 0,632 | 0,298 | 0,456 | 72,9% | 90,5 | VALIDATING |
| TP_R035 | 59 | 0,555 | 0,635 | 0,375 | 72,9% | 90,5 | VALIDATING |
| GB30_R100 | 59 | 0,616 | 0,298 | 0,446 | 78,0% | 90,4 | VALIDATING |
| GB30_R075 | 59 | 0,564 | 0,298 | 0,397 | 67,8% | 90,4 | VALIDATING |
| TP_R075 | 59 | 0,547 | 0,298 | 0,405 | 79,7% | 90,4 | VALIDATING |
| GB40_R050 | 59 | 0,550 | 0,711 | 0,383 | 67,8% | 90,4 | VALIDATING |
| GB40_R075 | 59 | 0,496 | 0,298 | 0,342 | 67,8% | 90,4 | VALIDATING |
| GB40_R100 | 59 | 0,539 | 0,298 | 0,383 | 78,0% | 90,4 | VALIDATING |
| TP_R050 | 59 | 0,598 | 0,785 | 0,431 | 67,8% | 90,4 | VALIDATING |
| GB50_R050 | 59 | 0,518 | 0,640 | 0,366 | 71,2% | 90,4 | VALIDATING |
| GB20_R050 | 59 | 0,578 | 0,689 | 0,432 | 72,9% | 90,4 | VALIDATING |
| GB50_R075 | 59 | 0,451 | 0,298 | 0,306 | 71,2% | 90,4 | VALIDATING |
| GB30_R050 | 59 | 0,547 | 0,639 | 0,377 | 67,8% | 90,3 | VALIDATING |
| TP_R060 | 59 | 0,456 | 0,298 | 0,318 | 72,9% | 90,3 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
