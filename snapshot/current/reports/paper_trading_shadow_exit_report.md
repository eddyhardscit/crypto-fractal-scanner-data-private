# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T09:38:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **703**
- Scenari virtuali ancora attivi: **10414**
- Gruppi in attesa dell'uscita originale: **320**
- Gruppi con originale chiuso ma Shadow ancora attive: **383**
- Confronti completati: **38965**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1540 | 1605 | +€6,31 | 48,3% | 510 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1540 | 1605 | +€4,71 | 46,6% | 527 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1540 | 1605 | +€2,58 | 45,5% | 516 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1540 | 1605 | +€1,82 | 44,7% | 573 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1539 | 1604 | +€1,39 | 45,1% | 477 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1511 | 1576 | +€6,13 | 42,2% | 469 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1510 | 1575 | +€8,41 | 45,5% | 414 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1510 | 1575 | +€6,55 | 44,8% | 400 | 53 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1509 | 1574 | +€5,43 | 44,9% | 330 | 110 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1505 | 1570 | +€4,30 | 42,1% | 264 | 224 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1477 | 1542 | €-0,34 | 46,4% | 373 | 229 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1446 | 1511 | +€6,79 | 31,5% | 229 | 157 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1442 | 1507 | +€0,82 | 35,5% | 179 | 327 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1410 | 1475 | +€2,67 | 42,8% | 191 | 333 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1410 | 1475 | €-3,18 | 30,5% | 159 | 390 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1391 | 1456 | +€8,05 | 39,8% | 102 | 229 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1374 | 1439 | €-10,67 | 29,5% | 303 | 275 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1340 | 1405 | €-7,84 | 27,9% | 114 | 401 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1322 | 1387 | €-0,46 | 36,8% | 87 | 390 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1251 | 1316 | €-14,17 | 23,3% | 113 | 395 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
