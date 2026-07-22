# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T14:23:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **268**
- Scenari virtuali ancora attivi: **3012**
- Gruppi in attesa dell'uscita originale: **164**
- Gruppi con originale chiuso ma Shadow ancora attive: **104**
- Confronti completati: **8708**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 399 | 460 | +€8,36 | 47,8% | 106 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 399 | 460 | +€6,40 | 46,5% | 105 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 399 | 460 | +€4,47 | 45,9% | 106 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 399 | 460 | +€3,71 | 45,9% | 115 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 399 | 460 | +€2,67 | 45,0% | 101 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 395 | 456 | €-0,24 | 52,2% | 92 | 50 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 386 | 447 | +€2,82 | 37,1% | 89 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 386 | 447 | +€1,79 | 36,5% | 81 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 386 | 447 | +€0,89 | 36,5% | 62 | 44 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 386 | 447 | +€0,54 | 35,6% | 96 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 385 | 446 | +€6,66 | 50,0% | 39 | 71 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 383 | 444 | €-2,91 | 28,4% | 32 | 100 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 372 | 433 | +€0,19 | 28,9% | 46 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 364 | 425 | €-0,71 | 32,7% | 37 | 72 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 362 | 422 | €-7,46 | 28,4% | 71 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 352 | 413 | +€4,44 | 35,1% | 19 | 49 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 352 | 413 | €-6,95 | 23,7% | 27 | 101 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 341 | 402 | €-5,80 | 30,3% | 20 | 98 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 327 | 388 | €-11,86 | 21,4% | 24 | 91 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 319 | 378 | €-14,23 | 20,1% | 23 | 87 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
