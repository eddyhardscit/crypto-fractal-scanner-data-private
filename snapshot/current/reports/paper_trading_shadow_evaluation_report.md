# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T22:38:43+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **13203**
- Valutazioni prodotte: **4037**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB30_R100 | 33 | 0,537 | 0,335 | 0,363 | 97,0% | 85,0 | EARLY_SIGNAL |
| ATR20_R100 | 27 | 0,283 | 0,408 | 0,147 | 88,9% | 84,3 | INSUFFICIENT_DATA |
| ATR15_R100 | 27 | 0,349 | 0,408 | 0,243 | 88,9% | 83,8 | INSUFFICIENT_DATA |
| GB50_R050 | 29 | 0,517 | 0,468 | 0,304 | 86,2% | 83,7 | INSUFFICIENT_DATA |
| GB50_R100 | 28 | 0,572 | 0,472 | 0,405 | 89,3% | 83,5 | INSUFFICIENT_DATA |
| TP_R200 | 31 | 0,288 | 0,408 | 0,096 | 77,4% | 83,4 | EARLY_SIGNAL |
| GB40_R100 | 33 | 0,446 | 0,330 | 0,270 | 78,8% | 81,2 | EARLY_SIGNAL |
| GB30_R050 | 33 | 0,374 | 0,330 | 0,101 | 84,8% | 81,2 | EARLY_SIGNAL |
| GB40_R050 | 33 | 0,302 | 0,330 | 0,038 | 75,8% | 81,2 | EARLY_SIGNAL |
| GB20_R100 | 33 | 0,513 | 0,408 | 0,285 | 87,9% | 81,2 | EARLY_SIGNAL |
| TP_R100 | 33 | 0,384 | 0,408 | 0,164 | 78,8% | 81,2 | EARLY_SIGNAL |
| GB20_R050 | 33 | 0,442 | 0,408 | 0,166 | 84,8% | 81,2 | EARLY_SIGNAL |
| TIME_6H | 586 | 0,056 | 0,039 | -0,021 | 52,9% | 79,6 | VALIDATING |
| BE_R050 | 26 | 0,197 | 0,365 | -0,035 | 84,6% | 75,0 | INSUFFICIENT_DATA |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| ATR30_R100 | 27 | 0,169 | 0,365 | -0,045 | 81,5% | 73,7 | INSUFFICIENT_DATA |
| TP_R150 | 31 | 0,143 | 0,287 | -0,020 | 58,1% | 73,4 | EARLY_SIGNAL |
| TIME_12H | 557 | 0,097 | 0,000 | 0,023 | 45,8% | 72,8 | VALIDATING |
| BE_R100 | 26 | 0,197 | 0,365 | -0,055 | 84,6% | 71,9 | INSUFFICIENT_DATA |
| GB30_R050 | 583 | 0,088 | 0,000 | 0,018 | 43,9% | 70,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
