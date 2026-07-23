# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T01:23:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **264**
- Scenari virtuali ancora attivi: **2356**
- Gruppi in attesa dell'uscita originale: **149**
- Gruppi con originale chiuso ma Shadow ancora attive: **115**
- Confronti completati: **10479**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 480 | 541 | +€8,14 | 46,8% | 124 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 480 | 541 | +€6,38 | 45,7% | 124 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 480 | 541 | +€4,39 | 44,9% | 125 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 480 | 541 | +€3,55 | 45,3% | 133 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 480 | 541 | +€2,44 | 44,2% | 120 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 479 | 540 | €-0,44 | 50,7% | 109 | 60 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 478 | 539 | +€1,70 | 42,9% | 41 | 118 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 473 | 534 | +€4,60 | 37,3% | 106 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 473 | 534 | +€2,32 | 36,0% | 113 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 472 | 533 | +€3,19 | 36,8% | 96 | 29 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 472 | 533 | +€1,86 | 36,8% | 76 | 47 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 472 | 533 | +€0,98 | 34,3% | 51 | 86 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 472 | 533 | €-3,54 | 28,3% | 33 | 120 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 457 | 518 | €-5,02 | 24,5% | 39 | 122 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 454 | 515 | €-3,42 | 29,7% | 22 | 142 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 451 | 512 | €-8,31 | 21,5% | 35 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 448 | 509 | +€1,32 | 27,5% | 48 | 53 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 437 | 498 | €-7,46 | 26,3% | 86 | 62 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 423 | 484 | €-0,63 | 30,2% | 20 | 81 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 399 | 459 | €-13,66 | 16,8% | 34 | 102 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
