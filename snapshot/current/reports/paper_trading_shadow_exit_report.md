# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T13:53:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **734**
- Scenari virtuali ancora attivi: **10720**
- Gruppi in attesa dell'uscita originale: **352**
- Gruppi con originale chiuso ma Shadow ancora attive: **382**
- Confronti completati: **41283**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1579 | 1644 | +€6,31 | 48,5% | 519 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1579 | 1644 | +€4,69 | 46,9% | 536 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1579 | 1644 | +€2,58 | 45,4% | 533 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1579 | 1644 | +€1,83 | 44,5% | 590 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1578 | 1643 | +€1,40 | 45,3% | 486 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1560 | 1625 | €-0,87 | 44,7% | 376 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1546 | 1611 | +€8,30 | 45,3% | 423 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1546 | 1611 | +€6,46 | 44,6% | 409 | 53 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1546 | 1611 | +€6,11 | 42,1% | 477 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1544 | 1609 | +€5,29 | 44,6% | 339 | 110 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1540 | 1605 | +€4,12 | 41,8% | 273 | 224 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1494 | 1559 | +€6,50 | 31,4% | 229 | 170 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1491 | 1556 | +€0,39 | 34,6% | 179 | 358 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1486 | 1551 | +€2,18 | 42,1% | 191 | 374 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1457 | 1522 | €-3,61 | 29,8% | 159 | 419 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1436 | 1501 | €-11,39 | 29,1% | 305 | 314 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1428 | 1493 | +€7,45 | 39,0% | 102 | 249 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1424 | 1489 | €-8,20 | 27,5% | 114 | 453 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1366 | 1431 | €-1,02 | 35,7% | 87 | 418 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1310 | 1375 | €-14,87 | 22,4% | 113 | 437 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
