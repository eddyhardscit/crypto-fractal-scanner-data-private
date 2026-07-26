# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T07:38:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **735**
- Scenari virtuali ancora attivi: **12607**
- Gruppi in attesa dell'uscita originale: **360**
- Gruppi con originale chiuso ma Shadow ancora attive: **375**
- Confronti completati: **34849**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1466 | 1531 | +€6,43 | 49,2% | 504 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1466 | 1531 | +€4,78 | 47,4% | 521 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1466 | 1531 | +€1,81 | 45,9% | 559 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1458 | 1523 | +€2,60 | 46,1% | 510 | 37 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1437 | 1502 | +€8,57 | 45,9% | 413 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1437 | 1502 | +€6,66 | 45,3% | 399 | 53 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1437 | 1502 | +€6,09 | 42,5% | 468 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1430 | 1495 | +€1,26 | 46,0% | 472 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1408 | 1473 | +€4,93 | 44,5% | 329 | 106 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1392 | 1457 | €-0,24 | 47,8% | 373 | 208 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1376 | 1441 | +€7,10 | 32,0% | 228 | 149 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1370 | 1435 | +€4,09 | 42,2% | 264 | 190 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1335 | 1400 | +€8,65 | 41,3% | 102 | 220 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1321 | 1386 | +€1,69 | 43,7% | 191 | 316 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1311 | 1376 | €-0,30 | 36,6% | 177 | 284 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1284 | 1349 | €-10,83 | 31,4% | 295 | 249 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1279 | 1344 | €-4,17 | 31,3% | 156 | 347 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1264 | 1329 | €-0,36 | 38,1% | 87 | 382 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1254 | 1319 | €-8,41 | 29,3% | 111 | 378 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1159 | 1224 | €-14,41 | 25,0% | 110 | 361 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
