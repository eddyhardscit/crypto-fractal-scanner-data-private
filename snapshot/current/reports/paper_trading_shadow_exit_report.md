# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T10:53:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **712**
- Scenari virtuali ancora attivi: **10750**
- Gruppi in attesa dell'uscita originale: **339**
- Gruppi con originale chiuso ma Shadow ancora attive: **373**
- Confronti completati: **39642**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1543 | 1608 | +€6,40 | 48,4% | 510 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1543 | 1608 | +€4,80 | 46,7% | 527 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1543 | 1608 | +€2,67 | 45,6% | 516 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1543 | 1608 | +€1,92 | 44,8% | 573 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1542 | 1607 | +€1,48 | 45,2% | 477 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1516 | 1581 | €-0,77 | 45,4% | 373 | 263 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1513 | 1578 | +€8,43 | 45,4% | 414 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1513 | 1578 | +€6,57 | 44,8% | 400 | 53 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1513 | 1578 | +€6,12 | 42,1% | 469 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1511 | 1576 | +€5,42 | 44,8% | 330 | 110 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1507 | 1572 | +€4,29 | 42,0% | 264 | 224 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1476 | 1541 | +€0,39 | 34,8% | 179 | 358 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1459 | 1524 | +€6,40 | 31,2% | 229 | 168 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1442 | 1507 | €-3,65 | 29,9% | 159 | 419 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1427 | 1492 | +€2,25 | 42,5% | 191 | 346 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1404 | 1469 | +€7,63 | 39,4% | 102 | 240 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1399 | 1464 | €-10,88 | 29,2% | 303 | 297 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1367 | 1432 | €-8,16 | 27,4% | 114 | 426 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1335 | 1400 | €-0,83 | 36,4% | 87 | 401 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1278 | 1343 | €-14,38 | 22,8% | 113 | 420 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
