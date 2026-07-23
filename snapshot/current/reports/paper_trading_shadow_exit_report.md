# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T02:23:42+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **274**
- Scenari virtuali ancora attivi: **2511**
- Gruppi in attesa dell'uscita originale: **157**
- Gruppi con originale chiuso ma Shadow ancora attive: **117**
- Confronti completati: **10559**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 484 | 545 | +€8,23 | 47,2% | 124 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 484 | 545 | +€6,47 | 46,1% | 124 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 484 | 545 | +€4,48 | 45,3% | 125 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 484 | 545 | +€3,67 | 45,7% | 133 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 484 | 545 | +€2,54 | 44,6% | 120 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 483 | 544 | €-0,31 | 50,9% | 110 | 60 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 480 | 541 | +€1,73 | 43,1% | 41 | 118 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 477 | 538 | +€4,80 | 37,7% | 106 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 477 | 538 | +€3,37 | 37,2% | 97 | 29 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 477 | 538 | +€2,54 | 36,4% | 113 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 477 | 538 | +€2,01 | 37,2% | 76 | 48 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 477 | 538 | +€1,10 | 34,8% | 51 | 87 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 477 | 538 | €-3,59 | 28,6% | 34 | 121 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 462 | 523 | €-5,05 | 24,9% | 40 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 456 | 517 | €-3,37 | 30,0% | 22 | 142 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 456 | 517 | €-8,32 | 21,9% | 36 | 124 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 451 | 512 | +€1,50 | 27,9% | 48 | 53 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 441 | 502 | €-7,34 | 26,7% | 87 | 62 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 425 | 486 | €-0,59 | 30,5% | 20 | 81 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 404 | 464 | €-13,61 | 17,2% | 35 | 103 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
