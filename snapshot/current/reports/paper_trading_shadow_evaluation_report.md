# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T16:23:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **2106**
- Valutazioni prodotte: **2094**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 70 | 0,167 | 0,000 | -0,015 | 35,7% | 61,7 | VALIDATING |
| GB30_R050 | 69 | 0,148 | 0,000 | -0,031 | 34,8% | 59,1 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R050 | 69 | 0,136 | 0,000 | -0,035 | 34,8% | 58,4 | VALIDATING |
| GB40_R050 | 69 | 0,115 | 0,000 | -0,059 | 34,8% | 54,8 | VALIDATING |
| TP_R200 | 68 | 0,093 | 0,000 | -0,055 | 26,5% | 51,3 | VALIDATING |
| BE_R050 | 63 | 0,045 | 0,000 | -0,124 | 27,0% | 48,0 | VALIDATING |
| GB20_R100 | 70 | 0,041 | 0,000 | -0,085 | 28,6% | 45,8 | VALIDATING |
| TP_R050 | 70 | 0,083 | 0,000 | -0,123 | 35,7% | 45,1 | VALIDATING |
| TIME_12H | 60 | 0,101 | 0,000 | -0,084 | 25,0% | 45,0 | VALIDATING |
| TIME_6H | 69 | 0,020 | 0,000 | -0,081 | 39,1% | 38,5 | VALIDATING |
| GB30_R100 | 69 | 0,005 | 0,000 | -0,121 | 29,0% | 31,3 | VALIDATING |
| TP_R100 | 70 | -0,010 | 0,000 | -0,146 | 28,6% | 29,7 | VALIDATING |
| GB40_R100 | 69 | -0,035 | 0,000 | -0,159 | 29,0% | 29,6 | VALIDATING |
| GB50_R100 | 69 | -0,018 | 0,000 | -0,129 | 27,5% | 29,4 | VALIDATING |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| TP_R150 | 70 | -0,024 | 0,000 | -0,139 | 21,4% | 25,9 | VALIDATING |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| ATR15_R100 | 60 | -0,034 | 0,000 | -0,106 | 25,0% | 20,8 | VALIDATING |
| ATR20_R100 | 57 | -0,055 | 0,000 | -0,154 | 21,1% | 20,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
