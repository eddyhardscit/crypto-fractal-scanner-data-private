# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T17:53:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **722**
- Scenari virtuali ancora attivi: **9736**
- Gruppi in attesa dell'uscita originale: **334**
- Gruppi con originale chiuso ma Shadow ancora attive: **388**
- Confronti completati: **44710**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1650 | 1715 | +€7,01 | 49,7% | 523 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1650 | 1715 | +€5,39 | 47,3% | 541 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1650 | 1715 | +€3,32 | 45,9% | 550 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1650 | 1715 | +€2,69 | 45,1% | 606 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1649 | 1714 | +€2,11 | 45,7% | 504 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1633 | 1698 | €-0,80 | 44,5% | 378 | 305 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1617 | 1682 | +€8,17 | 45,3% | 425 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1617 | 1682 | +€6,36 | 44,7% | 411 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1617 | 1682 | +€6,09 | 42,3% | 479 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1617 | 1682 | +€5,19 | 44,6% | 341 | 115 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1613 | 1678 | +€4,01 | 41,9% | 277 | 229 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1582 | 1647 | +€0,93 | 41,3% | 191 | 414 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1568 | 1633 | €-0,10 | 33,8% | 179 | 384 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1560 | 1625 | +€6,56 | 31,6% | 229 | 178 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1537 | 1602 | €-3,95 | 29,2% | 159 | 448 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1521 | 1586 | €-8,37 | 27,0% | 114 | 492 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1511 | 1576 | €-10,71 | 29,8% | 306 | 338 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1486 | 1551 | +€6,87 | 38,3% | 102 | 263 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1433 | 1498 | €-1,69 | 35,3% | 87 | 438 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1402 | 1467 | €-14,79 | 21,9% | 113 | 477 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
