# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T12:39:13+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **383**
- Scenari virtuali ancora attivi: **8904**
- Gruppi in attesa dell'uscita originale: **233**
- Gruppi con originale chiuso ma Shadow ancora attive: **150**
- Confronti completati: **163579**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4101 | 4167 | +€8,46 | 50,3% | 1067 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4101 | 4167 | +€7,51 | 49,3% | 1055 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4101 | 4167 | +€6,74 | 42,6% | 838 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4101 | 4167 | +€6,18 | 47,5% | 1066 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4101 | 4167 | +€5,14 | 42,0% | 794 | 165 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4101 | 4167 | +€4,91 | 40,9% | 913 | 94 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4101 | 4167 | +€4,88 | 47,8% | 1003 | 166 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4101 | 4167 | +€4,80 | 47,6% | 1182 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4101 | 4167 | +€4,30 | 41,3% | 701 | 260 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4100 | 4166 | +€2,66 | 40,1% | 599 | 429 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4093 | 4159 | +€1,09 | 33,2% | 414 | 780 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4091 | 4157 | €-0,29 | 30,5% | 327 | 972 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4089 | 4155 | €-4,89 | 27,4% | 276 | 1119 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4076 | 4142 | €-0,21 | 46,0% | 803 | 575 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4074 | 4140 | €-0,71 | 39,4% | 460 | 863 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4066 | 4132 | €-3,73 | 32,7% | 604 | 887 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4061 | 4127 | €-8,46 | 23,2% | 276 | 1253 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4058 | 4124 | +€5,29 | 32,7% | 486 | 423 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4029 | 4095 | +€4,43 | 35,6% | 236 | 677 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4027 | 4093 | €-5,27 | 31,1% | 209 | 1171 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
