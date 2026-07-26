# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T12:53:46+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **755**
- Scenari virtuali ancora attivi: **11795**
- Gruppi in attesa dell'uscita originale: **373**
- Gruppi con originale chiuso ma Shadow ancora attive: **382**
- Confronti completati: **39971**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1552 | 1617 | +€6,46 | 48,5% | 512 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1552 | 1617 | +€4,85 | 46,9% | 529 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1552 | 1617 | +€2,72 | 45,8% | 518 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1552 | 1617 | +€1,97 | 45,0% | 575 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1551 | 1616 | +€1,51 | 45,4% | 479 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1543 | 1608 | €-0,88 | 45,0% | 375 | 283 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1519 | 1584 | +€8,47 | 45,5% | 416 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1519 | 1584 | +€6,59 | 44,9% | 402 | 53 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1519 | 1584 | +€6,19 | 42,2% | 471 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1517 | 1582 | +€5,43 | 44,9% | 332 | 110 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1513 | 1578 | +€4,28 | 42,1% | 266 | 224 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1479 | 1544 | +€0,39 | 34,8% | 179 | 358 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1465 | 1530 | +€6,49 | 31,4% | 229 | 168 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1445 | 1510 | €-3,64 | 30,0% | 159 | 419 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1436 | 1501 | +€2,32 | 42,6% | 191 | 349 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1406 | 1471 | +€7,66 | 39,5% | 102 | 240 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1406 | 1471 | €-10,81 | 29,4% | 304 | 297 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1370 | 1435 | €-8,14 | 27,5% | 114 | 426 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1337 | 1402 | €-0,83 | 36,4% | 87 | 402 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1281 | 1346 | €-14,35 | 22,9% | 113 | 420 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
