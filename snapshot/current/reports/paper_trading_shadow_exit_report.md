# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T10:10:15+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **301**
- Scenari virtuali ancora attivi: **11245**
- Gruppi in attesa dell'uscita originale: **269**
- Gruppi con originale chiuso ma Shadow ancora attive: **32**
- Confronti completati: **126771**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3361 | 3427 | +€8,43 | 51,2% | 957 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3361 | 3427 | +€7,17 | 50,3% | 935 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3361 | 3427 | +€6,33 | 43,0% | 743 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3361 | 3427 | +€5,88 | 48,7% | 933 | 108 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3361 | 3427 | +€4,87 | 33,2% | 436 | 386 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3361 | 3427 | +€4,65 | 42,6% | 697 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3361 | 3427 | +€4,21 | 48,4% | 1060 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3361 | 3427 | +€4,12 | 41,1% | 811 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3361 | 3427 | +€3,91 | 41,6% | 611 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3361 | 3427 | +€3,85 | 36,0% | 207 | 627 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3360 | 3426 | €-1,28 | 45,9% | 680 | 515 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3343 | 3409 | +€4,48 | 48,9% | 872 | 153 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3343 | 3409 | +€2,23 | 40,1% | 524 | 390 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3330 | 3396 | €-3,58 | 33,2% | 560 | 718 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3329 | 3395 | €-0,18 | 31,8% | 370 | 702 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3329 | 3395 | €-0,86 | 29,1% | 314 | 840 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3329 | 3395 | €-0,90 | 39,9% | 404 | 740 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3329 | 3395 | €-4,30 | 32,2% | 191 | 1009 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3329 | 3395 | €-5,11 | 27,7% | 263 | 918 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3329 | 3395 | €-8,36 | 23,1% | 263 | 1051 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
