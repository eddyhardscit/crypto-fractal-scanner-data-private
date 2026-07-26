# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T18:53:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **751**
- Scenari virtuali ancora attivi: **11242**
- Gruppi in attesa dell'uscita originale: **367**
- Gruppi con originale chiuso ma Shadow ancora attive: **384**
- Confronti completati: **44858**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1652 | 1717 | +€6,97 | 49,6% | 525 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1652 | 1717 | +€5,35 | 47,3% | 543 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1652 | 1717 | +€3,28 | 45,8% | 552 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1652 | 1717 | +€2,66 | 45,1% | 608 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1651 | 1716 | +€2,08 | 45,7% | 506 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1636 | 1701 | €-0,81 | 44,5% | 380 | 305 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1619 | 1684 | +€8,16 | 45,4% | 425 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1619 | 1684 | +€6,35 | 44,7% | 413 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1619 | 1684 | +€6,08 | 42,3% | 479 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1619 | 1684 | +€5,19 | 44,5% | 341 | 115 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1613 | 1678 | +€4,01 | 41,9% | 277 | 229 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1607 | 1672 | +€0,43 | 40,8% | 191 | 436 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1568 | 1633 | €-0,10 | 33,8% | 179 | 384 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1560 | 1625 | +€6,56 | 31,6% | 229 | 178 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1537 | 1602 | €-3,95 | 29,2% | 159 | 448 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1521 | 1586 | €-8,37 | 27,0% | 114 | 492 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1513 | 1578 | €-10,75 | 29,7% | 308 | 338 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1492 | 1557 | +€6,84 | 38,2% | 102 | 269 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1461 | 1526 | €-1,09 | 36,0% | 87 | 446 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1402 | 1467 | €-14,79 | 21,9% | 113 | 477 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
