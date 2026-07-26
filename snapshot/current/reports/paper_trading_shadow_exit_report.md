# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T04:38:45+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **645**
- Scenari virtuali ancora attivi: **11290**
- Gruppi in attesa dell'uscita originale: **384**
- Gruppi con originale chiuso ma Shadow ancora attive: **261**
- Confronti completati: **28471**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1291 | 1356 | +€1,58 | 47,6% | 439 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1291 | 1356 | €-0,25 | 45,8% | 454 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1291 | 1356 | €-2,56 | 44,6% | 485 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1278 | 1343 | €-2,29 | 45,1% | 440 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1271 | 1336 | €-5,24 | 46,0% | 356 | 189 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1268 | 1333 | +€3,31 | 43,6% | 358 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1268 | 1333 | +€1,44 | 43,2% | 341 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1268 | 1333 | +€0,60 | 39,6% | 413 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1264 | 1329 | €-3,60 | 44,5% | 422 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1240 | 1305 | +€1,13 | 29,8% | 199 | 143 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1240 | 1305 | €-0,13 | 42,7% | 284 | 89 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1229 | 1294 | €-3,45 | 41,7% | 191 | 294 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1220 | 1285 | €-0,91 | 39,4% | 242 | 166 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1213 | 1278 | +€2,73 | 38,9% | 101 | 211 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1207 | 1272 | €-3,82 | 36,0% | 87 | 376 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1188 | 1253 | €-4,45 | 35,2% | 150 | 255 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1172 | 1237 | €-16,17 | 29,6% | 267 | 231 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1170 | 1235 | €-8,68 | 29,6% | 131 | 322 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1133 | 1198 | €-14,17 | 26,5% | 95 | 347 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1066 | 1131 | €-20,29 | 22,2% | 94 | 343 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
