# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T15:23:37+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **1979**
- Valutazioni prodotte: **2060**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 64 | 0,171 | 0,000 | -0,007 | 37,5% | 61,7 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R050 | 64 | 0,126 | 0,000 | -0,061 | 35,9% | 53,3 | VALIDATING |
| GB30_R050 | 64 | 0,138 | 0,000 | -0,075 | 35,9% | 51,3 | VALIDATING |
| GB40_R050 | 64 | 0,103 | 0,000 | -0,076 | 35,9% | 51,1 | VALIDATING |
| TIME_12H | 51 | 0,155 | 0,000 | -0,033 | 27,5% | 50,8 | VALIDATING |
| TP_R200 | 60 | 0,100 | 0,000 | -0,029 | 26,7% | 49,5 | VALIDATING |
| TP_R050 | 64 | 0,083 | 0,000 | -0,119 | 37,5% | 47,6 | VALIDATING |
| GB20_R100 | 64 | 0,048 | 0,000 | -0,086 | 31,2% | 46,0 | VALIDATING |
| BE_R050 | 58 | 0,032 | 0,000 | -0,145 | 27,6% | 38,7 | VALIDATING |
| TIME_6H | 64 | 0,008 | 0,000 | -0,090 | 40,6% | 31,9 | VALIDATING |
| GB30_R100 | 64 | 0,005 | 0,000 | -0,132 | 31,2% | 30,4 | VALIDATING |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| GB40_R100 | 64 | -0,037 | 0,000 | -0,177 | 31,2% | 28,6 | VALIDATING |
| TP_R100 | 64 | -0,003 | 0,000 | -0,145 | 31,2% | 28,5 | VALIDATING |
| GB50_R100 | 64 | -0,019 | 0,000 | -0,133 | 29,7% | 28,4 | VALIDATING |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| TP_R150 | 63 | -0,005 | 0,000 | -0,130 | 23,8% | 24,4 | VALIDATING |
| ATR15_R100 | 55 | -0,037 | 0,000 | -0,115 | 27,3% | 19,8 | VALIDATING |
| ATR20_R100 | 52 | -0,061 | 0,000 | -0,163 | 23,1% | 19,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
