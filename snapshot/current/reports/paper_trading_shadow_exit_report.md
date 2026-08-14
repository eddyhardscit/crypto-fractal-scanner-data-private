# Block 3 — Shadow Exit Engine

Generato: 2026-08-14T02:08:01+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **549**
- Scenari virtuali ancora attivi: **10111**
- Gruppi in attesa dell'uscita originale: **359**
- Gruppi con originale chiuso ma Shadow ancora attive: **190**
- Confronti completati: **184354**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4525 | 4591 | +€8,15 | 50,8% | 1185 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4525 | 4591 | +€7,18 | 49,8% | 1177 | 58 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4525 | 4591 | +€4,38 | 47,9% | 1323 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4525 | 4591 | €-0,61 | 46,1% | 846 | 666 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4525 | 4591 | €-0,93 | 40,3% | 482 | 957 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4524 | 4590 | +€5,87 | 48,0% | 1191 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4523 | 4589 | +€4,52 | 48,4% | 1119 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4519 | 4585 | €-5,20 | 32,1% | 209 | 1322 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4517 | 4583 | +€6,75 | 43,3% | 924 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4517 | 4583 | +€5,23 | 42,6% | 889 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4517 | 4583 | +€4,51 | 41,1% | 1032 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4510 | 4576 | +€5,24 | 33,3% | 557 | 454 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4509 | 4575 | +€4,41 | 41,8% | 781 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4509 | 4575 | +€2,65 | 40,7% | 658 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4501 | 4567 | +€5,23 | 36,9% | 261 | 713 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4498 | 4564 | +€0,89 | 34,1% | 478 | 833 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4490 | 4556 | €-0,09 | 31,8% | 345 | 1049 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4449 | 4515 | €-4,77 | 28,5% | 288 | 1193 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4447 | 4513 | €-3,91 | 33,9% | 662 | 937 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4420 | 4486 | €-8,69 | 24,3% | 288 | 1339 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
