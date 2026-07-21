# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T00:38:37+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **2318**
- Valutazioni prodotte: **2147**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R100 | 77 | 0,126 | 0,000 | -0,007 | 35,1% | 64,0 | VALIDATING |
| GB20_R050 | 80 | 0,242 | 0,000 | 0,087 | 43,8% | 62,5 | VALIDATING |
| GB30_R050 | 80 | 0,208 | 0,000 | 0,048 | 42,5% | 62,5 | VALIDATING |
| GB40_R050 | 80 | 0,166 | 0,000 | 0,013 | 42,5% | 62,4 | VALIDATING |
| GB50_R050 | 80 | 0,172 | 0,000 | 0,015 | 42,5% | 62,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 77 | 0,090 | 0,000 | -0,045 | 35,1% | 58,2 | VALIDATING |
| GB30_R100 | 77 | 0,078 | 0,000 | -0,050 | 35,1% | 57,5 | VALIDATING |
| TP_R050 | 80 | 0,146 | 0,000 | -0,042 | 43,8% | 56,1 | VALIDATING |
| TIME_12H | 76 | 0,103 | 0,000 | -0,034 | 36,8% | 54,6 | VALIDATING |
| TP_R200 | 69 | 0,099 | 0,000 | -0,037 | 27,5% | 54,1 | VALIDATING |
| GB50_R100 | 77 | 0,033 | 0,000 | -0,066 | 33,8% | 51,0 | VALIDATING |
| TIME_6H | 80 | 0,030 | 0,000 | -0,059 | 46,2% | 48,0 | VALIDATING |
| BE_R050 | 73 | 0,050 | 0,000 | -0,093 | 32,9% | 46,6 | VALIDATING |
| GB40_R100 | 77 | 0,030 | 0,000 | -0,093 | 35,1% | 46,1 | VALIDATING |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| ATR15_R100 | 66 | -0,018 | 0,000 | -0,085 | 31,8% | 27,9 | VALIDATING |
| TIME_24H | 55 | 0,017 | 0,000 | -0,121 | 21,8% | 27,6 | VALIDATING |
| ATR20_R100 | 63 | -0,037 | 0,000 | -0,126 | 28,6% | 26,5 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
