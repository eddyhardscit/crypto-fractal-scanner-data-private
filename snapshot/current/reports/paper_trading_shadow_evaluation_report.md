# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T20:23:37+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **2282**
- Valutazioni prodotte: **2142**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R100 | 76 | 0,119 | 0,000 | -0,012 | 34,2% | 63,0 | VALIDATING |
| GB20_R050 | 79 | 0,239 | 0,000 | 0,082 | 43,0% | 62,3 | VALIDATING |
| GB30_R050 | 79 | 0,206 | 0,000 | 0,049 | 41,8% | 62,2 | VALIDATING |
| GB40_R050 | 79 | 0,165 | 0,000 | 0,003 | 41,8% | 62,2 | VALIDATING |
| GB50_R050 | 79 | 0,172 | 0,000 | -0,003 | 41,8% | 61,7 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB30_R100 | 76 | 0,072 | 0,000 | -0,057 | 34,2% | 56,1 | VALIDATING |
| TP_R100 | 76 | 0,081 | 0,000 | -0,061 | 34,2% | 55,6 | VALIDATING |
| TP_R050 | 79 | 0,144 | 0,000 | -0,050 | 43,0% | 54,6 | VALIDATING |
| TIME_6H | 76 | 0,037 | 0,000 | -0,057 | 44,7% | 53,4 | VALIDATING |
| TP_R200 | 68 | 0,093 | 0,000 | -0,055 | 26,5% | 51,3 | VALIDATING |
| TIME_12H | 64 | 0,105 | 0,000 | -0,066 | 26,6% | 48,7 | VALIDATING |
| GB50_R100 | 76 | 0,030 | 0,000 | -0,082 | 32,9% | 47,0 | VALIDATING |
| BE_R050 | 72 | 0,053 | 0,000 | -0,091 | 33,3% | 46,8 | VALIDATING |
| GB40_R100 | 76 | 0,025 | 0,000 | -0,094 | 34,2% | 44,0 | VALIDATING |
| TIME_24H | 4 | 0,816 | 0,809 | -0,282 | 50,0% | 38,3 | INSUFFICIENT_DATA |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| ATR15_R100 | 66 | -0,018 | 0,000 | -0,085 | 31,8% | 27,9 | VALIDATING |
| ATR20_R100 | 63 | -0,037 | 0,000 | -0,126 | 28,6% | 26,5 | VALIDATING |
| ATR30_R100 | 62 | -0,027 | 0,000 | -0,120 | 29,0% | 26,3 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
