# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T14:31:22+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **576**
- Scenari virtuali ancora attivi: **5852**
- Gruppi in attesa dell'uscita originale: **312**
- Gruppi con originale chiuso ma Shadow ancora attive: **264**
- Confronti completati: **20790**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 1032 | 1096 | €-3,93 | 47,1% | 304 | 127 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 1030 | 1094 | +€2,98 | 49,1% | 335 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1030 | 1094 | +€1,09 | 47,9% | 342 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1030 | 1094 | €-1,11 | 46,6% | 338 | 24 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1030 | 1094 | €-1,48 | 47,3% | 358 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1023 | 1087 | €-2,40 | 46,0% | 325 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1019 | 1083 | €-1,13 | 44,4% | 155 | 227 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1012 | 1076 | +€1,91 | 41,4% | 309 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1011 | 1075 | +€3,87 | 43,7% | 281 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1011 | 1075 | +€2,10 | 44,1% | 263 | 39 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1008 | 1072 | +€0,73 | 43,5% | 224 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 997 | 1061 | €-0,51 | 40,2% | 181 | 149 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 975 | 1039 | +€3,95 | 33,1% | 130 | 94 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 939 | 1003 | +€4,03 | 41,5% | 72 | 154 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 933 | 997 | €-2,51 | 36,9% | 81 | 258 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 915 | 979 | €-13,47 | 29,0% | 214 | 156 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 912 | 976 | €-3,45 | 34,8% | 92 | 204 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 899 | 963 | €-7,13 | 29,9% | 77 | 249 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 883 | 947 | €-11,00 | 26,7% | 71 | 253 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 820 | 884 | €-17,10 | 21,9% | 70 | 246 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
