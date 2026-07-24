# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T06:53:44+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **15458**
- Valutazioni prodotte: **4355**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 114 | 0,523 | 0,408 | 0,379 | 87,7% | 98,7 | ROBUST |
| GB30_R050 | 114 | 0,465 | 0,326 | 0,333 | 87,7% | 98,7 | ROBUST |
| GB20_R100 | 110 | 0,536 | 0,417 | 0,411 | 86,4% | 98,6 | ROBUST |
| GB30_R100 | 110 | 0,495 | 0,413 | 0,375 | 89,1% | 98,6 | ROBUST |
| TP_R100 | 110 | 0,491 | 0,417 | 0,374 | 85,5% | 98,6 | ROBUST |
| GB40_R100 | 110 | 0,430 | 0,413 | 0,317 | 85,5% | 98,5 | ROBUST |
| GB50_R050 | 114 | 0,391 | 0,319 | 0,278 | 84,2% | 98,4 | ROBUST |
| GB50_R100 | 110 | 0,373 | 0,412 | 0,273 | 83,6% | 98,3 | ROBUST |
| GB40_R050 | 114 | 0,401 | 0,322 | 0,276 | 85,1% | 94,8 | ROBUST |
| BE_R050 | 106 | 0,104 | 0,158 | 0,002 | 66,0% | 94,2 | ROBUST |
| TP_R050 | 114 | 0,303 | 0,308 | 0,184 | 85,1% | 92,9 | ROBUST |
| ATR30_R100 | 103 | 0,048 | 0,147 | -0,044 | 65,0% | 87,7 | VALIDATING |
| ATR15_R100 | 110 | 0,048 | 0,147 | -0,047 | 68,2% | 87,1 | VALIDATING |
| BE_R100 | 103 | 0,039 | 0,147 | -0,054 | 65,0% | 84,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 622 | 0,102 | 0,000 | 0,034 | 45,2% | 70,0 | VALIDATING |
| GB20_R100 | 610 | 0,062 | 0,000 | 0,013 | 36,6% | 69,7 | VALIDATING |
| GB30_R050 | 622 | 0,062 | 0,000 | -0,002 | 43,6% | 69,7 | VALIDATING |
| TP_R150 | 599 | 0,058 | 0,000 | 0,009 | 27,4% | 69,7 | VALIDATING |
| ATR20_R100 | 108 | 0,005 | 0,147 | -0,099 | 63,9% | 65,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
