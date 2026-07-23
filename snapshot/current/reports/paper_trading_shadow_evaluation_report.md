# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T13:38:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **11085**
- Valutazioni prodotte: **3294**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 500 | 0,064 | 0,060 | -0,011 | 55,2% | 83,3 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 502 | 0,146 | 0,000 | 0,075 | 47,2% | 73,9 | VALIDATING |
| GB40_R050 | 502 | 0,144 | 0,000 | 0,078 | 46,8% | 73,8 | VALIDATING |
| GB20_R050 | 502 | 0,218 | 0,000 | 0,149 | 48,6% | 73,8 | VALIDATING |
| GB30_R050 | 502 | 0,183 | 0,000 | 0,115 | 47,4% | 73,8 | VALIDATING |
| TP_R100 | 493 | 0,088 | 0,000 | 0,038 | 35,3% | 73,5 | VALIDATING |
| GB20_R100 | 492 | 0,115 | 0,000 | 0,064 | 36,8% | 73,4 | VALIDATING |
| GB30_R100 | 492 | 0,090 | 0,000 | 0,039 | 36,4% | 73,4 | VALIDATING |
| GB40_R100 | 492 | 0,068 | 0,000 | 0,017 | 36,4% | 73,3 | VALIDATING |
| GB50_R100 | 491 | 0,052 | 0,000 | 0,008 | 34,2% | 73,2 | VALIDATING |
| GB50_R050 | 501 | 0,104 | 0,000 | 0,042 | 46,1% | 69,9 | VALIDATING |
| TIME_12H | 500 | 0,062 | 0,000 | -0,006 | 45,4% | 68,0 | VALIDATING |
| TP_R150 | 478 | 0,036 | 0,000 | -0,019 | 26,6% | 60,0 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 454 | -0,056 | 0,000 | -0,126 | 28,6% | 35,4 | VALIDATING |
| ATR15_R100 | 491 | -0,048 | 0,000 | -0,091 | 27,7% | 32,6 | UNDERPERFORMING |
| BE_R050 | 465 | -0,075 | 0,000 | -0,151 | 29,7% | 32,2 | UNDERPERFORMING |
| TIME_24H | 493 | -0,053 | 0,000 | -0,144 | 29,6% | 31,0 | VALIDATING |
| ATR20_R100 | 482 | -0,081 | 0,000 | -0,129 | 23,7% | 30,8 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
