# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T21:39:01+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **633**
- Scenari virtuali ancora attivi: **10399**
- Gruppi in attesa dell'uscita originale: **361**
- Gruppi con originale chiuso ma Shadow ancora attive: **272**
- Confronti completati: **25312**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1194 | 1259 | +€2,32 | 49,4% | 390 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1194 | 1259 | +€0,43 | 47,9% | 403 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1194 | 1259 | €-1,66 | 46,9% | 425 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1194 | 1259 | €-1,68 | 46,9% | 397 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1192 | 1257 | €-3,15 | 45,7% | 389 | 47 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1172 | 1237 | +€3,65 | 43,7% | 324 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1172 | 1237 | +€1,90 | 43,7% | 310 | 42 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1172 | 1237 | +€1,56 | 40,7% | 363 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1171 | 1236 | +€0,25 | 43,2% | 268 | 83 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1169 | 1234 | €-5,77 | 45,5% | 343 | 163 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1168 | 1233 | €-0,77 | 39,7% | 232 | 162 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1145 | 1210 | €-3,26 | 41,7% | 189 | 258 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1144 | 1209 | €-4,65 | 35,3% | 149 | 248 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1132 | 1197 | €-8,99 | 29,4% | 130 | 321 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1122 | 1187 | +€2,26 | 31,5% | 177 | 112 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1120 | 1185 | €-16,44 | 29,7% | 252 | 230 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1106 | 1171 | +€3,20 | 39,9% | 97 | 180 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1085 | 1150 | €-14,74 | 25,8% | 94 | 342 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1080 | 1145 | €-3,01 | 36,9% | 85 | 305 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1026 | 1091 | €-20,91 | 21,7% | 93 | 340 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
