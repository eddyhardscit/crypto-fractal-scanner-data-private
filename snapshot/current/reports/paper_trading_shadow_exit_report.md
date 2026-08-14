# Block 3 — Shadow Exit Engine

Generato: 2026-08-14T06:07:57+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **595**
- Scenari virtuali ancora attivi: **10584**
- Gruppi in attesa dell'uscita originale: **366**
- Gruppi con originale chiuso ma Shadow ancora attive: **229**
- Confronti completati: **187144**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4589 | 4655 | +€8,15 | 51,0% | 1201 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4589 | 4655 | +€7,17 | 50,1% | 1193 | 58 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4589 | 4655 | +€4,43 | 48,2% | 1339 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4588 | 4654 | +€5,87 | 48,3% | 1207 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4587 | 4653 | +€4,52 | 48,6% | 1135 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4587 | 4653 | €-0,42 | 46,6% | 852 | 667 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4582 | 4648 | €-0,64 | 40,9% | 484 | 957 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4582 | 4648 | €-4,69 | 32,6% | 209 | 1329 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4581 | 4647 | +€6,91 | 43,8% | 933 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4581 | 4647 | +€5,39 | 43,1% | 898 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4581 | 4647 | +€4,72 | 41,6% | 1041 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4574 | 4640 | +€5,62 | 34,0% | 558 | 454 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4573 | 4639 | +€4,54 | 42,2% | 796 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4573 | 4639 | +€2,76 | 41,0% | 674 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4563 | 4629 | +€5,64 | 37,6% | 261 | 713 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4556 | 4622 | +€1,13 | 34,8% | 481 | 833 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4553 | 4619 | +€0,23 | 32,6% | 347 | 1049 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4537 | 4603 | €-4,33 | 29,4% | 294 | 1205 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4485 | 4551 | €-3,77 | 34,1% | 672 | 938 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4448 | 4514 | €-8,50 | 24,7% | 288 | 1340 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
