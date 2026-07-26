# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T05:38:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **668**
- Scenari virtuali ancora attivi: **11372**
- Gruppi in attesa dell'uscita originale: **370**
- Gruppi con originale chiuso ma Shadow ancora attive: **298**
- Confronti completati: **30546**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1345 | 1410 | +€1,87 | 48,7% | 449 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1345 | 1410 | +€0,03 | 46,7% | 467 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1345 | 1410 | €-2,12 | 45,7% | 496 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1331 | 1396 | €-2,02 | 45,5% | 461 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1319 | 1384 | €-3,34 | 44,8% | 443 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1317 | 1382 | +€1,03 | 40,7% | 423 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1316 | 1381 | +€3,62 | 44,6% | 367 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1315 | 1380 | +€1,69 | 44,2% | 350 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1312 | 1377 | €-4,93 | 46,1% | 370 | 193 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1287 | 1352 | +€0,06 | 43,7% | 293 | 89 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1272 | 1337 | €-0,86 | 40,4% | 253 | 169 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1264 | 1329 | +€1,23 | 30,0% | 204 | 143 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1241 | 1306 | €-3,33 | 42,0% | 191 | 294 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1237 | 1302 | +€2,51 | 39,1% | 101 | 214 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1236 | 1301 | €-4,76 | 35,1% | 166 | 267 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1220 | 1285 | €-15,76 | 29,7% | 283 | 239 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1219 | 1284 | €-3,71 | 36,4% | 87 | 376 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1208 | 1273 | €-8,60 | 29,9% | 147 | 325 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1204 | 1269 | €-13,39 | 27,3% | 111 | 368 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1109 | 1174 | €-20,05 | 22,7% | 110 | 351 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
