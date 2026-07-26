# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T23:08:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **785**
- Scenari virtuali ancora attivi: **11929**
- Gruppi in attesa dell'uscita originale: **393**
- Gruppi con originale chiuso ma Shadow ancora attive: **392**
- Confronti completati: **45339**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 1668 | 1733 | €-0,77 | 44,8% | 391 | 305 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 1665 | 1730 | +€6,75 | 49,3% | 534 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1665 | 1730 | +€5,13 | 47,0% | 552 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1665 | 1730 | +€3,07 | 45,5% | 561 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1665 | 1730 | +€2,47 | 44,8% | 617 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1664 | 1729 | +€1,86 | 45,4% | 515 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1634 | 1699 | +€5,97 | 42,1% | 488 | 30 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1629 | 1694 | +€0,27 | 40,6% | 194 | 447 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1627 | 1692 | +€8,02 | 45,2% | 430 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1627 | 1692 | +€6,20 | 44,4% | 418 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1624 | 1689 | +€5,11 | 44,4% | 343 | 115 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1620 | 1685 | +€3,92 | 41,7% | 279 | 231 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1587 | 1652 | +€6,73 | 32,0% | 231 | 178 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1572 | 1637 | €-0,09 | 33,8% | 179 | 384 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1543 | 1608 | €-3,96 | 29,0% | 159 | 451 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1526 | 1591 | €-10,80 | 29,5% | 313 | 342 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1525 | 1590 | €-8,37 | 27,0% | 114 | 493 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1523 | 1588 | €-0,81 | 36,6% | 90 | 468 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1514 | 1579 | +€7,07 | 38,6% | 102 | 271 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1408 | 1473 | €-14,84 | 21,9% | 113 | 480 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
