# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T13:39:43+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **411**
- Scenari virtuali ancora attivi: **9089**
- Gruppi in attesa dell'uscita originale: **256**
- Gruppi con originale chiuso ma Shadow ancora attive: **155**
- Confronti completati: **163897**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4109 | 4175 | +€8,48 | 50,3% | 1069 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4109 | 4175 | +€7,53 | 49,3% | 1057 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4109 | 4175 | +€6,20 | 47,6% | 1068 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4109 | 4175 | +€4,90 | 47,8% | 1005 | 166 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4109 | 4175 | +€4,83 | 47,7% | 1184 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4105 | 4171 | +€6,74 | 42,6% | 838 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4105 | 4171 | +€5,14 | 42,1% | 794 | 165 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4105 | 4171 | +€4,91 | 40,9% | 913 | 94 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4105 | 4171 | +€4,29 | 41,3% | 701 | 260 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4104 | 4170 | +€2,66 | 40,1% | 601 | 429 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4098 | 4164 | +€1,10 | 33,3% | 414 | 780 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4095 | 4161 | €-0,29 | 30,4% | 327 | 974 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4092 | 4158 | €-4,90 | 27,4% | 276 | 1120 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4090 | 4156 | €-0,22 | 46,1% | 809 | 575 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4083 | 4149 | €-0,69 | 39,5% | 462 | 863 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4072 | 4138 | €-3,71 | 32,7% | 604 | 887 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4063 | 4129 | €-8,46 | 23,2% | 276 | 1253 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4060 | 4126 | +€5,29 | 32,7% | 486 | 423 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4032 | 4098 | +€4,39 | 35,5% | 236 | 678 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4030 | 4096 | €-5,29 | 31,1% | 209 | 1172 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
