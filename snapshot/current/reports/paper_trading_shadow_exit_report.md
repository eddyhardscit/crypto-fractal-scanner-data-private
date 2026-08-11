# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T09:10:33+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **292**
- Scenari virtuali ancora attivi: **11307**
- Gruppi in attesa dell'uscita originale: **264**
- Gruppi con originale chiuso ma Shadow ancora attive: **28**
- Confronti completati: **126277**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3350 | 3416 | +€8,54 | 51,4% | 953 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3350 | 3416 | +€7,26 | 50,5% | 931 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3350 | 3416 | +€6,40 | 43,2% | 739 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3350 | 3416 | +€5,97 | 48,9% | 929 | 108 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3350 | 3416 | +€4,92 | 33,3% | 432 | 386 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3350 | 3416 | +€4,71 | 42,7% | 693 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3350 | 3416 | +€4,31 | 48,5% | 1056 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3350 | 3416 | +€4,19 | 41,2% | 807 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3350 | 3416 | +€3,97 | 41,7% | 607 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3341 | 3407 | €-1,30 | 45,9% | 677 | 506 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3340 | 3406 | +€3,80 | 35,9% | 207 | 627 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3332 | 3398 | +€4,57 | 49,1% | 868 | 153 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3332 | 3398 | +€2,31 | 40,2% | 520 | 390 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3322 | 3388 | €-0,18 | 31,9% | 370 | 702 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3322 | 3388 | €-0,86 | 29,2% | 314 | 840 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3322 | 3388 | €-0,90 | 40,0% | 404 | 740 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3322 | 3388 | €-3,56 | 33,3% | 559 | 718 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3322 | 3388 | €-4,31 | 32,2% | 191 | 1009 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3322 | 3388 | €-5,12 | 27,7% | 263 | 918 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3322 | 3388 | €-8,37 | 23,1% | 263 | 1051 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
