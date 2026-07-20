# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T07:08:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **941**
- Valutazioni prodotte: **1495**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 22 | 0,585 | 0,417 | 0,251 | 54,5% | 72,8 | INSUFFICIENT_DATA |
| GB50_R050 | 22 | 0,504 | 0,330 | 0,212 | 54,5% | 72,8 | INSUFFICIENT_DATA |
| GB30_R050 | 22 | 0,547 | 0,388 | 0,272 | 54,5% | 72,8 | INSUFFICIENT_DATA |
| TP_R050 | 22 | 0,551 | 0,436 | 0,233 | 54,5% | 69,0 | INSUFFICIENT_DATA |
| GB40_R050 | 22 | 0,508 | 0,359 | 0,226 | 54,5% | 69,0 | INSUFFICIENT_DATA |
| BE_R050 | 21 | 0,363 | 0,000 | 0,164 | 38,1% | 54,1 | INSUFFICIENT_DATA |
| TP_R100 | 22 | 0,096 | 0,000 | -0,089 | 45,5% | 39,6 | INSUFFICIENT_DATA |
| GB20_R100 | 22 | 0,086 | 0,000 | -0,096 | 45,5% | 34,7 | INSUFFICIENT_DATA |
| GB30_R100 | 22 | 0,065 | 0,000 | -0,106 | 45,5% | 34,2 | INSUFFICIENT_DATA |
| GB40_R100 | 22 | 0,043 | 0,000 | -0,124 | 45,5% | 33,7 | INSUFFICIENT_DATA |
| TP_R200 | 4 | 0,075 | 0,000 | -0,150 | 25,0% | 28,3 | INSUFFICIENT_DATA |
| GB50_R100 | 22 | 0,022 | 0,000 | -0,151 | 45,5% | 26,6 | INSUFFICIENT_DATA |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| TP_R150 | 19 | -0,020 | 0,000 | -0,156 | 36,8% | 16,3 | INSUFFICIENT_DATA |
| ATR15_R100 | 21 | -0,018 | 0,000 | -0,139 | 33,3% | 12,9 | INSUFFICIENT_DATA |
| ATR20_R100 | 21 | -0,018 | 0,000 | -0,144 | 33,3% | 12,9 | INSUFFICIENT_DATA |
| ATR30_R100 | 21 | -0,018 | 0,000 | -0,135 | 33,3% | 12,9 | INSUFFICIENT_DATA |
| BE_R100 | 21 | -0,018 | 0,000 | -0,138 | 33,3% | 12,9 | INSUFFICIENT_DATA |
| TIME_12H | 18 | -0,021 | 0,000 | -0,171 | 38,9% | 12,3 | INSUFFICIENT_DATA |
| TIME_24H | 18 | -0,021 | 0,000 | -0,166 | 38,9% | 12,3 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
