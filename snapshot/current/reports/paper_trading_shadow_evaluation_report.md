# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T14:31:23+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **20790**
- Valutazioni prodotte: **5852**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB30_R100 | 360 | 0,108 | 0,149 | 0,020 | 58,1% | 87,9 | VALIDATING |
| TP_R200 | 304 | 0,178 | 0,192 | 0,063 | 57,9% | 87,6 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 360 | 0,135 | 0,091 | 0,051 | 56,1% | 86,0 | VALIDATING |
| TP_R100 | 361 | 0,102 | 0,104 | 0,018 | 52,6% | 82,6 | VALIDATING |
| GB20_R050 | 364 | 0,047 | 0,148 | -0,044 | 56,3% | 79,2 | VALIDATING |
| GB40_R100 | 358 | 0,062 | 0,149 | -0,021 | 56,1% | 79,0 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 660 | 0,092 | 0,000 | 0,028 | 46,1% | 70,0 | VALIDATING |
| TP_R150 | 633 | 0,063 | 0,000 | 0,012 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 645 | 0,065 | 0,000 | 0,015 | 37,4% | 69,8 | VALIDATING |
| GB30_R050 | 660 | 0,051 | 0,000 | -0,016 | 44,5% | 67,7 | VALIDATING |
| TP_R150 | 336 | 0,152 | 0,000 | 0,068 | 43,2% | 65,9 | VALIDATING |
| TP_R200 | 629 | 0,040 | 0,000 | -0,028 | 34,8% | 60,0 | VALIDATING |
| GB30_R050 | 364 | 0,013 | 0,135 | -0,078 | 55,5% | 58,9 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 645 | 0,033 | 0,000 | -0,022 | 35,2% | 58,7 | VALIDATING |
| GB30_R100 | 645 | 0,026 | 0,000 | -0,029 | 37,1% | 55,2 | VALIDATING |
| GB50_R100 | 349 | -0,004 | 0,053 | -0,080 | 53,3% | 52,3 | VALIDATING |
| TP_R050 | 660 | 0,013 | 0,000 | -0,054 | 43,5% | 51,5 | VALIDATING |
| GB50_R050 | 359 | -0,051 | 0,104 | -0,136 | 55,4% | 51,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
