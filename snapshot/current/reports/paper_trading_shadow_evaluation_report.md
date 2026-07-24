# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T13:54:16+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **16201**
- Valutazioni prodotte: **4506**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R100 | 134 | 0,388 | 0,312 | 0,248 | 73,9% | 98,7 | ELIGIBLE_FOR_MUTATION |
| GB40_R050 | 135 | 0,322 | 0,243 | 0,211 | 74,1% | 98,7 | ELIGIBLE_FOR_MUTATION |
| TP_R100 | 134 | 0,350 | 0,287 | 0,214 | 73,1% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB20_R050 | 135 | 0,433 | 0,335 | 0,310 | 76,3% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB30_R050 | 135 | 0,380 | 0,287 | 0,253 | 76,3% | 98,5 | ELIGIBLE_FOR_MUTATION |
| GB50_R050 | 135 | 0,309 | 0,243 | 0,198 | 72,6% | 98,5 | ELIGIBLE_FOR_MUTATION |
| GB30_R100 | 134 | 0,349 | 0,287 | 0,219 | 76,1% | 98,4 | ELIGIBLE_FOR_MUTATION |
| TP_R050 | 135 | 0,252 | 0,275 | 0,147 | 74,1% | 97,0 | ELIGIBLE_FOR_MUTATION |
| GB40_R100 | 134 | 0,292 | 0,273 | 0,174 | 73,1% | 94,8 | VALIDATING |
| GB50_R100 | 134 | 0,239 | 0,287 | 0,113 | 71,6% | 94,6 | VALIDATING |
| TP_R150 | 130 | 0,191 | 0,148 | 0,038 | 59,2% | 92,7 | ELIGIBLE_FOR_MUTATION |
| TIME_6H | 135 | 0,129 | 0,104 | -0,011 | 57,8% | 85,8 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 629 | 0,105 | 0,000 | 0,043 | 45,3% | 70,0 | VALIDATING |
| GB20_R100 | 623 | 0,072 | 0,000 | 0,023 | 36,9% | 69,8 | VALIDATING |
| TP_R150 | 616 | 0,077 | 0,000 | 0,028 | 28,2% | 69,8 | VALIDATING |
| GB30_R050 | 629 | 0,064 | 0,000 | -0,002 | 43,7% | 69,8 | VALIDATING |
| GB30_R100 | 623 | 0,033 | 0,000 | -0,014 | 36,4% | 63,7 | VALIDATING |
| TIME_12H | 632 | 0,041 | 0,000 | -0,036 | 44,0% | 62,6 | VALIDATING |
| TP_R100 | 623 | 0,037 | 0,000 | -0,013 | 34,5% | 61,4 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
