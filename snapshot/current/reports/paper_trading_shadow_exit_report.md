# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T01:38:45+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **583**
- Scenari virtuali ancora attivi: **9789**
- Gruppi in attesa dell'uscita originale: **358**
- Gruppi con originale chiuso ma Shadow ancora attive: **225**
- Confronti completati: **26854**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1232 | 1297 | +€2,79 | 49,1% | 397 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1232 | 1297 | €-1,06 | 46,5% | 436 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1229 | 1294 | +€1,04 | 47,6% | 411 | 10 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1227 | 1292 | €-0,95 | 46,7% | 403 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1226 | 1291 | €-2,41 | 45,7% | 393 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1225 | 1290 | €-5,51 | 45,5% | 343 | 186 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1210 | 1275 | +€1,55 | 41,0% | 368 | 26 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1207 | 1272 | €-3,70 | 41,0% | 189 | 292 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1205 | 1270 | +€3,68 | 44,1% | 324 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1205 | 1270 | +€1,97 | 44,1% | 310 | 42 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1204 | 1269 | +€0,36 | 43,6% | 268 | 83 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1202 | 1267 | €-0,63 | 39,9% | 236 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1185 | 1250 | +€1,41 | 30,9% | 177 | 143 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1179 | 1244 | €-4,01 | 35,9% | 85 | 368 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1171 | 1236 | €-4,43 | 35,6% | 149 | 248 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1164 | 1229 | +€2,29 | 38,9% | 97 | 211 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1160 | 1225 | €-8,67 | 29,8% | 130 | 322 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1147 | 1212 | €-15,51 | 30,1% | 252 | 230 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1113 | 1178 | €-14,29 | 26,3% | 94 | 343 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1053 | 1118 | €-20,27 | 22,4% | 93 | 340 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
