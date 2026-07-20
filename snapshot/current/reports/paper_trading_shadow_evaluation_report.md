# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T09:23:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **1275**
- Valutazioni prodotte: **1732**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 31 | 0,574 | 0,251 | 0,318 | 64,5% | 84,8 | EARLY_SIGNAL |
| GB30_R050 | 31 | 0,528 | 0,182 | 0,303 | 64,5% | 84,8 | EARLY_SIGNAL |
| GB40_R050 | 31 | 0,483 | 0,113 | 0,249 | 64,5% | 84,8 | EARLY_SIGNAL |
| TP_R050 | 31 | 0,499 | 0,198 | 0,266 | 64,5% | 84,8 | EARLY_SIGNAL |
| GB50_R050 | 31 | 0,466 | 0,075 | 0,246 | 64,5% | 84,7 | EARLY_SIGNAL |
| GB20_R100 | 31 | 0,324 | 0,033 | 0,114 | 58,1% | 73,9 | EARLY_SIGNAL |
| GB30_R100 | 31 | 0,277 | 0,033 | 0,086 | 58,1% | 73,8 | EARLY_SIGNAL |
| GB40_R100 | 31 | 0,231 | 0,033 | 0,045 | 58,1% | 73,7 | EARLY_SIGNAL |
| TP_R100 | 31 | 0,273 | 0,033 | 0,072 | 58,1% | 73,5 | EARLY_SIGNAL |
| GB50_R100 | 31 | 0,184 | 0,033 | 0,014 | 58,1% | 69,8 | EARLY_SIGNAL |
| BE_R050 | 30 | 0,266 | 0,000 | 0,108 | 43,3% | 56,1 | EARLY_SIGNAL |
| TP_R150 | 30 | 0,063 | 0,000 | -0,139 | 43,3% | 35,9 | EARLY_SIGNAL |
| ATR15_R100 | 30 | 0,032 | 0,006 | -0,073 | 50,0% | 35,0 | EARLY_SIGNAL |
| BE_R100 | 27 | 0,033 | 0,000 | -0,081 | 44,4% | 31,8 | INSUFFICIENT_DATA |
| ATR30_R100 | 27 | 0,033 | 0,000 | -0,081 | 44,4% | 31,8 | INSUFFICIENT_DATA |
| ATR20_R100 | 27 | 0,033 | 0,000 | -0,101 | 44,4% | 28,9 | INSUFFICIENT_DATA |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| TP_R200 | 4 | 0,075 | 0,000 | -0,150 | 25,0% | 28,3 | INSUFFICIENT_DATA |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| TP_R200 | 26 | -0,105 | 0,000 | -0,257 | 38,5% | 22,7 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
