# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T13:38:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **277**
- Scenari virtuali ancora attivi: **2548**
- Gruppi in attesa dell'uscita originale: **176**
- Gruppi con originale chiuso ma Shadow ancora attive: **101**
- Confronti completati: **11085**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 508 | 569 | +€9,26 | 47,6% | 125 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 508 | 569 | +€7,47 | 46,6% | 126 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 508 | 569 | +€5,50 | 45,7% | 128 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 508 | 569 | +€4,81 | 46,4% | 134 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 507 | 568 | +€3,65 | 44,9% | 123 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 506 | 567 | +€2,68 | 44,1% | 44 | 119 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 506 | 567 | +€1,10 | 52,0% | 113 | 60 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 499 | 560 | +€2,92 | 35,9% | 114 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 499 | 560 | €-2,73 | 30,5% | 22 | 158 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 498 | 559 | +€5,00 | 37,0% | 107 | 18 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 498 | 559 | +€3,58 | 36,5% | 98 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 498 | 559 | +€2,25 | 36,5% | 77 | 49 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 497 | 558 | +€1,44 | 34,2% | 51 | 88 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 497 | 558 | €-3,23 | 28,1% | 34 | 122 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 488 | 549 | €-4,66 | 24,6% | 40 | 128 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 486 | 547 | €-8,35 | 21,6% | 36 | 133 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 484 | 545 | +€0,89 | 27,0% | 49 | 63 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 471 | 532 | €-6,85 | 27,1% | 87 | 72 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 460 | 521 | €-2,08 | 28,8% | 20 | 95 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 440 | 500 | €-14,10 | 16,6% | 35 | 118 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
