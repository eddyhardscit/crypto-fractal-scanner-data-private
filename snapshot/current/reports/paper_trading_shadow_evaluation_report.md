# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T14:53:45+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **16420**
- Valutazioni prodotte: **4569**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 139 | 0,415 | 0,330 | 0,290 | 74,8% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB30_R050 | 139 | 0,363 | 0,286 | 0,236 | 74,8% | 98,5 | ELIGIBLE_FOR_MUTATION |
| GB50_R050 | 138 | 0,305 | 0,243 | 0,203 | 71,7% | 98,5 | ELIGIBLE_FOR_MUTATION |
| GB40_R050 | 139 | 0,305 | 0,243 | 0,187 | 72,7% | 98,4 | ELIGIBLE_FOR_MUTATION |
| TP_R050 | 139 | 0,237 | 0,271 | 0,132 | 72,7% | 96,8 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 138 | 0,377 | 0,294 | 0,232 | 72,5% | 94,9 | VALIDATING |
| TP_R100 | 138 | 0,340 | 0,287 | 0,210 | 71,7% | 94,9 | VALIDATING |
| GB40_R100 | 137 | 0,290 | 0,258 | 0,169 | 72,3% | 94,8 | VALIDATING |
| GB30_R100 | 138 | 0,338 | 0,287 | 0,214 | 74,6% | 94,7 | VALIDATING |
| GB50_R100 | 137 | 0,238 | 0,287 | 0,115 | 70,8% | 94,6 | VALIDATING |
| TP_R150 | 133 | 0,183 | 0,147 | 0,033 | 57,9% | 91,3 | ELIGIBLE_FOR_MUTATION |
| TIME_6H | 138 | 0,111 | 0,104 | -0,032 | 56,5% | 81,4 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 636 | 0,102 | 0,000 | 0,040 | 45,3% | 70,0 | VALIDATING |
| GB20_R100 | 630 | 0,071 | 0,000 | 0,025 | 37,0% | 69,8 | VALIDATING |
| TP_R150 | 623 | 0,069 | 0,000 | 0,017 | 28,1% | 69,8 | VALIDATING |
| GB30_R050 | 636 | 0,062 | 0,000 | -0,005 | 43,7% | 69,3 | VALIDATING |
| GB30_R100 | 629 | 0,033 | 0,000 | -0,020 | 36,6% | 62,8 | VALIDATING |
| TIME_12H | 639 | 0,040 | 0,000 | -0,035 | 44,0% | 62,2 | VALIDATING |
| TP_R100 | 630 | 0,038 | 0,000 | -0,012 | 34,8% | 61,7 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
