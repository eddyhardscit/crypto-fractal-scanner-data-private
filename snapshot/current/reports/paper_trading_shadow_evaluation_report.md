# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T01:38:37+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **2335**
- Valutazioni prodotte: **2147**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R100 | 77 | 0,126 | 0,000 | -0,007 | 35,1% | 64,0 | VALIDATING |
| GB20_R050 | 81 | 0,246 | 0,000 | 0,089 | 44,4% | 62,7 | VALIDATING |
| GB30_R050 | 81 | 0,212 | 0,000 | 0,052 | 43,2% | 62,7 | VALIDATING |
| GB40_R050 | 81 | 0,170 | 0,000 | 0,004 | 43,2% | 62,6 | VALIDATING |
| GB50_R050 | 81 | 0,175 | 0,000 | 0,021 | 43,2% | 62,6 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 77 | 0,090 | 0,000 | -0,045 | 35,1% | 58,2 | VALIDATING |
| GB30_R100 | 77 | 0,078 | 0,000 | -0,050 | 35,1% | 57,5 | VALIDATING |
| TP_R050 | 81 | 0,152 | 0,000 | -0,036 | 44,4% | 57,3 | VALIDATING |
| TIME_12H | 77 | 0,110 | 0,000 | -0,034 | 37,7% | 54,9 | VALIDATING |
| TP_R200 | 69 | 0,099 | 0,000 | -0,037 | 27,5% | 54,1 | VALIDATING |
| GB50_R100 | 77 | 0,033 | 0,000 | -0,066 | 33,8% | 51,0 | VALIDATING |
| TIME_6H | 81 | 0,032 | 0,000 | -0,059 | 46,9% | 48,8 | VALIDATING |
| BE_R050 | 74 | 0,051 | 0,000 | -0,091 | 33,8% | 47,1 | VALIDATING |
| GB40_R100 | 77 | 0,030 | 0,000 | -0,093 | 35,1% | 46,1 | VALIDATING |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| TIME_24H | 55 | 0,017 | 0,000 | -0,121 | 21,8% | 27,6 | VALIDATING |
| ATR20_R100 | 63 | -0,037 | 0,000 | -0,126 | 28,6% | 26,5 | VALIDATING |
| ATR30_R100 | 62 | -0,027 | 0,000 | -0,120 | 29,0% | 26,3 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
