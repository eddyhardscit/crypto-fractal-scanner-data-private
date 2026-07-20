# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T02:08:37+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **415**
- Valutazioni prodotte: **775**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| ATR15_R100 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| ATR20_R100 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| ATR30_R100 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| BE_R050 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| BE_R100 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| GB20_R050 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| GB20_R100 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| GB30_R050 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| GB30_R100 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| GB40_R050 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| GB40_R100 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| GB50_R050 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| GB50_R100 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| TIME_12H | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| TIME_24H | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| TIME_6H | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| TP_R050 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| TP_R100 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| TP_R150 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |
| TP_R200 | 1 | 0,428 | 0,428 | 0,428 | 100,0% | 75,2 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
