# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T02:23:43+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **10559**
- Valutazioni prodotte: **3287**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 478 | 0,196 | 0,000 | 0,123 | 48,1% | 73,8 | VALIDATING |
| TP_R050 | 478 | 0,122 | 0,000 | 0,050 | 46,4% | 73,8 | VALIDATING |
| GB30_R050 | 478 | 0,162 | 0,000 | 0,093 | 46,9% | 73,8 | VALIDATING |
| TIME_6H | 477 | 0,034 | 0,043 | -0,043 | 54,1% | 73,7 | VALIDATING |
| GB40_R050 | 478 | 0,123 | 0,000 | 0,054 | 46,4% | 73,7 | VALIDATING |
| GB20_R100 | 471 | 0,111 | 0,000 | 0,060 | 37,6% | 73,6 | VALIDATING |
| GB30_R100 | 471 | 0,086 | 0,000 | 0,034 | 37,2% | 73,5 | VALIDATING |
| TP_R150 | 445 | 0,051 | 0,000 | -0,008 | 27,6% | 72,0 | VALIDATING |
| TP_R100 | 471 | 0,080 | 0,000 | 0,025 | 35,9% | 69,8 | VALIDATING |
| GB50_R050 | 478 | 0,080 | 0,000 | 0,014 | 45,8% | 69,8 | VALIDATING |
| GB40_R100 | 471 | 0,063 | 0,000 | 0,016 | 37,2% | 69,6 | VALIDATING |
| GB50_R100 | 471 | 0,045 | 0,000 | 0,001 | 34,8% | 69,4 | VALIDATING |
| TIME_12H | 474 | 0,040 | 0,000 | -0,027 | 44,3% | 59,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 419 | -0,023 | 0,000 | -0,096 | 30,5% | 39,7 | VALIDATING |
| TIME_24H | 450 | -0,068 | 0,000 | -0,167 | 28,9% | 34,7 | VALIDATING |
| BE_R050 | 435 | -0,083 | 0,000 | -0,157 | 29,4% | 32,1 | UNDERPERFORMING |
| ATR15_R100 | 471 | -0,056 | 0,000 | -0,103 | 28,2% | 31,1 | UNDERPERFORMING |
| ATR30_R100 | 450 | -0,114 | 0,000 | -0,185 | 23,3% | 31,0 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
