# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T12:23:45+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **20214**
- Valutazioni prodotte: **5615**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB30_R100 | 331 | 0,136 | 0,189 | 0,039 | 62,2% | 92,0 | VALIDATING |
| GB20_R100 | 331 | 0,163 | 0,149 | 0,076 | 60,1% | 90,1 | VALIDATING |
| TP_R200 | 277 | 0,177 | 0,243 | 0,058 | 59,9% | 89,5 | ELIGIBLE_FOR_MUTATION |
| GB40_R100 | 329 | 0,088 | 0,189 | 0,000 | 60,5% | 86,6 | VALIDATING |
| TP_R100 | 331 | 0,120 | 0,149 | 0,026 | 56,2% | 86,2 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R150 | 298 | 0,132 | 0,000 | 0,035 | 45,3% | 73,3 | VALIDATING |
| GB20_R050 | 334 | 0,037 | 0,149 | -0,059 | 57,2% | 71,3 | VALIDATING |
| GB20_R050 | 660 | 0,092 | 0,000 | 0,028 | 46,1% | 70,0 | VALIDATING |
| TP_R150 | 633 | 0,063 | 0,000 | 0,012 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 645 | 0,065 | 0,000 | 0,015 | 37,4% | 69,8 | VALIDATING |
| GB50_R100 | 321 | 0,023 | 0,122 | -0,057 | 57,6% | 67,7 | VALIDATING |
| GB30_R050 | 660 | 0,051 | 0,000 | -0,016 | 44,5% | 67,7 | VALIDATING |
| TP_R200 | 623 | 0,050 | 0,000 | -0,013 | 35,2% | 64,0 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 645 | 0,033 | 0,000 | -0,022 | 35,2% | 58,7 | VALIDATING |
| GB30_R100 | 645 | 0,026 | 0,000 | -0,029 | 37,1% | 55,2 | VALIDATING |
| GB30_R050 | 334 | 0,003 | 0,135 | -0,100 | 56,3% | 52,8 | VALIDATING |
| GB50_R050 | 329 | -0,059 | 0,104 | -0,145 | 56,2% | 51,6 | VALIDATING |
| TP_R050 | 660 | 0,013 | 0,000 | -0,054 | 43,5% | 51,5 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
