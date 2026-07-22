# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T23:53:40+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **6047**
- Valutazioni prodotte: **3085**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 269 | 0,221 | 0,043 | 0,121 | 50,6% | 84,3 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB30_R050 | 269 | 0,182 | 0,000 | 0,087 | 48,3% | 73,8 | VALIDATING |
| TP_R050 | 269 | 0,141 | 0,000 | 0,038 | 47,2% | 73,8 | VALIDATING |
| GB40_R050 | 269 | 0,143 | 0,000 | 0,045 | 48,0% | 73,7 | VALIDATING |
| TP_R200 | 221 | 0,128 | 0,000 | 0,046 | 37,1% | 72,4 | VALIDATING |
| GB50_R050 | 269 | 0,101 | 0,000 | 0,015 | 46,8% | 69,6 | VALIDATING |
| GB20_R100 | 257 | 0,084 | 0,000 | 0,013 | 39,7% | 69,3 | VALIDATING |
| GB30_R100 | 257 | 0,053 | 0,000 | -0,016 | 36,6% | 67,2 | VALIDATING |
| TIME_12H | 242 | 0,054 | 0,000 | -0,014 | 38,0% | 66,7 | VALIDATING |
| TP_R100 | 257 | 0,053 | 0,000 | -0,020 | 36,6% | 62,7 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 237 | 0,041 | 0,000 | -0,036 | 31,2% | 58,1 | VALIDATING |
| GB50_R100 | 254 | 0,019 | 0,000 | -0,041 | 34,6% | 50,9 | VALIDATING |
| GB40_R100 | 257 | 0,019 | 0,000 | -0,056 | 38,5% | 48,8 | VALIDATING |
| BE_R050 | 231 | -0,022 | 0,000 | -0,126 | 32,9% | 39,1 | VALIDATING |
| TIME_6H | 262 | -0,019 | 0,000 | -0,104 | 48,9% | 35,5 | VALIDATING |
| ATR20_R100 | 235 | -0,135 | 0,000 | -0,204 | 24,3% | 35,2 | UNDERPERFORMING |
| ATR30_R100 | 211 | -0,198 | 0,000 | -0,287 | 24,6% | 34,3 | UNDERPERFORMING |
| BE_R100 | 200 | -0,143 | 0,000 | -0,237 | 26,0% | 34,2 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
