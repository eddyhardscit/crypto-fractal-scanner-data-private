# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T08:38:46+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **764**
- Scenari virtuali ancora attivi: **13272**
- Gruppi in attesa dell'uscita originale: **366**
- Gruppi con originale chiuso ma Shadow ancora attive: **398**
- Confronti completati: **35996**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1490 | 1555 | +€6,46 | 49,5% | 510 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1490 | 1555 | +€4,82 | 47,8% | 527 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1490 | 1555 | +€1,86 | 45,8% | 573 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1483 | 1548 | +€2,64 | 46,4% | 516 | 38 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1471 | 1536 | +€1,16 | 45,8% | 477 | 83 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1461 | 1526 | +€8,65 | 46,7% | 414 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1461 | 1526 | +€6,73 | 46,0% | 400 | 53 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1461 | 1526 | +€6,24 | 43,3% | 469 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1439 | 1504 | +€4,98 | 45,3% | 330 | 110 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1424 | 1489 | +€3,80 | 42,2% | 264 | 220 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1406 | 1471 | €-0,15 | 48,0% | 373 | 212 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1391 | 1456 | +€7,15 | 32,6% | 229 | 149 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1362 | 1427 | +€1,10 | 37,4% | 177 | 295 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1337 | 1402 | +€8,64 | 41,3% | 102 | 220 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1329 | 1394 | +€2,26 | 44,0% | 191 | 316 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1310 | 1375 | €-10,70 | 30,8% | 300 | 260 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1300 | 1365 | €-4,14 | 30,8% | 156 | 358 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1275 | 1340 | €-8,31 | 28,9% | 111 | 389 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1266 | 1331 | €-0,30 | 38,1% | 87 | 382 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1180 | 1245 | €-14,20 | 24,6% | 110 | 372 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
