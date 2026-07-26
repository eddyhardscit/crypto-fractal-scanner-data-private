# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T02:38:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **610**
- Scenari virtuali ancora attivi: **10295**
- Gruppi in attesa dell'uscita originale: **359**
- Gruppi con originale chiuso ma Shadow ancora attive: **251**
- Confronti completati: **27688**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1262 | 1327 | +€2,02 | 48,6% | 419 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1262 | 1327 | €-2,18 | 45,5% | 465 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1256 | 1321 | +€0,25 | 46,9% | 434 | 10 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1254 | 1319 | €-1,81 | 45,9% | 426 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1245 | 1310 | €-3,21 | 45,1% | 411 | 48 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1240 | 1305 | +€3,64 | 44,3% | 341 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1240 | 1305 | +€0,84 | 40,2% | 396 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1232 | 1297 | +€1,87 | 44,3% | 323 | 42 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1231 | 1296 | €-5,48 | 45,6% | 344 | 186 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1217 | 1282 | +€0,23 | 43,3% | 273 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1214 | 1279 | +€1,23 | 30,3% | 187 | 143 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1208 | 1273 | €-3,68 | 41,1% | 189 | 292 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1207 | 1272 | €-0,69 | 39,8% | 237 | 166 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1190 | 1255 | +€2,73 | 39,4% | 97 | 211 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1181 | 1246 | €-3,96 | 36,0% | 85 | 368 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1178 | 1243 | €-4,38 | 35,5% | 149 | 254 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1161 | 1226 | €-8,63 | 29,9% | 130 | 322 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1160 | 1225 | €-16,07 | 29,9% | 264 | 230 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1119 | 1184 | €-14,20 | 26,5% | 94 | 345 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1056 | 1121 | €-20,32 | 22,4% | 93 | 342 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
