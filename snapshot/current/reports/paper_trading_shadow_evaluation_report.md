# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T14:23:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **1864**
- Valutazioni prodotte: **2055**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB20_R050 | 59 | 0,186 | 0,000 | -0,031 | 40,7% | 57,0 | VALIDATING |
| GB30_R050 | 59 | 0,150 | 0,000 | -0,052 | 39,0% | 53,8 | VALIDATING |
| TP_R200 | 55 | 0,109 | 0,000 | -0,033 | 29,1% | 51,6 | VALIDATING |
| GB50_R050 | 59 | 0,137 | 0,000 | -0,069 | 39,0% | 51,1 | VALIDATING |
| GB40_R050 | 59 | 0,112 | 0,000 | -0,099 | 39,0% | 46,8 | VALIDATING |
| TP_R050 | 59 | 0,090 | 0,000 | -0,142 | 40,7% | 46,6 | VALIDATING |
| BE_R050 | 52 | 0,064 | 0,000 | -0,119 | 30,8% | 45,8 | VALIDATING |
| GB20_R100 | 59 | 0,053 | 0,000 | -0,102 | 33,9% | 42,8 | VALIDATING |
| TIME_12H | 45 | 0,129 | 0,000 | -0,069 | 28,9% | 39,9 | EARLY_SIGNAL |
| GB30_R100 | 59 | 0,005 | 0,000 | -0,146 | 33,9% | 29,5 | VALIDATING |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| GB40_R100 | 59 | -0,040 | 0,000 | -0,187 | 33,9% | 27,6 | VALIDATING |
| TP_R100 | 59 | -0,003 | 0,000 | -0,162 | 33,9% | 27,5 | VALIDATING |
| GB50_R100 | 59 | -0,021 | 0,000 | -0,128 | 32,2% | 27,4 | VALIDATING |
| TIME_6H | 54 | -0,007 | 0,000 | -0,131 | 38,9% | 25,7 | VALIDATING |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| TP_R150 | 58 | -0,005 | 0,000 | -0,138 | 25,9% | 23,4 | VALIDATING |
| ATR20_R100 | 45 | -0,009 | 0,000 | -0,092 | 26,7% | 18,9 | EARLY_SIGNAL |
| ATR15_R100 | 50 | -0,041 | 0,000 | -0,127 | 30,0% | 18,8 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
