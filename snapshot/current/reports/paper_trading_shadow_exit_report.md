# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T21:40:36+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **392**
- Scenari virtuali ancora attivi: **7916**
- Gruppi in attesa dell'uscita originale: **201**
- Gruppi con originale chiuso ma Shadow ancora attive: **191**
- Confronti completati: **171893**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4283 | 4349 | +€8,32 | 50,2% | 1120 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4283 | 4349 | +€7,37 | 49,2% | 1112 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4283 | 4349 | +€6,00 | 47,3% | 1133 | 114 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4283 | 4349 | +€4,75 | 47,4% | 1248 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4283 | 4349 | +€4,68 | 47,7% | 1061 | 167 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4283 | 4349 | +€4,61 | 40,4% | 961 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4280 | 4346 | +€6,71 | 42,4% | 861 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4280 | 4346 | +€5,03 | 41,6% | 832 | 169 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4280 | 4346 | +€4,11 | 40,7% | 749 | 264 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4274 | 4340 | +€2,44 | 39,7% | 631 | 442 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4265 | 4331 | +€0,69 | 32,7% | 450 | 802 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4263 | 4329 | +€5,13 | 32,4% | 512 | 446 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4258 | 4324 | +€0,25 | 45,9% | 820 | 595 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4240 | 4306 | €-0,38 | 30,2% | 327 | 1008 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4220 | 4286 | +€4,39 | 35,2% | 242 | 705 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4216 | 4282 | €-3,67 | 32,9% | 636 | 896 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4212 | 4278 | €-0,05 | 39,5% | 470 | 864 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4210 | 4276 | €-4,76 | 27,2% | 276 | 1133 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4187 | 4253 | €-8,27 | 23,0% | 276 | 1274 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4163 | 4229 | €-5,52 | 30,4% | 209 | 1208 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
