# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T06:08:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **7404**
- Valutazioni prodotte: **3158**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 333 | 0,229 | 0,000 | 0,141 | 49,2% | 73,8 | VALIDATING |
| TP_R200 | 296 | 0,123 | 0,000 | 0,040 | 36,5% | 72,9 | VALIDATING |
| TP_R050 | 333 | 0,150 | 0,000 | 0,058 | 46,5% | 70,1 | VALIDATING |
| GB30_R050 | 333 | 0,190 | 0,000 | 0,103 | 47,4% | 70,1 | VALIDATING |
| GB40_R050 | 333 | 0,151 | 0,000 | 0,066 | 47,1% | 70,1 | VALIDATING |
| GB50_R050 | 333 | 0,108 | 0,000 | 0,027 | 46,2% | 69,8 | VALIDATING |
| GB30_R100 | 324 | 0,064 | 0,000 | 0,002 | 36,1% | 69,6 | VALIDATING |
| TP_R100 | 329 | 0,065 | 0,000 | -0,000 | 35,9% | 69,6 | VALIDATING |
| GB20_R100 | 328 | 0,094 | 0,000 | 0,031 | 38,1% | 69,4 | VALIDATING |
| TIME_12H | 312 | 0,079 | 0,000 | 0,011 | 46,5% | 69,2 | VALIDATING |
| TIME_6H | 333 | 0,018 | 0,033 | -0,068 | 52,6% | 63,1 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 313 | 0,026 | 0,000 | -0,043 | 28,8% | 52,5 | VALIDATING |
| GB40_R100 | 316 | 0,013 | 0,000 | -0,049 | 35,4% | 51,4 | VALIDATING |
| GB50_R100 | 313 | 0,012 | 0,000 | -0,040 | 32,6% | 48,3 | VALIDATING |
| BE_R050 | 301 | -0,071 | 0,000 | -0,166 | 32,6% | 35,7 | VALIDATING |
| ATR20_R100 | 303 | -0,141 | 0,000 | -0,196 | 21,5% | 31,7 | UNDERPERFORMING |
| ATR15_R100 | 310 | -0,070 | 0,000 | -0,114 | 24,8% | 31,2 | UNDERPERFORMING |
| BE_R100 | 268 | -0,205 | 0,000 | -0,295 | 22,4% | 30,3 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
