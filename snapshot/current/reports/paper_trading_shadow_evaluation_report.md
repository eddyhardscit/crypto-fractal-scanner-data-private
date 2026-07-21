# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T13:38:40+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **3528**
- Valutazioni prodotte: **2672**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 140 | 0,308 | 0,068 | 0,169 | 53,6% | 83,7 | VALIDATING |
| TP_R050 | 140 | 0,227 | 0,075 | 0,092 | 53,6% | 83,6 | VALIDATING |
| GB30_R050 | 140 | 0,280 | 0,068 | 0,146 | 52,9% | 83,0 | VALIDATING |
| GB40_R050 | 140 | 0,237 | 0,068 | 0,094 | 52,9% | 82,9 | VALIDATING |
| GB50_R050 | 140 | 0,192 | 0,060 | 0,067 | 52,9% | 82,3 | VALIDATING |
| TIME_6H | 136 | 0,055 | 0,036 | -0,049 | 58,8% | 81,2 | VALIDATING |
| GB20_R100 | 138 | 0,216 | 0,033 | 0,104 | 50,7% | 80,2 | VALIDATING |
| GB50_R100 | 126 | 0,161 | 0,033 | 0,066 | 50,8% | 80,0 | VALIDATING |
| GB40_R100 | 138 | 0,141 | 0,017 | 0,037 | 50,0% | 75,0 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 125 | 0,138 | 0,000 | 0,032 | 43,2% | 73,0 | VALIDATING |
| GB30_R100 | 138 | 0,182 | 0,000 | 0,073 | 49,3% | 69,5 | VALIDATING |
| TP_R100 | 138 | 0,196 | 0,000 | 0,092 | 49,3% | 69,5 | VALIDATING |
| TIME_12H | 128 | 0,141 | 0,000 | 0,043 | 49,2% | 68,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 126 | 0,034 | 0,000 | -0,058 | 38,9% | 57,0 | VALIDATING |
| ATR15_R100 | 122 | 0,020 | 0,000 | -0,064 | 42,6% | 51,2 | VALIDATING |
| ATR20_R100 | 122 | -0,015 | 0,000 | -0,122 | 41,8% | 39,3 | VALIDATING |
| TIME_24H | 112 | -0,081 | 0,000 | -0,286 | 39,3% | 34,2 | VALIDATING |
| ATR30_R100 | 121 | -0,138 | 0,000 | -0,289 | 39,7% | 33,6 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
