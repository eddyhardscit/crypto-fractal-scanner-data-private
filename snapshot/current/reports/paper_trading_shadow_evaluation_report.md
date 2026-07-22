# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T08:08:40+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **8062**
- Valutazioni prodotte: **3213**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 348 | 0,171 | 0,036 | 0,095 | 51,7% | 84,5 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 363 | 0,197 | 0,000 | 0,109 | 46,8% | 73,8 | VALIDATING |
| GB30_R050 | 363 | 0,159 | 0,000 | 0,078 | 45,2% | 73,8 | VALIDATING |
| GB40_R050 | 363 | 0,122 | 0,000 | 0,041 | 44,9% | 73,8 | VALIDATING |
| TP_R200 | 331 | 0,108 | 0,000 | 0,038 | 34,4% | 72,7 | VALIDATING |
| TP_R050 | 363 | 0,126 | 0,000 | 0,040 | 44,4% | 70,1 | VALIDATING |
| GB50_R050 | 363 | 0,082 | 0,000 | 0,005 | 44,1% | 69,8 | VALIDATING |
| TIME_6H | 363 | 0,024 | 0,036 | -0,058 | 54,3% | 68,3 | VALIDATING |
| GB20_R100 | 360 | 0,060 | 0,000 | -0,002 | 35,3% | 65,3 | VALIDATING |
| GB30_R100 | 353 | 0,039 | 0,000 | -0,023 | 33,7% | 60,3 | VALIDATING |
| TP_R100 | 361 | 0,035 | 0,000 | -0,024 | 33,2% | 58,7 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB40_R100 | 341 | 0,007 | 0,000 | -0,047 | 33,4% | 49,6 | VALIDATING |
| GB50_R100 | 339 | 0,003 | 0,000 | -0,045 | 30,7% | 44,6 | VALIDATING |
| TP_R150 | 346 | 0,008 | 0,000 | -0,053 | 26,6% | 41,2 | VALIDATING |
| BE_R050 | 328 | -0,072 | 0,000 | -0,153 | 31,7% | 35,9 | VALIDATING |
| ATR20_R100 | 329 | -0,137 | 0,000 | -0,189 | 20,4% | 31,7 | UNDERPERFORMING |
| ATR15_R100 | 335 | -0,070 | 0,000 | -0,110 | 23,6% | 31,2 | UNDERPERFORMING |
| BE_R100 | 296 | -0,204 | 0,000 | -0,290 | 20,9% | 30,4 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
