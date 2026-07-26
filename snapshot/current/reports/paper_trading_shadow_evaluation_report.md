# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-26T04:38:48+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **28471**
- Valutazioni prodotte: **10692**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R100 | 113 | 0,283 | 0,252 | 0,146 | 59,3% | 89,1 | VALIDATING |
| GB50_R100 | 70 | 0,285 | 0,275 | 0,119 | 61,4% | 85,2 | VALIDATING |
| GB40_R100 | 86 | 0,223 | 0,095 | 0,061 | 58,1% | 85,2 | VALIDATING |
| BE_R075 | 56 | 0,146 | 0,286 | -0,005 | 71,4% | 84,1 | VALIDATING |
| BE_A075 | 56 | 0,146 | 0,286 | -0,007 | 71,4% | 83,7 | VALIDATING |
| GB20_R075 | 113 | 0,232 | 0,057 | 0,092 | 54,0% | 83,6 | VALIDATING |
| BE_A060 | 56 | 0,146 | 0,286 | -0,010 | 71,4% | 83,2 | VALIDATING |
| GB50_R075 | 74 | 0,245 | 0,199 | 0,073 | 58,1% | 82,5 | VALIDATING |
| GB30_R100 | 113 | 0,174 | 0,151 | 0,031 | 54,9% | 80,8 | VALIDATING |
| TP_R250 | 84 | 0,231 | 0,199 | 0,060 | 54,8% | 80,6 | VALIDATING |
| ATR15_R100 | 62 | 0,099 | 0,269 | -0,042 | 64,5% | 79,8 | VALIDATING |
| ATR30_R100 | 56 | 0,110 | 0,286 | -0,044 | 71,4% | 78,8 | VALIDATING |
| ATR20_R100 | 56 | 0,110 | 0,286 | -0,046 | 71,4% | 78,4 | VALIDATING |
| BE_R100 | 56 | 0,110 | 0,286 | -0,053 | 71,4% | 77,4 | VALIDATING |
| BE_A100 | 56 | 0,110 | 0,286 | -0,054 | 71,4% | 77,2 | VALIDATING |
| TP_R300 | 75 | 0,381 | 0,063 | 0,153 | 52,0% | 76,8 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 665 | 0,107 | 0,000 | 0,043 | 46,2% | 69,6 | VALIDATING |
| GB30_R050 | 665 | 0,067 | 0,000 | -0,001 | 44,7% | 69,5 | VALIDATING |
| GB40_R075 | 86 | 0,192 | 0,000 | 0,035 | 48,8% | 66,9 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
