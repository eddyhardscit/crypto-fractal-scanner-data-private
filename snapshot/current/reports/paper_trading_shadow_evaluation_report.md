# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T12:08:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **8563**
- Valutazioni prodotte: **3261**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 376 | 0,172 | 0,041 | 0,105 | 52,7% | 85,4 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 386 | 0,205 | 0,000 | 0,122 | 49,0% | 73,8 | VALIDATING |
| TP_R050 | 386 | 0,131 | 0,000 | 0,050 | 46,6% | 73,8 | VALIDATING |
| GB30_R050 | 386 | 0,166 | 0,000 | 0,089 | 47,4% | 73,8 | VALIDATING |
| GB40_R050 | 386 | 0,129 | 0,000 | 0,051 | 47,2% | 73,7 | VALIDATING |
| GB50_R050 | 386 | 0,088 | 0,000 | 0,013 | 46,4% | 73,5 | VALIDATING |
| TIME_6H | 376 | 0,031 | 0,043 | -0,050 | 55,3% | 72,9 | VALIDATING |
| TP_R200 | 343 | 0,113 | 0,000 | 0,044 | 36,4% | 72,8 | VALIDATING |
| GB20_R100 | 377 | 0,068 | 0,000 | 0,009 | 37,1% | 65,6 | VALIDATING |
| GB30_R100 | 377 | 0,054 | 0,000 | -0,002 | 36,6% | 65,6 | VALIDATING |
| GB40_R100 | 377 | 0,043 | 0,000 | -0,013 | 36,6% | 63,0 | VALIDATING |
| TP_R100 | 377 | 0,040 | 0,000 | -0,018 | 35,0% | 61,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 361 | 0,019 | 0,000 | -0,040 | 28,5% | 54,2 | VALIDATING |
| GB50_R100 | 353 | 0,008 | 0,000 | -0,040 | 32,6% | 51,0 | VALIDATING |
| TIME_24H | 329 | -0,103 | 0,000 | -0,196 | 29,5% | 33,6 | UNDERPERFORMING |
| ATR15_R100 | 372 | -0,038 | 0,000 | -0,087 | 27,7% | 33,3 | VALIDATING |
| BE_R050 | 349 | -0,065 | 0,000 | -0,150 | 33,0% | 32,0 | VALIDATING |
| ATR20_R100 | 343 | -0,132 | 0,000 | -0,185 | 22,4% | 31,5 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
