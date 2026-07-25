# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T18:23:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **582**
- Scenari virtuali ancora attivi: **9144**
- Gruppi in attesa dell'uscita originale: **336**
- Gruppi con originale chiuso ma Shadow ancora attive: **246**
- Confronti completati: **23395**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1145 | 1210 | +€1,79 | 48,0% | 387 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1145 | 1210 | €-0,13 | 46,5% | 399 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1145 | 1210 | €-2,37 | 45,5% | 421 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1144 | 1209 | €-2,32 | 45,5% | 393 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1143 | 1208 | €-3,77 | 44,3% | 385 | 47 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1135 | 1200 | €-5,25 | 46,2% | 342 | 142 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1128 | 1193 | €-3,27 | 41,7% | 188 | 253 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1123 | 1188 | +€2,66 | 42,1% | 322 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1123 | 1188 | +€0,96 | 42,1% | 308 | 41 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1123 | 1188 | +€0,48 | 39,0% | 361 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1121 | 1186 | €-0,62 | 41,5% | 266 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1118 | 1183 | €-1,55 | 38,0% | 230 | 160 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1104 | 1169 | +€2,12 | 31,1% | 175 | 111 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1092 | 1157 | +€3,21 | 39,8% | 96 | 179 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1076 | 1141 | €-4,45 | 33,9% | 145 | 229 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1073 | 1138 | €-9,26 | 27,5% | 126 | 310 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1069 | 1134 | €-17,23 | 27,6% | 248 | 228 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1028 | 1093 | €-3,52 | 35,8% | 84 | 290 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1027 | 1092 | €-15,33 | 23,6% | 90 | 332 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 968 | 1033 | €-21,87 | 19,2% | 89 | 330 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
