# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-26T01:38:47+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **26854**
- Valutazioni prodotte: **10286**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R040 | 64 | 0,510 | 0,689 | 0,326 | 71,9% | 91,5 | VALIDATING |
| TP_R040 | 64 | 0,462 | 0,685 | 0,267 | 67,2% | 91,5 | VALIDATING |
| TP_R035 | 64 | 0,421 | 0,635 | 0,215 | 67,2% | 91,5 | VALIDATING |
| GB20_R050 | 64 | 0,452 | 0,659 | 0,274 | 67,2% | 91,4 | VALIDATING |
| GB30_R040 | 61 | 0,553 | 0,639 | 0,378 | 70,5% | 90,9 | VALIDATING |
| GB30_R050 | 61 | 0,493 | 0,639 | 0,318 | 65,6% | 90,8 | VALIDATING |
| GB40_R040 | 59 | 0,610 | 0,711 | 0,450 | 72,9% | 90,6 | VALIDATING |
| GB20_R100 | 59 | 0,686 | 0,358 | 0,506 | 78,0% | 90,5 | VALIDATING |
| GB20_R075 | 59 | 0,632 | 0,298 | 0,456 | 72,9% | 90,5 | VALIDATING |
| GB30_R100 | 59 | 0,616 | 0,298 | 0,446 | 78,0% | 90,4 | VALIDATING |
| GB30_R075 | 59 | 0,564 | 0,298 | 0,397 | 67,8% | 90,4 | VALIDATING |
| GB40_R050 | 59 | 0,550 | 0,711 | 0,383 | 67,8% | 90,4 | VALIDATING |
| GB40_R075 | 59 | 0,496 | 0,298 | 0,342 | 67,8% | 90,4 | VALIDATING |
| GB40_R100 | 59 | 0,539 | 0,298 | 0,383 | 78,0% | 90,4 | VALIDATING |
| GB50_R050 | 59 | 0,518 | 0,640 | 0,366 | 71,2% | 90,4 | VALIDATING |
| GB50_R075 | 59 | 0,451 | 0,298 | 0,306 | 71,2% | 90,4 | VALIDATING |
| GB50_R100 | 59 | 0,461 | 0,298 | 0,304 | 71,2% | 90,3 | VALIDATING |
| ATR10_R050 | 59 | 0,339 | 0,359 | 0,220 | 69,5% | 90,0 | VALIDATING |
| TP_R050 | 64 | 0,473 | 0,585 | 0,269 | 62,5% | 88,9 | VALIDATING |
| TP_R100 | 64 | 0,575 | 0,357 | 0,401 | 71,9% | 87,8 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
