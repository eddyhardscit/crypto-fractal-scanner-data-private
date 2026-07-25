# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T23:38:54+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **600**
- Scenari virtuali ancora attivi: **10240**
- Gruppi in attesa dell'uscita originale: **361**
- Gruppi con originale chiuso ma Shadow ancora attive: **239**
- Confronti completati: **25888**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1204 | 1269 | +€2,30 | 49,3% | 392 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1204 | 1269 | +€0,43 | 47,7% | 409 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1204 | 1269 | €-1,65 | 46,7% | 431 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1204 | 1269 | €-1,66 | 46,7% | 403 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1203 | 1268 | €-3,12 | 45,7% | 393 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1194 | 1259 | €-5,94 | 44,6% | 343 | 184 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1182 | 1247 | +€3,63 | 44,0% | 324 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1182 | 1247 | +€1,89 | 44,0% | 310 | 42 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1182 | 1247 | +€1,56 | 41,1% | 363 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1181 | 1246 | +€0,25 | 43,5% | 268 | 83 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1179 | 1244 | €-0,76 | 39,7% | 236 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1172 | 1237 | €-3,51 | 40,7% | 189 | 281 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1148 | 1213 | €-4,63 | 35,4% | 149 | 248 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1147 | 1212 | +€1,92 | 30,9% | 177 | 133 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1137 | 1202 | €-8,95 | 29,5% | 130 | 322 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1131 | 1196 | +€2,83 | 39,0% | 97 | 201 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1127 | 1192 | €-3,70 | 35,7% | 85 | 345 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1124 | 1189 | €-16,39 | 29,8% | 252 | 230 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1089 | 1154 | €-14,68 | 25,9% | 94 | 342 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1030 | 1095 | €-20,83 | 21,8% | 93 | 340 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
