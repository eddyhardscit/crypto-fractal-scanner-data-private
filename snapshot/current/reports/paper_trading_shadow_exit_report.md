# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T07:08:52+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **467**
- Scenari virtuali ancora attivi: **4386**
- Gruppi in attesa dell'uscita originale: **222**
- Gruppi con originale chiuso ma Shadow ancora attive: **245**
- Confronti completati: **19842**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 985 | 1049 | +€3,40 | 49,4% | 313 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 985 | 1049 | €-1,33 | 47,5% | 336 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 984 | 1048 | +€1,38 | 48,2% | 320 | 8 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 982 | 1046 | €-3,73 | 47,8% | 283 | 125 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 974 | 1038 | €-0,64 | 47,3% | 318 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 968 | 1032 | +€4,63 | 45,2% | 260 | 25 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 968 | 1032 | +€2,47 | 42,6% | 288 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 967 | 1031 | €-1,94 | 46,3% | 309 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 953 | 1017 | €-1,67 | 43,9% | 151 | 212 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 944 | 1008 | +€2,56 | 44,6% | 242 | 35 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 931 | 995 | +€1,41 | 44,7% | 205 | 61 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 924 | 988 | +€3,71 | 33,5% | 123 | 92 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 921 | 985 | +€0,51 | 42,3% | 166 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 896 | 960 | €-3,50 | 36,7% | 81 | 257 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 888 | 952 | +€4,08 | 41,8% | 70 | 146 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 888 | 952 | €-3,17 | 35,7% | 91 | 199 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 879 | 943 | €-13,31 | 28,5% | 204 | 149 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 875 | 939 | €-6,90 | 30,7% | 76 | 244 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 854 | 918 | €-10,57 | 27,6% | 70 | 243 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 795 | 859 | €-17,11 | 22,6% | 69 | 240 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
