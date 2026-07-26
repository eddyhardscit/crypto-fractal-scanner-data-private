# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T06:38:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **714**
- Scenari virtuali ancora attivi: **12617**
- Gruppi in attesa dell'uscita originale: **381**
- Gruppi con originale chiuso ma Shadow ancora attive: **333**
- Confronti completati: **31830**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1386 | 1451 | +€1,47 | 48,2% | 477 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1386 | 1451 | €-0,22 | 46,2% | 496 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1386 | 1451 | €-2,54 | 45,3% | 525 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1370 | 1435 | €-2,21 | 45,2% | 486 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1357 | 1422 | +€3,53 | 44,6% | 389 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1357 | 1422 | +€1,60 | 44,0% | 374 | 53 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1357 | 1422 | +€0,93 | 41,0% | 443 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1354 | 1419 | €-3,51 | 44,7% | 464 | 50 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1326 | 1391 | +€0,04 | 43,4% | 310 | 97 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1321 | 1386 | €-5,00 | 45,8% | 373 | 199 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1304 | 1369 | +€1,06 | 30,2% | 214 | 149 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1299 | 1364 | €-0,70 | 40,6% | 262 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1273 | 1338 | €-3,16 | 42,2% | 191 | 310 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1260 | 1325 | +€2,56 | 39,0% | 101 | 220 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1245 | 1310 | €-4,74 | 35,0% | 171 | 270 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1234 | 1299 | €-15,73 | 29,4% | 290 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1225 | 1290 | €-3,73 | 36,2% | 87 | 382 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1214 | 1279 | €-8,57 | 29,8% | 147 | 331 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1210 | 1275 | €-13,34 | 27,2% | 111 | 374 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1115 | 1180 | €-19,96 | 22,5% | 110 | 357 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
