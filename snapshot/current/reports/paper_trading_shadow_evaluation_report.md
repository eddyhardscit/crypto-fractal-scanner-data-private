# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T04:08:40+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **6450**
- Valutazioni prodotte: **3139**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 290 | 0,218 | 0,050 | 0,118 | 51,7% | 81,7 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 231 | 0,141 | 0,000 | 0,060 | 39,8% | 72,6 | VALIDATING |
| GB30_R050 | 290 | 0,177 | 0,000 | 0,090 | 49,7% | 69,9 | VALIDATING |
| TP_R050 | 290 | 0,129 | 0,000 | 0,026 | 48,6% | 69,9 | VALIDATING |
| GB40_R050 | 290 | 0,137 | 0,000 | 0,049 | 49,3% | 69,8 | VALIDATING |
| GB50_R050 | 290 | 0,093 | 0,000 | 0,010 | 48,3% | 69,7 | VALIDATING |
| GB20_R100 | 275 | 0,102 | 0,000 | 0,032 | 42,9% | 69,5 | VALIDATING |
| GB30_R100 | 275 | 0,068 | 0,000 | 0,001 | 40,0% | 65,7 | VALIDATING |
| TP_R150 | 249 | 0,050 | 0,000 | -0,019 | 32,9% | 62,1 | VALIDATING |
| TP_R100 | 277 | 0,068 | 0,000 | -0,006 | 39,7% | 61,0 | VALIDATING |
| TIME_12H | 270 | 0,036 | 0,000 | -0,035 | 40,7% | 60,6 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R100 | 272 | 0,027 | 0,000 | -0,031 | 37,1% | 54,8 | VALIDATING |
| GB40_R100 | 275 | 0,032 | 0,000 | -0,034 | 40,7% | 52,4 | VALIDATING |
| TIME_6H | 286 | -0,055 | 0,000 | -0,140 | 48,3% | 35,6 | VALIDATING |
| BE_R050 | 250 | -0,050 | 0,000 | -0,148 | 33,6% | 35,5 | VALIDATING |
| BE_R100 | 217 | -0,152 | 0,000 | -0,248 | 27,6% | 33,9 | UNDERPERFORMING |
| ATR20_R100 | 265 | -0,155 | 0,000 | -0,222 | 24,5% | 31,7 | UNDERPERFORMING |
| ATR15_R100 | 274 | -0,075 | 0,000 | -0,124 | 28,1% | 31,2 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
