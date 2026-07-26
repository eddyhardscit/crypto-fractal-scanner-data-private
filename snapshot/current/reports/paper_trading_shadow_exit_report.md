# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T03:38:46+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **607**
- Scenari virtuali ancora attivi: **10329**
- Gruppi in attesa dell'uscita originale: **364**
- Gruppi con originale chiuso ma Shadow ancora attive: **243**
- Confronti completati: **27930**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1270 | 1335 | +€2,01 | 48,3% | 420 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1270 | 1335 | +€0,19 | 46,4% | 435 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1270 | 1335 | €-2,17 | 45,2% | 466 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1261 | 1326 | €-1,80 | 45,7% | 426 | 26 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1258 | 1323 | €-4,86 | 46,5% | 344 | 189 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1252 | 1317 | €-3,19 | 44,9% | 411 | 48 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1248 | 1313 | +€3,62 | 44,0% | 342 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1248 | 1313 | +€1,77 | 43,7% | 324 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1248 | 1313 | +€0,84 | 40,0% | 397 | 26 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1225 | 1290 | €-3,39 | 41,7% | 189 | 294 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1224 | 1289 | +€0,23 | 43,1% | 273 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1222 | 1287 | +€1,22 | 30,1% | 188 | 143 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1214 | 1279 | €-0,69 | 39,6% | 237 | 166 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1200 | 1265 | €-3,77 | 36,0% | 85 | 374 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1198 | 1263 | +€2,71 | 39,1% | 97 | 211 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1186 | 1251 | €-4,35 | 35,3% | 149 | 255 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1168 | 1233 | €-8,59 | 29,7% | 130 | 322 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1167 | 1232 | €-15,98 | 29,7% | 264 | 230 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1131 | 1196 | €-14,09 | 26,5% | 94 | 347 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1063 | 1128 | €-20,20 | 22,3% | 93 | 342 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
