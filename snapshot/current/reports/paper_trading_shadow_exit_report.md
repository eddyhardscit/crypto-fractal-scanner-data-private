# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T20:23:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **272**
- Scenari virtuali ancora attivi: **2588**
- Gruppi in attesa dell'uscita originale: **154**
- Gruppi con originale chiuso ma Shadow ancora attive: **118**
- Confronti completati: **10218**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 470 | 531 | +€8,35 | 47,5% | 123 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 470 | 531 | +€6,56 | 46,3% | 123 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 470 | 531 | +€4,54 | 45,6% | 124 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 470 | 531 | +€3,69 | 46,0% | 132 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 470 | 531 | +€2,57 | 44,8% | 119 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 469 | 530 | €-0,89 | 50,0% | 109 | 60 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 463 | 524 | +€4,68 | 37,8% | 105 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 463 | 524 | +€2,34 | 36,5% | 112 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 462 | 523 | +€3,21 | 37,3% | 96 | 28 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 462 | 523 | +€1,87 | 37,3% | 76 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 460 | 521 | +€1,04 | 34,9% | 51 | 83 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 454 | 515 | €-2,96 | 29,1% | 33 | 111 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 451 | 512 | +€2,21 | 43,8% | 41 | 106 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 448 | 509 | €-4,96 | 25,0% | 39 | 121 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 434 | 495 | +€1,93 | 28,3% | 48 | 48 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 434 | 495 | €-7,95 | 22,2% | 35 | 114 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 426 | 487 | €-7,12 | 26,9% | 85 | 60 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 425 | 486 | €-3,19 | 30,0% | 22 | 128 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 409 | 470 | €-0,11 | 30,9% | 20 | 76 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 389 | 449 | €-13,58 | 17,1% | 34 | 100 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
