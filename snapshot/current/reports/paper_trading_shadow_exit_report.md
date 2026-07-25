# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T22:38:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **639**
- Scenari virtuali ancora attivi: **10508**
- Gruppi in attesa dell'uscita originale: **361**
- Gruppi con originale chiuso ma Shadow ancora attive: **278**
- Confronti completati: **25462**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1200 | 1265 | +€2,31 | 49,3% | 392 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1200 | 1265 | +€0,43 | 47,7% | 409 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1200 | 1265 | €-1,65 | 46,6% | 431 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1200 | 1265 | €-1,67 | 46,7% | 403 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1198 | 1263 | €-3,14 | 45,7% | 393 | 47 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1178 | 1243 | +€3,64 | 44,0% | 324 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1178 | 1243 | +€1,90 | 44,0% | 310 | 42 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1178 | 1243 | +€1,57 | 41,0% | 363 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1177 | 1242 | +€0,25 | 43,5% | 268 | 83 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1174 | 1239 | €-0,77 | 39,7% | 236 | 162 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1169 | 1234 | €-5,77 | 45,5% | 343 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1145 | 1210 | €-3,26 | 41,7% | 189 | 258 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1144 | 1209 | €-4,65 | 35,3% | 149 | 248 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1132 | 1197 | €-8,99 | 29,4% | 130 | 321 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1122 | 1187 | +€2,26 | 31,5% | 177 | 112 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1120 | 1185 | €-16,44 | 29,7% | 252 | 230 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1106 | 1171 | +€3,20 | 39,9% | 97 | 180 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1085 | 1150 | €-14,74 | 25,8% | 94 | 342 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1082 | 1147 | €-3,06 | 36,8% | 85 | 307 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1026 | 1091 | €-20,91 | 21,7% | 93 | 340 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
