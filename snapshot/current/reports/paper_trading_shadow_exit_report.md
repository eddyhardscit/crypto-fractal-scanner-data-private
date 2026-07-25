# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T20:38:54+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **611**
- Scenari virtuali ancora attivi: **9369**
- Gruppi in attesa dell'uscita originale: **338**
- Gruppi con originale chiuso ma Shadow ancora attive: **273**
- Confronti completati: **25116**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1191 | 1256 | +€2,32 | 49,3% | 390 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1191 | 1256 | +€0,43 | 47,8% | 403 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1191 | 1256 | €-1,67 | 46,7% | 425 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1190 | 1255 | €-1,69 | 46,8% | 397 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1189 | 1254 | €-3,17 | 45,6% | 389 | 47 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1169 | 1234 | +€3,65 | 43,6% | 324 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1169 | 1234 | +€1,90 | 43,6% | 310 | 42 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1169 | 1234 | +€1,56 | 40,6% | 363 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1167 | 1232 | +€0,24 | 43,0% | 268 | 83 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1165 | 1230 | €-0,78 | 39,6% | 232 | 162 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1146 | 1211 | €-5,26 | 46,0% | 343 | 144 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1139 | 1204 | €-3,25 | 41,6% | 189 | 255 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1131 | 1196 | €-4,39 | 35,4% | 149 | 239 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1129 | 1194 | €-9,02 | 29,2% | 130 | 321 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1119 | 1184 | +€2,26 | 31,3% | 177 | 112 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1117 | 1182 | €-16,49 | 29,5% | 252 | 230 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1103 | 1168 | +€3,20 | 39,7% | 97 | 180 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1082 | 1147 | €-14,78 | 25,6% | 94 | 342 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1055 | 1120 | €-3,30 | 35,9% | 85 | 300 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1023 | 1088 | €-20,97 | 21,5% | 93 | 340 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
