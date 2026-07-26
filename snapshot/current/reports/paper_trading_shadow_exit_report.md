# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T00:39:19+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **583**
- Scenari virtuali ancora attivi: **10439**
- Gruppi in attesa dell'uscita originale: **358**
- Gruppi con originale chiuso ma Shadow ancora attive: **225**
- Confronti completati: **26770**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1226 | 1291 | +€3,00 | 49,3% | 392 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1226 | 1291 | +€1,13 | 47,7% | 409 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1226 | 1291 | €-0,87 | 46,7% | 431 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1226 | 1291 | €-0,95 | 46,8% | 403 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1225 | 1290 | €-2,41 | 45,7% | 393 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1224 | 1289 | €-5,54 | 45,5% | 343 | 186 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1204 | 1269 | +€3,68 | 44,1% | 324 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1204 | 1269 | +€1,97 | 44,1% | 310 | 42 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1204 | 1269 | +€1,65 | 41,2% | 363 | 26 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1204 | 1269 | €-3,74 | 41,1% | 189 | 291 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1203 | 1268 | +€0,36 | 43,6% | 268 | 83 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1201 | 1266 | €-0,63 | 39,9% | 236 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1179 | 1244 | +€1,42 | 31,0% | 177 | 143 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1170 | 1235 | €-4,19 | 35,7% | 85 | 365 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1170 | 1235 | €-4,43 | 35,6% | 149 | 248 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1163 | 1228 | +€2,29 | 38,9% | 97 | 211 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1159 | 1224 | €-8,67 | 29,8% | 130 | 322 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1146 | 1211 | €-15,52 | 30,1% | 252 | 230 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1112 | 1177 | €-14,30 | 26,3% | 94 | 343 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1052 | 1117 | €-20,29 | 22,4% | 93 | 340 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
