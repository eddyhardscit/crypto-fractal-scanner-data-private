# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T16:23:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **533**
- Scenari virtuali ancora attivi: **5268**
- Gruppi in attesa dell'uscita originale: **275**
- Gruppi con originale chiuso ma Shadow ancora attive: **258**
- Confronti completati: **22429**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1102 | 1167 | +€0,23 | 47,2% | 382 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1102 | 1167 | €-1,67 | 46,2% | 388 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1102 | 1167 | €-3,86 | 45,1% | 383 | 24 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1102 | 1167 | €-4,11 | 45,1% | 410 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1101 | 1166 | €-7,00 | 45,3% | 341 | 141 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1098 | 1163 | €-5,23 | 43,9% | 375 | 43 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1090 | 1155 | €-4,08 | 42,3% | 187 | 249 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1079 | 1144 | +€2,18 | 42,7% | 319 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1079 | 1144 | +€0,49 | 42,7% | 305 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1079 | 1144 | €-0,08 | 39,4% | 358 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1078 | 1143 | €-1,09 | 42,2% | 264 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1072 | 1137 | €-1,89 | 38,6% | 227 | 154 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1065 | 1130 | +€2,35 | 31,9% | 169 | 108 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1049 | 1114 | +€4,05 | 41,1% | 92 | 171 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1039 | 1104 | €-4,52 | 34,7% | 141 | 227 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1015 | 1080 | €-18,15 | 26,9% | 237 | 215 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 999 | 1064 | €-9,35 | 28,3% | 122 | 279 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 982 | 1047 | €-15,48 | 24,4% | 86 | 321 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 974 | 1039 | €-3,82 | 36,5% | 84 | 274 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 920 | 985 | €-22,11 | 19,8% | 85 | 316 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
