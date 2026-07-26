# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T15:53:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **716**
- Scenari virtuali ancora attivi: **10131**
- Gruppi in attesa dell'uscita originale: **341**
- Gruppi con originale chiuso ma Shadow ancora attive: **375**
- Confronti completati: **43966**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1623 | 1688 | +€7,07 | 49,5% | 519 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1623 | 1688 | +€5,45 | 47,9% | 536 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1623 | 1688 | +€3,38 | 46,4% | 533 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1623 | 1688 | +€2,73 | 45,6% | 590 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1622 | 1687 | +€2,19 | 46,3% | 486 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1602 | 1667 | €-0,59 | 44,9% | 376 | 286 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1594 | 1659 | +€8,14 | 45,0% | 423 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1594 | 1659 | +€6,35 | 44,4% | 409 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1594 | 1659 | +€6,03 | 42,0% | 477 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1593 | 1658 | +€5,21 | 44,5% | 339 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1589 | 1654 | +€4,06 | 41,7% | 273 | 228 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1562 | 1627 | €-0,10 | 33,9% | 179 | 384 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1556 | 1621 | +€0,87 | 41,1% | 191 | 405 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1540 | 1605 | +€6,27 | 31,3% | 229 | 177 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1530 | 1595 | €-3,96 | 29,3% | 159 | 447 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1515 | 1580 | €-8,40 | 27,2% | 114 | 492 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1502 | 1567 | €-10,63 | 29,9% | 305 | 336 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1474 | 1539 | +€6,91 | 38,3% | 102 | 261 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1427 | 1492 | €-1,72 | 35,3% | 87 | 438 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1391 | 1456 | €-14,74 | 22,1% | 113 | 472 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
