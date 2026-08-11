# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T08:10:14+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **276**
- Scenari virtuali ancora attivi: **11040**
- Gruppi in attesa dell'uscita originale: **248**
- Gruppi con originale chiuso ma Shadow ancora attive: **28**
- Confronti completati: **126096**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3347 | 3413 | +€8,54 | 51,4% | 953 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3347 | 3413 | +€7,26 | 50,5% | 931 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3347 | 3413 | +€6,41 | 43,2% | 739 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3347 | 3413 | +€5,97 | 48,9% | 929 | 108 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3347 | 3413 | +€4,92 | 33,3% | 432 | 386 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3347 | 3413 | +€4,71 | 42,7% | 693 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3347 | 3413 | +€4,31 | 48,5% | 1056 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3347 | 3413 | +€4,19 | 41,2% | 807 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3347 | 3413 | +€3,97 | 41,7% | 607 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3337 | 3403 | +€3,80 | 35,9% | 207 | 627 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3337 | 3403 | €-1,31 | 45,9% | 677 | 505 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3319 | 3385 | +€4,68 | 49,2% | 868 | 143 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3319 | 3385 | +€2,40 | 40,3% | 520 | 380 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3319 | 3385 | €-0,19 | 31,9% | 370 | 702 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3319 | 3385 | €-0,87 | 29,2% | 314 | 840 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3319 | 3385 | €-0,90 | 40,0% | 404 | 740 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3319 | 3385 | €-3,56 | 33,2% | 559 | 718 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3319 | 3385 | €-4,32 | 32,2% | 191 | 1009 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3319 | 3385 | €-5,13 | 27,7% | 263 | 918 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3319 | 3385 | €-8,39 | 23,1% | 263 | 1051 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
