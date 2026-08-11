# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T14:11:15+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **336**
- Scenari virtuali ancora attivi: **10768**
- Gruppi in attesa dell'uscita originale: **270**
- Gruppi con originale chiuso ma Shadow ancora attive: **66**
- Confronti completati: **130742**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3448 | 3514 | +€7,96 | 50,7% | 986 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3448 | 3514 | +€6,83 | 49,7% | 971 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3448 | 3514 | +€6,16 | 42,7% | 772 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3448 | 3514 | +€5,51 | 48,1% | 971 | 108 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3448 | 3514 | +€4,44 | 42,1% | 733 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3448 | 3514 | +€3,96 | 40,8% | 840 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3448 | 3514 | +€3,72 | 47,7% | 1098 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3448 | 3514 | +€3,63 | 41,1% | 647 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3436 | 3502 | +€4,92 | 32,9% | 447 | 386 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3436 | 3502 | +€3,48 | 35,7% | 219 | 636 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3435 | 3501 | €-0,13 | 32,0% | 378 | 729 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3432 | 3498 | €-1,13 | 29,2% | 322 | 872 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3430 | 3496 | +€4,06 | 48,3% | 910 | 153 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3430 | 3496 | +€1,90 | 39,6% | 562 | 390 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3430 | 3496 | €-1,43 | 45,7% | 699 | 524 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3407 | 3473 | €-0,77 | 40,1% | 412 | 749 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3404 | 3470 | €-5,32 | 27,6% | 271 | 934 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3390 | 3456 | €-4,08 | 32,8% | 568 | 734 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3389 | 3455 | €-8,79 | 22,8% | 271 | 1067 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3382 | 3448 | €-4,61 | 31,8% | 199 | 1018 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
