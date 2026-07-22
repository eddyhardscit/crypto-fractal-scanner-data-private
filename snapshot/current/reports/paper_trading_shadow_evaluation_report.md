# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T18:23:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **9579**
- Valutazioni prodotte: **3283**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 396 | 0,140 | 0,026 | 0,072 | 50,5% | 81,8 | VALIDATING |
| TIME_6H | 429 | 0,059 | 0,060 | -0,017 | 56,4% | 79,7 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 438 | 0,192 | 0,000 | 0,112 | 49,8% | 73,8 | VALIDATING |
| GB30_R050 | 438 | 0,157 | 0,000 | 0,086 | 48,2% | 73,8 | VALIDATING |
| GB20_R100 | 430 | 0,110 | 0,000 | 0,056 | 39,1% | 73,5 | VALIDATING |
| GB30_R100 | 430 | 0,084 | 0,000 | 0,031 | 38,6% | 73,4 | VALIDATING |
| GB40_R100 | 430 | 0,062 | 0,000 | 0,007 | 38,6% | 73,3 | VALIDATING |
| GB50_R100 | 428 | 0,046 | 0,000 | -0,007 | 36,2% | 72,2 | VALIDATING |
| TP_R050 | 438 | 0,117 | 0,000 | 0,037 | 47,9% | 70,0 | VALIDATING |
| GB40_R050 | 438 | 0,116 | 0,000 | 0,044 | 47,9% | 70,0 | VALIDATING |
| TP_R100 | 430 | 0,077 | 0,000 | 0,019 | 37,2% | 69,7 | VALIDATING |
| TP_R150 | 403 | 0,069 | 0,000 | 0,009 | 29,5% | 69,3 | VALIDATING |
| TP_R200 | 359 | 0,085 | 0,000 | 0,013 | 34,8% | 69,1 | VALIDATING |
| GB50_R050 | 438 | 0,072 | 0,000 | 0,003 | 47,3% | 66,0 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TIME_24H | 361 | -0,002 | 0,000 | -0,113 | 31,0% | 38,3 | VALIDATING |
| ATR30_R100 | 392 | -0,078 | 0,000 | -0,151 | 26,0% | 34,7 | VALIDATING |
| BE_R050 | 387 | -0,063 | 0,000 | -0,142 | 31,3% | 32,1 | VALIDATING |
| ATR20_R100 | 406 | -0,063 | 0,000 | -0,119 | 26,1% | 31,0 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
