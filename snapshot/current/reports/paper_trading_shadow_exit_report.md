# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T06:55:24+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **489**
- Scenari virtuali ancora attivi: **11506**
- Gruppi in attesa dell'uscita originale: **301**
- Gruppi con originale chiuso ma Shadow ancora attive: **188**
- Confronti completati: **180193**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4445 | 4511 | +€8,06 | 50,3% | 1168 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4445 | 4511 | +€7,11 | 49,3% | 1160 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4445 | 4511 | +€6,57 | 42,7% | 911 | 102 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4445 | 4511 | +€4,51 | 40,7% | 1009 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4445 | 4511 | +€4,50 | 47,6% | 1296 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4443 | 4509 | +€5,03 | 41,9% | 877 | 171 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4441 | 4507 | €-0,35 | 46,0% | 833 | 649 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4439 | 4505 | +€5,85 | 47,7% | 1168 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4439 | 4505 | +€4,52 | 48,0% | 1096 | 171 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4439 | 4505 | +€4,28 | 41,3% | 766 | 279 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4439 | 4505 | +€2,55 | 40,2% | 643 | 470 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4434 | 4500 | +€5,28 | 33,1% | 544 | 446 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4426 | 4492 | €-0,69 | 40,1% | 475 | 925 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4425 | 4491 | +€5,15 | 36,6% | 254 | 705 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4420 | 4486 | +€0,86 | 33,5% | 457 | 827 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4420 | 4486 | €-0,06 | 31,4% | 330 | 1042 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4391 | 4457 | €-4,74 | 28,1% | 277 | 1189 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4365 | 4431 | €-3,81 | 33,6% | 641 | 930 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4356 | 4422 | €-8,72 | 23,8% | 277 | 1332 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4313 | 4379 | €-5,73 | 31,0% | 209 | 1246 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
