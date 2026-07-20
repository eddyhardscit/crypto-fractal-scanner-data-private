# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T13:23:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **1751**
- Valutazioni prodotte: **2026**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB50_R050 | 49 | 0,243 | 0,000 | 0,015 | 46,9% | 59,5 | EARLY_SIGNAL |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 51 | 0,117 | 0,000 | -0,043 | 31,4% | 53,1 | VALIDATING |
| GB20_R050 | 55 | 0,199 | 0,000 | -0,027 | 43,6% | 53,0 | VALIDATING |
| GB50_R100 | 49 | 0,053 | 0,000 | -0,074 | 38,8% | 48,0 | EARLY_SIGNAL |
| GB30_R050 | 55 | 0,161 | 0,000 | -0,069 | 41,8% | 46,8 | VALIDATING |
| GB40_R050 | 54 | 0,129 | 0,000 | -0,098 | 42,6% | 42,1 | VALIDATING |
| TP_R050 | 55 | 0,097 | 0,000 | -0,154 | 43,6% | 42,0 | VALIDATING |
| GB20_R100 | 55 | 0,056 | 0,000 | -0,127 | 36,4% | 42,0 | VALIDATING |
| BE_R050 | 48 | 0,069 | 0,000 | -0,136 | 33,3% | 41,2 | EARLY_SIGNAL |
| TIME_12H | 40 | 0,085 | 0,000 | -0,120 | 30,0% | 33,8 | EARLY_SIGNAL |
| TIME_6H | 47 | 0,016 | 0,000 | -0,135 | 42,6% | 31,0 | EARLY_SIGNAL |
| GB30_R100 | 55 | 0,006 | 0,000 | -0,165 | 36,4% | 28,9 | VALIDATING |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| TP_R100 | 55 | -0,003 | 0,000 | -0,184 | 36,4% | 26,7 | VALIDATING |
| GB40_R100 | 54 | -0,037 | 0,000 | -0,207 | 37,0% | 26,6 | VALIDATING |
| TP_R150 | 54 | -0,006 | 0,000 | -0,141 | 27,8% | 26,4 | VALIDATING |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| ATR15_R100 | 44 | 0,000 | 0,000 | -0,076 | 34,1% | 21,3 | EARLY_SIGNAL |
| ATR20_R100 | 41 | -0,009 | 0,000 | -0,106 | 29,3% | 16,9 | EARLY_SIGNAL |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
