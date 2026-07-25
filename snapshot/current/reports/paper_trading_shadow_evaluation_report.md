# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T06:08:54+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **19522**
- Valutazioni prodotte: **5507**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R100 | 275 | 0,233 | 0,330 | 0,135 | 65,8% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB30_R100 | 273 | 0,201 | 0,322 | 0,099 | 67,4% | 98,6 | ELIGIBLE_FOR_MUTATION |
| TP_R100 | 293 | 0,204 | 0,287 | 0,106 | 62,8% | 96,5 | ELIGIBLE_FOR_MUTATION |
| GB40_R100 | 273 | 0,140 | 0,275 | 0,042 | 65,6% | 91,2 | VALIDATING |
| GB50_R100 | 268 | 0,091 | 0,276 | -0,002 | 66,0% | 90,7 | VALIDATING |
| GB20_R050 | 297 | 0,133 | 0,253 | 0,031 | 63,0% | 88,5 | VALIDATING |
| GB30_R050 | 297 | 0,078 | 0,243 | -0,017 | 62,0% | 84,8 | VALIDATING |
| TP_R200 | 231 | 0,118 | 0,149 | -0,028 | 58,4% | 83,9 | VALIDATING |
| TP_R150 | 260 | 0,164 | 0,010 | 0,052 | 50,0% | 77,0 | VALIDATING |
| TP_R050 | 297 | 0,038 | 0,243 | -0,060 | 62,0% | 75,6 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 657 | 0,090 | 0,000 | 0,028 | 45,8% | 70,0 | VALIDATING |
| TP_R150 | 633 | 0,063 | 0,000 | 0,012 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 643 | 0,062 | 0,000 | 0,013 | 37,2% | 69,8 | VALIDATING |
| GB40_R050 | 297 | 0,028 | 0,196 | -0,067 | 59,9% | 69,7 | VALIDATING |
| GB30_R050 | 657 | 0,050 | 0,000 | -0,017 | 44,3% | 67,5 | VALIDATING |
| GB50_R050 | 294 | 0,016 | 0,152 | -0,069 | 60,5% | 65,9 | VALIDATING |
| TP_R200 | 623 | 0,050 | 0,000 | -0,013 | 35,2% | 64,0 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 643 | 0,030 | 0,000 | -0,023 | 35,0% | 57,5 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
