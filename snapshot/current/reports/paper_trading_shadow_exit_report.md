# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T13:08:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **269**
- Scenari virtuali ancora attivi: **3059**
- Gruppi in attesa dell'uscita originale: **169**
- Gruppi con originale chiuso ma Shadow ancora attive: **100**
- Confronti completati: **8616**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 394 | 453 | +€7,81 | 47,2% | 106 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 394 | 453 | +€5,87 | 45,9% | 105 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 394 | 453 | +€3,94 | 45,3% | 106 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 394 | 453 | +€3,22 | 45,3% | 115 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 394 | 453 | +€2,16 | 44,4% | 101 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 391 | 450 | €-0,57 | 52,0% | 92 | 48 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 385 | 444 | +€2,33 | 36,9% | 89 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 385 | 444 | +€1,33 | 36,3% | 81 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 385 | 444 | +€0,43 | 36,3% | 62 | 44 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 385 | 444 | +€0,09 | 35,4% | 96 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 384 | 443 | +€6,47 | 49,9% | 39 | 71 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 380 | 439 | €-3,48 | 27,8% | 32 | 100 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 371 | 430 | €-0,40 | 28,6% | 46 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 361 | 420 | €-1,26 | 32,4% | 37 | 71 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 357 | 415 | €-7,59 | 28,9% | 71 | 50 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 351 | 410 | +€4,10 | 35,1% | 19 | 49 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 351 | 410 | €-7,42 | 23,4% | 27 | 101 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 339 | 398 | €-6,02 | 30,2% | 20 | 97 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 326 | 385 | €-11,95 | 21,6% | 24 | 91 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 318 | 375 | €-14,34 | 20,3% | 23 | 87 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
