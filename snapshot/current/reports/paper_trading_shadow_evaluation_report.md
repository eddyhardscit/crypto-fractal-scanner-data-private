# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T11:08:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **8471**
- Valutazioni prodotte: **3241**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 371 | 0,173 | 0,039 | 0,102 | 52,3% | 85,0 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 382 | 0,131 | 0,000 | 0,051 | 46,1% | 73,9 | VALIDATING |
| GB40_R050 | 382 | 0,128 | 0,000 | 0,051 | 46,6% | 73,8 | VALIDATING |
| GB20_R050 | 382 | 0,205 | 0,000 | 0,123 | 48,4% | 73,8 | VALIDATING |
| GB30_R050 | 382 | 0,166 | 0,000 | 0,091 | 46,9% | 73,8 | VALIDATING |
| GB50_R050 | 382 | 0,087 | 0,000 | 0,011 | 45,8% | 73,6 | VALIDATING |
| TP_R200 | 339 | 0,113 | 0,000 | 0,045 | 35,7% | 72,8 | VALIDATING |
| TIME_6H | 372 | 0,030 | 0,043 | -0,057 | 54,8% | 70,8 | VALIDATING |
| GB20_R100 | 373 | 0,067 | 0,000 | 0,009 | 36,5% | 65,8 | VALIDATING |
| GB30_R100 | 373 | 0,053 | 0,000 | -0,005 | 35,9% | 65,1 | VALIDATING |
| GB40_R100 | 373 | 0,041 | 0,000 | -0,013 | 35,9% | 62,5 | VALIDATING |
| TP_R100 | 373 | 0,038 | 0,000 | -0,020 | 34,3% | 60,5 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 357 | 0,017 | 0,000 | -0,041 | 27,7% | 53,5 | VALIDATING |
| GB50_R100 | 349 | 0,006 | 0,000 | -0,041 | 31,8% | 50,2 | VALIDATING |
| ATR15_R100 | 357 | -0,045 | 0,000 | -0,091 | 25,8% | 32,5 | VALIDATING |
| BE_R050 | 345 | -0,068 | 0,000 | -0,156 | 32,2% | 32,0 | VALIDATING |
| ATR20_R100 | 339 | -0,136 | 0,000 | -0,189 | 21,5% | 31,4 | UNDERPERFORMING |
| BE_R100 | 306 | -0,200 | 0,000 | -0,281 | 22,2% | 30,7 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
