# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T14:38:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **294**
- Scenari virtuali ancora attivi: **2844**
- Gruppi in attesa dell'uscita originale: **184**
- Gruppi con originale chiuso ma Shadow ancora attive: **110**
- Confronti completati: **11365**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 527 | 588 | +€8,00 | 46,3% | 137 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 527 | 588 | +€6,19 | 45,2% | 138 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 527 | 588 | +€4,23 | 44,4% | 140 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 527 | 588 | +€3,61 | 45,1% | 146 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 525 | 586 | +€2,47 | 43,7% | 134 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 525 | 586 | +€1,12 | 50,9% | 114 | 71 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 517 | 578 | +€4,12 | 36,0% | 119 | 18 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 517 | 578 | +€2,63 | 35,5% | 110 | 30 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 517 | 578 | +€2,26 | 34,8% | 126 | 18 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 517 | 578 | +€1,25 | 35,5% | 89 | 49 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 514 | 575 | +€0,45 | 33,2% | 62 | 88 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 513 | 574 | +€2,65 | 43,6% | 44 | 119 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 506 | 567 | €-2,70 | 30,2% | 22 | 158 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 503 | 564 | €-3,19 | 27,8% | 34 | 122 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 502 | 563 | +€0,80 | 26,1% | 50 | 63 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 494 | 555 | €-4,61 | 24,3% | 40 | 128 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 492 | 553 | €-8,25 | 21,3% | 36 | 133 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 478 | 539 | €-6,94 | 26,7% | 87 | 73 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 471 | 532 | €-1,67 | 28,8% | 21 | 96 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 447 | 507 | €-14,11 | 16,4% | 35 | 119 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
