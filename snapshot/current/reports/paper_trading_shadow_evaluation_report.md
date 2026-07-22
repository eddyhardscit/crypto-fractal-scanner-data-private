# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T00:53:40+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **6131**
- Valutazioni prodotte: **3101**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 274 | 0,219 | 0,043 | 0,121 | 50,7% | 84,5 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB30_R050 | 274 | 0,180 | 0,000 | 0,088 | 48,5% | 73,8 | VALIDATING |
| TP_R050 | 274 | 0,140 | 0,000 | 0,037 | 47,4% | 73,8 | VALIDATING |
| TP_R200 | 223 | 0,129 | 0,000 | 0,045 | 37,7% | 72,5 | VALIDATING |
| GB40_R050 | 274 | 0,141 | 0,000 | 0,048 | 48,2% | 70,0 | VALIDATING |
| GB50_R050 | 274 | 0,099 | 0,000 | 0,016 | 47,1% | 69,7 | VALIDATING |
| GB20_R100 | 261 | 0,085 | 0,000 | 0,012 | 40,6% | 69,3 | VALIDATING |
| GB30_R100 | 259 | 0,054 | 0,000 | -0,016 | 37,1% | 67,2 | VALIDATING |
| TIME_12H | 246 | 0,050 | 0,000 | -0,018 | 38,2% | 66,2 | VALIDATING |
| TP_R100 | 261 | 0,055 | 0,000 | -0,016 | 37,5% | 63,4 | VALIDATING |
| TP_R150 | 239 | 0,043 | 0,000 | -0,030 | 31,8% | 59,7 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R100 | 256 | 0,021 | 0,000 | -0,040 | 35,2% | 51,5 | VALIDATING |
| GB40_R100 | 259 | 0,021 | 0,000 | -0,049 | 39,0% | 49,9 | VALIDATING |
| TIME_6H | 272 | -0,029 | 0,000 | -0,115 | 48,2% | 35,5 | VALIDATING |
| BE_R050 | 233 | -0,020 | 0,000 | -0,124 | 33,5% | 35,4 | VALIDATING |
| ATR30_R100 | 213 | -0,194 | 0,000 | -0,285 | 25,4% | 33,7 | UNDERPERFORMING |
| BE_R100 | 202 | -0,140 | 0,000 | -0,236 | 26,7% | 33,6 | UNDERPERFORMING |
| ATR15_R100 | 259 | -0,074 | 0,000 | -0,125 | 27,4% | 31,5 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
