# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T19:24:03+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **597**
- Scenari virtuali ancora attivi: **9888**
- Gruppi in attesa dell'uscita originale: **348**
- Gruppi con originale chiuso ma Shadow ancora attive: **249**
- Confronti completati: **23875**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1161 | 1226 | +€1,99 | 48,2% | 388 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1161 | 1226 | +€0,07 | 46,7% | 400 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1161 | 1226 | €-2,11 | 45,7% | 422 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1160 | 1225 | €-2,11 | 45,7% | 394 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1159 | 1224 | €-3,58 | 44,5% | 386 | 47 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1141 | 1206 | €-5,22 | 46,0% | 342 | 142 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1138 | 1203 | +€2,99 | 42,4% | 322 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1138 | 1203 | +€1,27 | 42,4% | 308 | 41 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1138 | 1203 | +€0,90 | 39,3% | 361 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1136 | 1201 | €-0,34 | 41,8% | 266 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1134 | 1199 | €-1,29 | 38,3% | 230 | 161 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1133 | 1198 | €-3,25 | 41,6% | 188 | 253 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1109 | 1174 | +€2,11 | 31,0% | 175 | 111 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1100 | 1165 | €-4,56 | 34,0% | 146 | 238 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1098 | 1163 | €-9,29 | 27,7% | 127 | 320 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1097 | 1162 | +€3,19 | 39,7% | 96 | 179 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1087 | 1152 | €-17,00 | 28,0% | 249 | 230 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1051 | 1116 | €-15,23 | 23,9% | 91 | 341 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1049 | 1114 | €-3,39 | 35,7% | 84 | 299 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 992 | 1057 | €-21,62 | 19,6% | 90 | 339 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
