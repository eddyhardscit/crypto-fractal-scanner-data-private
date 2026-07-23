# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T12:38:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **10711**
- Valutazioni prodotte: **3289**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 485 | 0,038 | 0,043 | -0,040 | 54,2% | 75,5 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 486 | 0,194 | 0,000 | 0,125 | 47,9% | 73,8 | VALIDATING |
| TP_R050 | 486 | 0,122 | 0,000 | 0,049 | 46,5% | 73,8 | VALIDATING |
| GB30_R050 | 486 | 0,160 | 0,000 | 0,089 | 46,7% | 73,8 | VALIDATING |
| GB40_R050 | 486 | 0,121 | 0,000 | 0,052 | 46,1% | 73,7 | VALIDATING |
| GB20_R100 | 475 | 0,110 | 0,000 | 0,061 | 37,3% | 73,6 | VALIDATING |
| TP_R100 | 475 | 0,079 | 0,000 | 0,026 | 35,6% | 69,8 | VALIDATING |
| GB30_R100 | 475 | 0,086 | 0,000 | 0,033 | 36,8% | 69,8 | VALIDATING |
| GB50_R050 | 486 | 0,079 | 0,000 | 0,015 | 45,3% | 69,8 | VALIDATING |
| GB40_R100 | 475 | 0,063 | 0,000 | 0,014 | 36,8% | 69,6 | VALIDATING |
| TP_R150 | 453 | 0,064 | 0,000 | 0,008 | 28,0% | 69,5 | VALIDATING |
| GB50_R100 | 475 | 0,045 | 0,000 | 0,001 | 34,5% | 69,3 | VALIDATING |
| TIME_12H | 485 | 0,041 | 0,000 | -0,029 | 44,1% | 59,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 423 | -0,023 | 0,000 | -0,094 | 30,3% | 40,0 | VALIDATING |
| TIME_24H | 479 | -0,071 | 0,000 | -0,162 | 28,8% | 34,6 | VALIDATING |
| BE_R050 | 443 | -0,086 | 0,000 | -0,159 | 28,9% | 32,1 | UNDERPERFORMING |
| ATR15_R100 | 475 | -0,055 | 0,000 | -0,101 | 28,0% | 31,1 | UNDERPERFORMING |
| ATR30_R100 | 454 | -0,113 | 0,000 | -0,185 | 23,1% | 31,0 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
