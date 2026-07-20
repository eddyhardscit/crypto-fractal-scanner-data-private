# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T04:08:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **628**
- Valutazioni prodotte: **1114**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R050 | 9 | 1,125 | 1,535 | 0,707 | 88,9% | 80,3 | INSUFFICIENT_DATA |
| GB20_R050 | 9 | 1,147 | 1,560 | 0,713 | 88,9% | 80,2 | INSUFFICIENT_DATA |
| GB30_R050 | 9 | 1,096 | 1,494 | 0,686 | 88,9% | 80,2 | INSUFFICIENT_DATA |
| GB40_R050 | 9 | 1,044 | 1,429 | 0,653 | 88,9% | 80,2 | INSUFFICIENT_DATA |
| GB50_R050 | 9 | 0,993 | 1,363 | 0,611 | 88,9% | 80,2 | INSUFFICIENT_DATA |
| BE_R050 | 9 | 0,735 | 1,034 | 0,428 | 77,8% | 80,2 | INSUFFICIENT_DATA |
| ATR15_R100 | 8 | 0,084 | 0,033 | 0,025 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| ATR20_R100 | 8 | 0,084 | 0,033 | 0,025 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| ATR30_R100 | 8 | 0,084 | 0,033 | 0,026 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| BE_R100 | 8 | 0,084 | 0,033 | 0,026 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| GB20_R100 | 8 | 0,084 | 0,033 | 0,025 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| GB30_R100 | 8 | 0,084 | 0,033 | 0,026 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| GB40_R100 | 8 | 0,084 | 0,033 | 0,026 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| GB50_R100 | 8 | 0,084 | 0,033 | 0,025 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| TIME_12H | 8 | 0,084 | 0,033 | 0,025 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| TIME_24H | 8 | 0,084 | 0,033 | 0,026 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| TIME_6H | 8 | 0,084 | 0,033 | 0,026 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| TP_R100 | 8 | 0,084 | 0,033 | 0,026 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| TP_R150 | 8 | 0,084 | 0,033 | 0,025 | 87,5% | 76,6 | INSUFFICIENT_DATA |
| TP_R200 | 8 | 0,084 | 0,033 | 0,025 | 87,5% | 76,6 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
