# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T17:23:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **9158**
- Valutazioni prodotte: **3274**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 391 | 0,147 | 0,033 | 0,076 | 51,2% | 83,9 | VALIDATING |
| TIME_6H | 412 | 0,045 | 0,051 | -0,033 | 55,6% | 80,3 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R100 | 414 | 0,086 | 0,000 | 0,030 | 37,4% | 73,5 | VALIDATING |
| GB30_R100 | 414 | 0,063 | 0,000 | 0,005 | 37,0% | 73,4 | VALIDATING |
| GB40_R100 | 414 | 0,044 | 0,000 | -0,011 | 37,0% | 71,1 | VALIDATING |
| TP_R050 | 421 | 0,099 | 0,000 | 0,018 | 45,8% | 70,1 | VALIDATING |
| GB30_R050 | 421 | 0,139 | 0,000 | 0,063 | 46,3% | 70,0 | VALIDATING |
| GB40_R050 | 421 | 0,100 | 0,000 | 0,026 | 46,1% | 70,0 | VALIDATING |
| GB20_R050 | 421 | 0,173 | 0,000 | 0,096 | 47,7% | 70,0 | VALIDATING |
| TP_R150 | 397 | 0,066 | 0,000 | 0,009 | 29,5% | 69,3 | VALIDATING |
| TP_R200 | 355 | 0,089 | 0,000 | 0,018 | 35,2% | 69,1 | VALIDATING |
| TP_R100 | 414 | 0,053 | 0,000 | -0,004 | 35,5% | 69,0 | VALIDATING |
| GB50_R050 | 421 | 0,057 | 0,000 | -0,014 | 45,4% | 67,7 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R100 | 391 | 0,002 | 0,000 | -0,046 | 33,2% | 44,4 | VALIDATING |
| TIME_24H | 357 | 0,001 | 0,000 | -0,111 | 31,4% | 34,8 | VALIDATING |
| ATR15_R100 | 384 | -0,034 | 0,000 | -0,082 | 27,6% | 34,1 | VALIDATING |
| BE_R050 | 370 | -0,066 | 0,000 | -0,143 | 31,9% | 32,1 | VALIDATING |
| BE_R100 | 320 | -0,190 | 0,000 | -0,266 | 22,5% | 30,3 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
