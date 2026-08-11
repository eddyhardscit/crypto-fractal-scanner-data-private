# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T12:10:16+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **327**
- Scenari virtuali ancora attivi: **11845**
- Gruppi in attesa dell'uscita originale: **270**
- Gruppi con originale chiuso ma Shadow ancora attive: **57**
- Confronti completati: **127584**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3389 | 3455 | +€8,18 | 51,1% | 970 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3389 | 3455 | +€6,91 | 50,0% | 955 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3389 | 3455 | +€6,16 | 43,0% | 756 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3389 | 3455 | +€5,63 | 48,5% | 953 | 108 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3389 | 3455 | +€4,47 | 42,4% | 717 | 153 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3389 | 3455 | +€4,01 | 41,1% | 824 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3389 | 3455 | +€3,92 | 48,1% | 1080 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3389 | 3455 | +€3,70 | 41,4% | 631 | 245 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3380 | 3446 | €-1,30 | 45,8% | 691 | 515 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3377 | 3443 | +€4,80 | 33,1% | 440 | 386 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3371 | 3437 | +€4,20 | 48,7% | 892 | 153 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3371 | 3437 | +€2,00 | 39,9% | 544 | 390 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3368 | 3434 | +€3,82 | 35,9% | 211 | 627 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3339 | 3405 | €-0,88 | 40,0% | 404 | 740 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3333 | 3399 | €-3,58 | 33,2% | 560 | 718 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3332 | 3398 | €-0,18 | 31,8% | 370 | 702 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3332 | 3398 | €-0,86 | 29,1% | 314 | 840 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3332 | 3398 | €-4,30 | 32,1% | 191 | 1009 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3332 | 3398 | €-5,10 | 27,6% | 263 | 918 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3332 | 3398 | €-8,35 | 23,1% | 263 | 1051 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
