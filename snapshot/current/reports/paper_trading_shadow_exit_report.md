# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T00:40:13+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **546**
- Scenari virtuali ancora attivi: **14249**
- Gruppi in attesa dell'uscita originale: **318**
- Gruppi con originale chiuso ma Shadow ancora attive: **228**
- Confronti completati: **173281**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4324 | 4390 | +€7,80 | 49,8% | 1157 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4324 | 4390 | +€6,83 | 48,8% | 1149 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4324 | 4390 | +€6,30 | 42,1% | 901 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4324 | 4390 | +€4,73 | 41,3% | 869 | 171 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4324 | 4390 | +€4,20 | 40,0% | 998 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4324 | 4390 | +€4,18 | 47,0% | 1285 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4321 | 4387 | +€5,51 | 47,0% | 1163 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4321 | 4387 | +€4,16 | 47,4% | 1091 | 171 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4314 | 4380 | +€3,91 | 40,5% | 762 | 277 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4304 | 4370 | +€4,90 | 32,1% | 540 | 446 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4292 | 4358 | +€2,33 | 39,5% | 638 | 449 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4291 | 4357 | +€0,02 | 45,7% | 826 | 616 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4272 | 4338 | +€0,62 | 32,7% | 453 | 802 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4264 | 4330 | +€4,36 | 35,1% | 253 | 705 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4244 | 4310 | €-0,38 | 30,2% | 327 | 1008 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4233 | 4299 | +€0,02 | 39,8% | 470 | 864 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4225 | 4291 | €-3,74 | 32,9% | 640 | 897 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4214 | 4280 | €-4,76 | 27,2% | 276 | 1133 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4192 | 4258 | €-8,27 | 23,0% | 276 | 1275 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4182 | 4248 | €-5,53 | 30,3% | 209 | 1221 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
