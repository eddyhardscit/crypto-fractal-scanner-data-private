# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T00:23:42+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **267**
- Scenari virtuali ancora attivi: **2466**
- Gruppi in attesa dell'uscita originale: **154**
- Gruppi con originale chiuso ma Shadow ancora attive: **113**
- Confronti completati: **10317**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 472 | 533 | +€8,32 | 47,3% | 123 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 472 | 533 | +€6,53 | 46,2% | 123 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 472 | 533 | +€4,53 | 45,4% | 124 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 472 | 533 | +€3,67 | 45,8% | 132 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 472 | 533 | +€2,56 | 44,7% | 119 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 472 | 533 | €-0,84 | 50,1% | 109 | 60 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 468 | 529 | +€1,73 | 43,5% | 41 | 115 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 465 | 526 | +€4,66 | 37,6% | 105 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 465 | 526 | +€3,18 | 37,1% | 96 | 29 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 465 | 526 | +€2,33 | 36,3% | 112 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 464 | 525 | +€1,86 | 37,1% | 76 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 462 | 523 | +€1,04 | 34,8% | 51 | 83 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 456 | 517 | €-2,95 | 29,0% | 33 | 111 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 450 | 511 | €-4,94 | 24,9% | 39 | 121 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 448 | 509 | €-3,47 | 30,1% | 22 | 142 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 444 | 505 | €-8,28 | 21,8% | 35 | 122 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 441 | 502 | +€1,34 | 27,9% | 48 | 53 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 429 | 490 | €-7,28 | 26,7% | 85 | 61 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 417 | 478 | €-0,64 | 30,5% | 20 | 81 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 392 | 452 | €-13,71 | 17,0% | 34 | 101 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
