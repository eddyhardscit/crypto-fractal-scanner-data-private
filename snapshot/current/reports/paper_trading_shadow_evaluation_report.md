# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T14:38:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **11365**
- Valutazioni prodotte: **3294**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 519 | 0,063 | 0,043 | -0,005 | 53,8% | 82,8 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB40_R050 | 521 | 0,114 | 0,000 | 0,047 | 45,3% | 73,8 | VALIDATING |
| TP_R050 | 521 | 0,117 | 0,000 | 0,048 | 45,7% | 73,8 | VALIDATING |
| GB20_R050 | 521 | 0,188 | 0,000 | 0,120 | 47,0% | 73,8 | VALIDATING |
| GB30_R050 | 521 | 0,153 | 0,000 | 0,084 | 45,9% | 73,8 | VALIDATING |
| GB20_R100 | 511 | 0,094 | 0,000 | 0,041 | 35,6% | 73,5 | VALIDATING |
| TP_R100 | 511 | 0,071 | 0,000 | 0,024 | 34,1% | 73,5 | VALIDATING |
| GB30_R100 | 511 | 0,068 | 0,000 | 0,016 | 35,2% | 73,4 | VALIDATING |
| GB40_R100 | 511 | 0,044 | 0,000 | -0,007 | 35,2% | 72,0 | VALIDATING |
| GB50_R050 | 519 | 0,076 | 0,000 | 0,011 | 44,7% | 69,9 | VALIDATING |
| TIME_12H | 507 | 0,061 | 0,000 | -0,005 | 44,8% | 68,1 | VALIDATING |
| TP_R150 | 496 | 0,034 | 0,000 | -0,021 | 25,6% | 62,5 | VALIDATING |
| GB50_R100 | 508 | 0,029 | 0,000 | -0,018 | 33,1% | 61,5 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 465 | -0,046 | 0,000 | -0,120 | 28,6% | 35,3 | VALIDATING |
| ATR15_R100 | 497 | -0,047 | 0,000 | -0,091 | 27,4% | 32,6 | UNDERPERFORMING |
| BE_R050 | 472 | -0,078 | 0,000 | -0,149 | 29,2% | 32,2 | UNDERPERFORMING |
| TIME_24H | 500 | -0,053 | 0,000 | -0,140 | 29,2% | 31,0 | VALIDATING |
| ATR20_R100 | 488 | -0,080 | 0,000 | -0,129 | 23,4% | 30,8 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
