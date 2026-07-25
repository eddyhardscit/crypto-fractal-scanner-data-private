# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T15:23:56+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **567**
- Scenari virtuali ancora attivi: **5503**
- Gruppi in attesa dell'uscita originale: **276**
- Gruppi con originale chiuso ma Shadow ancora attive: **291**
- Confronti completati: **21871**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1088 | 1153 | +€0,20 | 47,6% | 379 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1088 | 1153 | €-1,75 | 46,5% | 386 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1088 | 1153 | €-3,96 | 45,3% | 382 | 24 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1088 | 1153 | €-4,16 | 45,5% | 406 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1081 | 1146 | €-5,26 | 44,3% | 373 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1070 | 1135 | €-6,11 | 45,8% | 339 | 127 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1065 | 1130 | +€2,16 | 42,9% | 318 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1065 | 1130 | +€0,46 | 42,9% | 304 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1065 | 1130 | €-0,11 | 39,6% | 357 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1062 | 1127 | €-1,12 | 42,4% | 264 | 78 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1054 | 1119 | €-2,85 | 43,3% | 186 | 227 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1053 | 1118 | €-1,81 | 39,1% | 225 | 149 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1046 | 1111 | +€2,30 | 31,7% | 169 | 108 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1033 | 1098 | +€4,10 | 41,2% | 92 | 171 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1000 | 1065 | €-4,44 | 35,6% | 137 | 206 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 985 | 1050 | €-9,28 | 28,6% | 122 | 276 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 952 | 1017 | €-15,02 | 28,4% | 236 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 938 | 1003 | €-2,66 | 36,7% | 84 | 258 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 903 | 968 | €-11,74 | 26,2% | 86 | 255 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 845 | 910 | €-18,16 | 21,4% | 85 | 253 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
