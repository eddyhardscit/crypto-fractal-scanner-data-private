# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T04:08:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **842**
- Scenari virtuali ancora attivi: **14231**
- Gruppi in attesa dell'uscita originale: **426**
- Gruppi con originale chiuso ma Shadow ancora attive: **416**
- Confronti completati: **49864**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1756 | 1821 | +€6,93 | 48,9% | 536 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1756 | 1821 | +€5,34 | 46,8% | 553 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1756 | 1821 | +€3,34 | 45,4% | 562 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1756 | 1821 | +€2,86 | 44,6% | 619 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1756 | 1821 | €-0,40 | 45,1% | 392 | 305 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1755 | 1820 | +€2,13 | 44,8% | 524 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1741 | 1806 | +€1,19 | 40,5% | 195 | 462 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1724 | 1789 | +€8,07 | 45,2% | 430 | 33 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1724 | 1789 | +€6,27 | 44,4% | 418 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1724 | 1789 | +€6,12 | 42,0% | 489 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1723 | 1788 | +€5,18 | 44,4% | 343 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1717 | 1782 | +€3,98 | 41,6% | 279 | 237 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1692 | 1757 | +€0,29 | 33,5% | 192 | 397 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1656 | 1721 | +€6,43 | 31,3% | 232 | 183 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1654 | 1719 | €-3,49 | 28,7% | 164 | 472 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1635 | 1700 | €-1,77 | 35,5% | 90 | 506 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1627 | 1692 | €-7,75 | 26,7% | 118 | 510 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1617 | 1682 | €-10,25 | 28,4% | 329 | 349 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1583 | 1648 | +€6,66 | 37,7% | 102 | 276 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1497 | 1562 | €-14,35 | 21,1% | 117 | 499 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
