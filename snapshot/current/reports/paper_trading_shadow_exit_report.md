# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T21:08:33+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **581**
- Scenari virtuali ancora attivi: **11182**
- Gruppi in attesa dell'uscita originale: **375**
- Gruppi con originale chiuso ma Shadow ancora attive: **206**
- Confronti completati: **181956**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4476 | 4542 | +€8,06 | 50,4% | 1181 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4476 | 4542 | +€7,07 | 49,3% | 1173 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4476 | 4542 | +€6,63 | 42,8% | 924 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4476 | 4542 | +€5,11 | 42,1% | 885 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4476 | 4542 | +€4,37 | 40,6% | 1032 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4476 | 4542 | +€4,26 | 47,4% | 1319 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4475 | 4541 | +€5,76 | 47,6% | 1187 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4474 | 4540 | +€4,42 | 47,9% | 1115 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4469 | 4535 | +€5,24 | 33,1% | 557 | 447 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4468 | 4534 | +€4,30 | 41,4% | 777 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4468 | 4534 | +€2,54 | 40,2% | 654 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4466 | 4532 | €-0,38 | 46,0% | 846 | 649 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4466 | 4532 | €-0,71 | 40,1% | 482 | 940 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4460 | 4526 | +€5,21 | 36,7% | 261 | 706 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4457 | 4523 | +€0,79 | 33,6% | 474 | 833 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4449 | 4515 | €-0,21 | 31,3% | 345 | 1049 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4445 | 4511 | €-5,01 | 32,0% | 209 | 1292 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4412 | 4478 | €-4,91 | 28,1% | 288 | 1193 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4399 | 4465 | €-4,05 | 33,5% | 662 | 934 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4380 | 4446 | €-8,86 | 23,9% | 288 | 1336 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
