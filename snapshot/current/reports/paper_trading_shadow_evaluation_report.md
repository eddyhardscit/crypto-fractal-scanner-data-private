# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T08:23:46+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **20021**
- Valutazioni prodotte: **5580**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB30_R100 | 323 | 0,155 | 0,189 | 0,064 | 63,2% | 93,0 | VALIDATING |
| GB20_R100 | 326 | 0,180 | 0,187 | 0,094 | 61,0% | 91,0 | VALIDATING |
| GB40_R100 | 298 | 0,091 | 0,198 | 0,004 | 60,7% | 90,6 | VALIDATING |
| TP_R200 | 267 | 0,171 | 0,243 | 0,044 | 59,9% | 89,7 | ELIGIBLE_FOR_MUTATION |
| GB50_R100 | 283 | 0,055 | 0,243 | -0,031 | 63,3% | 88,4 | VALIDATING |
| TP_R100 | 326 | 0,137 | 0,159 | 0,047 | 57,1% | 87,0 | VALIDATING |
| GB20_R050 | 328 | 0,058 | 0,167 | -0,039 | 57,9% | 77,7 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R150 | 293 | 0,142 | 0,000 | 0,042 | 45,7% | 73,3 | VALIDATING |
| GB20_R050 | 660 | 0,092 | 0,000 | 0,028 | 46,1% | 70,0 | VALIDATING |
| TP_R150 | 633 | 0,063 | 0,000 | 0,012 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 645 | 0,065 | 0,000 | 0,015 | 37,4% | 69,8 | VALIDATING |
| GB30_R050 | 660 | 0,051 | 0,000 | -0,016 | 44,5% | 67,7 | VALIDATING |
| TP_R200 | 623 | 0,050 | 0,000 | -0,013 | 35,2% | 64,0 | VALIDATING |
| GB30_R050 | 327 | 0,019 | 0,147 | -0,073 | 57,2% | 63,1 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 645 | 0,033 | 0,000 | -0,022 | 35,2% | 58,7 | VALIDATING |
| GB30_R100 | 645 | 0,026 | 0,000 | -0,029 | 37,1% | 55,2 | VALIDATING |
| GB50_R050 | 313 | -0,031 | 0,140 | -0,120 | 58,1% | 53,5 | VALIDATING |
| TP_R050 | 328 | -0,047 | 0,147 | -0,145 | 57,0% | 52,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
