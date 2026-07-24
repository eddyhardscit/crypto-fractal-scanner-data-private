# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T12:53:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **15838**
- Valutazioni prodotte: **4379**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 125 | 0,470 | 0,359 | 0,346 | 80,0% | 98,7 | ELIGIBLE_FOR_MUTATION |
| GB30_R050 | 125 | 0,418 | 0,287 | 0,305 | 80,0% | 98,7 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 124 | 0,505 | 0,401 | 0,391 | 79,0% | 98,7 | ELIGIBLE_FOR_MUTATION |
| TP_R100 | 125 | 0,466 | 0,330 | 0,353 | 78,4% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB40_R050 | 125 | 0,359 | 0,279 | 0,239 | 77,6% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB40_R100 | 124 | 0,406 | 0,322 | 0,308 | 78,2% | 98,6 | ELIGIBLE_FOR_MUTATION |
| GB50_R050 | 125 | 0,349 | 0,287 | 0,250 | 76,8% | 98,4 | ELIGIBLE_FOR_MUTATION |
| GB30_R100 | 124 | 0,466 | 0,326 | 0,358 | 81,5% | 98,4 | ELIGIBLE_FOR_MUTATION |
| GB50_R100 | 124 | 0,352 | 0,322 | 0,257 | 76,6% | 98,4 | ELIGIBLE_FOR_MUTATION |
| TP_R050 | 125 | 0,271 | 0,287 | 0,153 | 77,6% | 96,8 | ELIGIBLE_FOR_MUTATION |
| TP_R150 | 115 | 0,232 | 0,149 | 0,094 | 61,7% | 91,5 | ROBUST |
| TIME_6H | 125 | 0,179 | 0,147 | 0,042 | 60,8% | 90,4 | ELIGIBLE_FOR_MUTATION |
| ATR15_R100 | 120 | 0,044 | 0,116 | -0,048 | 62,5% | 84,0 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 623 | 0,103 | 0,000 | 0,037 | 45,3% | 70,0 | VALIDATING |
| GB20_R100 | 611 | 0,062 | 0,000 | 0,015 | 36,7% | 69,7 | VALIDATING |
| GB30_R050 | 623 | 0,062 | 0,000 | -0,002 | 43,7% | 69,7 | VALIDATING |
| TP_R150 | 600 | 0,058 | 0,000 | 0,010 | 27,5% | 69,7 | VALIDATING |
| TIME_12H | 626 | 0,040 | 0,000 | -0,036 | 43,8% | 62,1 | VALIDATING |
| GB30_R100 | 611 | 0,024 | 0,000 | -0,024 | 36,2% | 59,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
