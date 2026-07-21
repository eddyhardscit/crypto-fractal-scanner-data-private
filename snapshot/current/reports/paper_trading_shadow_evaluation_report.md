# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T03:38:37+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **2371**
- Valutazioni prodotte: **2152**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R100 | 80 | 0,145 | 0,000 | 0,020 | 36,2% | 65,8 | VALIDATING |
| GB20_R050 | 82 | 0,243 | 0,000 | 0,087 | 43,9% | 62,9 | VALIDATING |
| GB30_R050 | 82 | 0,209 | 0,000 | 0,048 | 42,7% | 62,9 | VALIDATING |
| GB40_R050 | 82 | 0,168 | 0,000 | 0,021 | 42,7% | 62,8 | VALIDATING |
| GB50_R050 | 82 | 0,173 | 0,000 | 0,017 | 42,7% | 62,8 | VALIDATING |
| TP_R100 | 80 | 0,112 | 0,000 | -0,024 | 36,2% | 62,2 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB30_R100 | 78 | 0,077 | 0,000 | -0,050 | 34,6% | 57,6 | VALIDATING |
| TP_R050 | 82 | 0,150 | 0,000 | -0,038 | 43,9% | 57,2 | VALIDATING |
| TIME_12H | 80 | 0,108 | 0,000 | -0,028 | 37,5% | 56,4 | VALIDATING |
| TP_R200 | 70 | 0,097 | 0,000 | -0,035 | 27,1% | 54,7 | VALIDATING |
| GB50_R100 | 78 | 0,033 | 0,000 | -0,068 | 33,3% | 50,8 | VALIDATING |
| TIME_6H | 82 | 0,032 | 0,000 | -0,054 | 46,3% | 49,7 | VALIDATING |
| BE_R050 | 75 | 0,050 | 0,000 | -0,094 | 33,3% | 46,9 | VALIDATING |
| GB40_R100 | 78 | 0,030 | 0,000 | -0,094 | 34,6% | 46,0 | VALIDATING |
| TIME_24H | 61 | 0,015 | 0,000 | -0,141 | 23,0% | 28,8 | VALIDATING |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| ATR20_R100 | 64 | -0,036 | 0,000 | -0,119 | 28,1% | 26,7 | VALIDATING |
| ATR30_R100 | 63 | -0,026 | 0,000 | -0,116 | 28,6% | 26,5 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
