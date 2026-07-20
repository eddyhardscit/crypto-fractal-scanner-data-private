# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T05:10:21+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **695**
- Valutazioni prodotte: **1190**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 13 | 0,949 | 0,683 | 0,601 | 84,6% | 81,3 | INSUFFICIENT_DATA |
| GB50_R050 | 13 | 0,826 | 0,606 | 0,524 | 84,6% | 81,3 | INSUFFICIENT_DATA |
| GB30_R050 | 13 | 0,894 | 0,597 | 0,578 | 84,6% | 81,3 | INSUFFICIENT_DATA |
| TP_R050 | 13 | 0,894 | 0,500 | 0,577 | 84,6% | 81,3 | INSUFFICIENT_DATA |
| GB40_R050 | 13 | 0,839 | 0,512 | 0,514 | 84,6% | 81,2 | INSUFFICIENT_DATA |
| GB50_R100 | 12 | 0,205 | 0,044 | 0,068 | 83,3% | 79,9 | INSUFFICIENT_DATA |
| GB40_R100 | 12 | 0,235 | 0,044 | 0,086 | 83,3% | 79,8 | INSUFFICIENT_DATA |
| GB30_R100 | 12 | 0,265 | 0,044 | 0,094 | 83,3% | 79,7 | INSUFFICIENT_DATA |
| TP_R100 | 12 | 0,306 | 0,044 | 0,098 | 83,3% | 79,7 | INSUFFICIENT_DATA |
| GB20_R100 | 12 | 0,295 | 0,044 | 0,099 | 83,3% | 79,7 | INSUFFICIENT_DATA |
| TIME_12H | 9 | 0,074 | 0,033 | 0,021 | 77,8% | 76,8 | INSUFFICIENT_DATA |
| TIME_24H | 9 | 0,074 | 0,033 | 0,019 | 77,8% | 76,8 | INSUFFICIENT_DATA |
| TIME_6H | 9 | 0,074 | 0,033 | 0,021 | 77,8% | 76,8 | INSUFFICIENT_DATA |
| TP_R150 | 9 | 0,074 | 0,033 | 0,021 | 77,8% | 76,8 | INSUFFICIENT_DATA |
| TP_R200 | 9 | 0,074 | 0,033 | 0,021 | 77,8% | 76,8 | INSUFFICIENT_DATA |
| ATR15_R100 | 12 | 0,056 | 0,033 | 0,013 | 58,3% | 67,0 | INSUFFICIENT_DATA |
| ATR20_R100 | 12 | 0,056 | 0,033 | 0,013 | 58,3% | 67,0 | INSUFFICIENT_DATA |
| ATR30_R100 | 12 | 0,056 | 0,033 | 0,013 | 58,3% | 67,0 | INSUFFICIENT_DATA |
| BE_R100 | 12 | 0,056 | 0,033 | 0,013 | 58,3% | 67,0 | INSUFFICIENT_DATA |
| BE_R050 | 13 | 0,509 | 0,428 | 0,238 | 53,8% | 66,1 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
