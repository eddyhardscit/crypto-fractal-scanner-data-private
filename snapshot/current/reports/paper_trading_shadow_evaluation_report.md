# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T20:38:44+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **13123**
- Valutazioni prodotte: **4006**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| ATR20_R100 | 27 | 0,283 | 0,408 | 0,147 | 88,9% | 84,3 | INSUFFICIENT_DATA |
| GB20_R050 | 28 | 0,659 | 0,477 | 0,443 | 96,4% | 83,9 | INSUFFICIENT_DATA |
| GB30_R100 | 27 | 0,664 | 0,477 | 0,489 | 100,0% | 83,8 | INSUFFICIENT_DATA |
| GB40_R100 | 27 | 0,588 | 0,477 | 0,429 | 92,6% | 83,8 | INSUFFICIENT_DATA |
| GB40_R050 | 27 | 0,543 | 0,477 | 0,336 | 88,9% | 83,8 | INSUFFICIENT_DATA |
| GB30_R050 | 27 | 0,611 | 0,477 | 0,396 | 96,3% | 83,8 | INSUFFICIENT_DATA |
| ATR15_R100 | 27 | 0,349 | 0,408 | 0,243 | 88,9% | 83,8 | INSUFFICIENT_DATA |
| GB20_R100 | 27 | 0,729 | 0,477 | 0,543 | 100,0% | 83,7 | INSUFFICIENT_DATA |
| TP_R100 | 27 | 0,540 | 0,477 | 0,332 | 88,9% | 83,7 | INSUFFICIENT_DATA |
| GB50_R100 | 27 | 0,598 | 0,477 | 0,424 | 92,6% | 83,3 | INSUFFICIENT_DATA |
| GB50_R050 | 27 | 0,560 | 0,477 | 0,349 | 92,6% | 83,3 | INSUFFICIENT_DATA |
| TP_R200 | 27 | 0,283 | 0,330 | 0,075 | 77,8% | 82,3 | INSUFFICIENT_DATA |
| ATR30_R100 | 26 | 0,220 | 0,365 | 0,021 | 84,6% | 80,2 | INSUFFICIENT_DATA |
| TP_R150 | 27 | 0,190 | 0,287 | 0,002 | 66,7% | 80,2 | INSUFFICIENT_DATA |
| BE_R050 | 25 | 0,265 | 0,365 | 0,087 | 88,0% | 80,0 | INSUFFICIENT_DATA |
| BE_R100 | 25 | 0,265 | 0,365 | 0,076 | 88,0% | 80,0 | INSUFFICIENT_DATA |
| TP_R050 | 28 | 0,327 | 0,369 | 0,106 | 89,3% | 79,1 | INSUFFICIENT_DATA |
| TIME_6H | 582 | 0,054 | 0,039 | -0,024 | 52,9% | 79,0 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TIME_12H | 555 | 0,094 | 0,000 | 0,020 | 45,6% | 72,7 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
