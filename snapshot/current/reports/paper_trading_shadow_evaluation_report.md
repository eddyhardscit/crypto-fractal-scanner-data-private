# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T20:23:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **10218**
- Valutazioni prodotte: **3283**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 464 | 0,124 | 0,000 | 0,051 | 46,8% | 73,8 | VALIDATING |
| GB40_R050 | 464 | 0,125 | 0,000 | 0,054 | 46,8% | 73,8 | VALIDATING |
| GB20_R050 | 464 | 0,199 | 0,000 | 0,122 | 48,5% | 73,8 | VALIDATING |
| GB30_R050 | 464 | 0,165 | 0,000 | 0,097 | 47,2% | 73,7 | VALIDATING |
| GB20_R100 | 457 | 0,108 | 0,000 | 0,059 | 37,6% | 73,5 | VALIDATING |
| TP_R100 | 457 | 0,076 | 0,000 | 0,021 | 35,9% | 73,5 | VALIDATING |
| GB30_R100 | 456 | 0,083 | 0,000 | 0,033 | 37,3% | 73,5 | VALIDATING |
| GB40_R100 | 456 | 0,061 | 0,000 | 0,010 | 37,3% | 73,3 | VALIDATING |
| GB50_R100 | 454 | 0,045 | 0,000 | -0,001 | 35,0% | 72,8 | VALIDATING |
| GB50_R050 | 464 | 0,082 | 0,000 | 0,018 | 46,1% | 69,9 | VALIDATING |
| TP_R150 | 428 | 0,062 | 0,000 | 0,004 | 28,0% | 69,4 | VALIDATING |
| TIME_6H | 463 | 0,022 | 0,036 | -0,054 | 53,1% | 66,9 | VALIDATING |
| TIME_12H | 445 | 0,052 | 0,000 | -0,020 | 45,2% | 65,8 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 403 | -0,012 | 0,000 | -0,086 | 31,0% | 41,1 | VALIDATING |
| TIME_24H | 419 | -0,064 | 0,000 | -0,167 | 28,9% | 34,6 | VALIDATING |
| ATR15_R100 | 448 | -0,040 | 0,000 | -0,083 | 28,8% | 33,5 | VALIDATING |
| BE_R050 | 420 | -0,075 | 0,000 | -0,149 | 29,8% | 32,1 | UNDERPERFORMING |
| ATR30_R100 | 428 | -0,103 | 0,000 | -0,173 | 23,8% | 31,0 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
