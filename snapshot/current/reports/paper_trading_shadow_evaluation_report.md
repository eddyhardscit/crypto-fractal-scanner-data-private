# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T17:23:36+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **2235**
- Valutazioni prodotte: **2135**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R100 | 76 | 0,119 | 0,000 | -0,012 | 34,2% | 63,0 | VALIDATING |
| GB20_R050 | 77 | 0,226 | 0,000 | 0,051 | 41,6% | 61,8 | VALIDATING |
| GB30_R050 | 77 | 0,194 | 0,000 | 0,023 | 40,3% | 61,8 | VALIDATING |
| GB50_R050 | 76 | 0,175 | 0,000 | 0,007 | 40,8% | 61,5 | VALIDATING |
| GB40_R050 | 77 | 0,155 | 0,000 | -0,011 | 40,3% | 60,1 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB30_R100 | 76 | 0,072 | 0,000 | -0,057 | 34,2% | 56,1 | VALIDATING |
| TP_R100 | 76 | 0,081 | 0,000 | -0,061 | 34,2% | 55,6 | VALIDATING |
| TP_R050 | 77 | 0,134 | 0,000 | -0,057 | 41,6% | 53,3 | VALIDATING |
| GB50_R100 | 75 | 0,040 | 0,000 | -0,073 | 33,3% | 51,6 | VALIDATING |
| TP_R200 | 68 | 0,093 | 0,000 | -0,055 | 26,5% | 51,3 | VALIDATING |
| TIME_6H | 75 | 0,031 | 0,000 | -0,063 | 44,0% | 50,2 | VALIDATING |
| BE_R050 | 70 | 0,055 | 0,000 | -0,089 | 34,3% | 46,7 | VALIDATING |
| TIME_12H | 60 | 0,101 | 0,000 | -0,084 | 25,0% | 45,0 | VALIDATING |
| GB40_R100 | 76 | 0,025 | 0,000 | -0,094 | 34,2% | 44,0 | VALIDATING |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| ATR15_R100 | 66 | -0,018 | 0,000 | -0,085 | 31,8% | 27,9 | VALIDATING |
| ATR20_R100 | 63 | -0,037 | 0,000 | -0,126 | 28,6% | 26,5 | VALIDATING |
| ATR30_R100 | 62 | -0,027 | 0,000 | -0,120 | 29,0% | 26,3 | VALIDATING |
| BE_R100 | 62 | -0,027 | 0,000 | -0,115 | 29,0% | 26,3 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
