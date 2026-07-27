# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T02:08:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **792**
- Scenari virtuali ancora attivi: **11870**
- Gruppi in attesa dell'uscita originale: **382**
- Gruppi con originale chiuso ma Shadow ancora attive: **410**
- Confronti completati: **48870**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 1738 | 1803 | €-0,45 | 45,3% | 392 | 305 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 1735 | 1800 | +€6,95 | 49,1% | 536 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1735 | 1800 | +€5,35 | 46,9% | 553 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1735 | 1800 | +€3,33 | 45,6% | 562 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1735 | 1800 | +€2,84 | 44,8% | 619 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1734 | 1799 | +€2,11 | 45,0% | 524 | 87 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1703 | 1768 | +€8,14 | 45,4% | 430 | 33 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1703 | 1768 | +€6,31 | 44,6% | 418 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1703 | 1768 | +€6,16 | 42,2% | 489 | 31 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1703 | 1768 | +€0,69 | 40,0% | 195 | 462 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1702 | 1767 | +€5,22 | 44,5% | 343 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1696 | 1761 | +€4,01 | 41,8% | 279 | 237 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1674 | 1739 | +€0,29 | 33,8% | 190 | 397 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1638 | 1703 | +€6,43 | 31,5% | 232 | 183 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1636 | 1701 | €-3,53 | 29,0% | 161 | 472 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1609 | 1674 | €-7,84 | 27,0% | 115 | 510 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1599 | 1664 | €-10,39 | 28,7% | 326 | 349 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1597 | 1662 | €-1,29 | 35,8% | 90 | 492 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1568 | 1633 | +€6,72 | 38,0% | 102 | 276 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1479 | 1544 | €-14,52 | 21,4% | 114 | 499 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
