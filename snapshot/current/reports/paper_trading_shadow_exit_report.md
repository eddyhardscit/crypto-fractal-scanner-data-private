# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T18:23:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **302**
- Scenari virtuali ancora attivi: **2924**
- Gruppi in attesa dell'uscita originale: **166**
- Gruppi con originale chiuso ma Shadow ancora attive: **136**
- Confronti completati: **9579**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 444 | 505 | +€7,94 | 48,5% | 121 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 444 | 505 | +€6,12 | 47,1% | 122 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 444 | 505 | +€4,08 | 46,5% | 122 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 444 | 505 | +€3,24 | 46,9% | 130 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 444 | 505 | +€2,10 | 45,7% | 117 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 436 | 497 | +€4,72 | 39,0% | 104 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 436 | 497 | +€3,22 | 38,4% | 96 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 436 | 497 | +€2,28 | 37,6% | 111 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 436 | 497 | +€1,85 | 38,4% | 76 | 45 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 435 | 496 | +€0,56 | 52,6% | 105 | 51 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 434 | 495 | +€1,01 | 36,0% | 51 | 82 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 427 | 488 | €-3,05 | 30,3% | 33 | 110 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 412 | 473 | €-4,01 | 26,8% | 38 | 110 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 409 | 470 | +€2,14 | 29,6% | 48 | 46 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 402 | 463 | +€5,86 | 48,2% | 40 | 80 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 398 | 459 | €-7,11 | 24,0% | 35 | 102 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 393 | 454 | €-6,86 | 28,0% | 84 | 52 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 367 | 428 | €-0,64 | 32,0% | 21 | 101 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 365 | 426 | +€3,98 | 34,0% | 20 | 53 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 354 | 414 | €-13,27 | 18,6% | 34 | 89 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
