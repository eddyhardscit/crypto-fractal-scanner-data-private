# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T20:40:45+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **391**
- Scenari virtuali ancora attivi: **8445**
- Gruppi in attesa dell'uscita originale: **230**
- Gruppi con originale chiuso ma Shadow ancora attive: **161**
- Confronti completati: **170502**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4246 | 4312 | +€8,89 | 50,6% | 1086 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4246 | 4312 | +€7,96 | 49,6% | 1078 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4246 | 4312 | +€6,75 | 42,3% | 850 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4246 | 4312 | +€6,61 | 47,7% | 1099 | 114 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4246 | 4312 | +€5,34 | 47,8% | 1212 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4246 | 4312 | +€5,31 | 48,1% | 1025 | 167 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4246 | 4312 | +€5,15 | 41,8% | 806 | 169 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4246 | 4312 | +€5,01 | 40,7% | 925 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4246 | 4312 | +€4,27 | 40,9% | 723 | 264 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4244 | 4310 | +€0,37 | 46,1% | 809 | 593 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4240 | 4306 | +€2,69 | 39,9% | 603 | 442 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4240 | 4306 | +€1,07 | 32,9% | 426 | 802 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4226 | 4292 | +€5,33 | 32,6% | 486 | 446 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4211 | 4277 | €-0,24 | 30,3% | 327 | 985 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4205 | 4271 | €-4,76 | 27,1% | 276 | 1132 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4191 | 4257 | €-3,18 | 33,1% | 612 | 896 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4186 | 4252 | €-8,27 | 23,0% | 276 | 1274 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4184 | 4250 | €-0,45 | 39,3% | 462 | 864 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4162 | 4228 | €-5,52 | 30,4% | 209 | 1208 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4157 | 4223 | +€3,93 | 34,9% | 236 | 704 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
