# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T02:53:44+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **14805**
- Valutazioni prodotte: **4321**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 86 | 0,406 | 0,366 | 0,253 | 86,0% | 95,6 | VALIDATING |
| GB30_R050 | 86 | 0,358 | 0,301 | 0,208 | 86,0% | 95,5 | VALIDATING |
| GB40_R050 | 86 | 0,300 | 0,287 | 0,153 | 82,6% | 95,4 | VALIDATING |
| GB20_R100 | 85 | 0,469 | 0,408 | 0,331 | 85,9% | 95,4 | VALIDATING |
| GB30_R100 | 85 | 0,440 | 0,335 | 0,311 | 89,4% | 95,3 | VALIDATING |
| TP_R100 | 85 | 0,421 | 0,408 | 0,286 | 84,7% | 95,3 | VALIDATING |
| GB40_R100 | 85 | 0,378 | 0,330 | 0,260 | 84,7% | 95,3 | VALIDATING |
| GB50_R050 | 84 | 0,338 | 0,287 | 0,204 | 84,5% | 94,8 | VALIDATING |
| GB50_R100 | 83 | 0,353 | 0,408 | 0,227 | 84,3% | 94,6 | VALIDATING |
| TP_R050 | 86 | 0,221 | 0,287 | 0,070 | 82,6% | 89,3 | VALIDATING |
| TIME_6H | 82 | 0,075 | 0,192 | -0,079 | 67,1% | 78,5 | VALIDATING |
| ATR15_R100 | 83 | 0,053 | 0,104 | -0,064 | 63,9% | 76,2 | VALIDATING |
| BE_R050 | 78 | 0,083 | 0,136 | -0,056 | 59,0% | 75,3 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 64 | 0,050 | 0,243 | -0,122 | 73,4% | 71,7 | VALIDATING |
| GB20_R050 | 611 | 0,096 | 0,000 | 0,030 | 44,2% | 70,0 | VALIDATING |
| GB20_R100 | 605 | 0,055 | 0,000 | 0,008 | 36,0% | 69,7 | VALIDATING |
| TP_R150 | 599 | 0,058 | 0,000 | 0,009 | 27,4% | 69,7 | VALIDATING |
| GB30_R050 | 611 | 0,056 | 0,000 | -0,007 | 42,6% | 69,0 | VALIDATING |
| TIME_12H | 612 | 0,046 | 0,000 | -0,027 | 43,6% | 65,0 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
