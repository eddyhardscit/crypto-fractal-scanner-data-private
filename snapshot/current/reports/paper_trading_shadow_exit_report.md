# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T08:23:45+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **479**
- Scenari virtuali ancora attivi: **4521**
- Gruppi in attesa dell'uscita originale: **228**
- Gruppi con originale chiuso ma Shadow ancora attive: **251**
- Confronti completati: **20021**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 994 | 1058 | +€3,15 | 49,3% | 318 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 994 | 1058 | €-1,55 | 47,4% | 341 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 993 | 1057 | +€1,18 | 48,2% | 325 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 991 | 1055 | €-1,01 | 46,9% | 321 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 991 | 1055 | €-3,82 | 47,7% | 286 | 125 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 977 | 1041 | +€4,47 | 44,9% | 265 | 25 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 977 | 1041 | +€2,34 | 42,4% | 293 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 974 | 1038 | +€2,71 | 45,2% | 247 | 38 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 974 | 1038 | €-2,13 | 46,3% | 312 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 962 | 1026 | €-1,80 | 43,7% | 154 | 212 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 948 | 1012 | +€1,03 | 44,1% | 208 | 69 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 932 | 996 | +€3,65 | 33,4% | 126 | 92 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 928 | 992 | +€0,31 | 42,1% | 169 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 900 | 964 | €-3,48 | 36,5% | 81 | 257 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 896 | 960 | +€4,10 | 41,7% | 70 | 146 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 891 | 955 | €-3,16 | 35,6% | 91 | 199 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 885 | 949 | €-13,53 | 28,7% | 207 | 149 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 878 | 942 | €-6,88 | 30,6% | 76 | 244 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 857 | 921 | €-10,54 | 27,5% | 70 | 243 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 798 | 862 | €-17,05 | 22,5% | 69 | 240 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
