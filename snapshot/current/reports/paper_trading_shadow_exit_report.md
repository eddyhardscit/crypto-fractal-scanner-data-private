# Block 3 — Shadow Exit Engine

Generato: 2026-08-05T07:24:11+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **11**
- Scenari virtuali ancora attivi: **0**
- Gruppi in attesa dell'uscita originale: **11**
- Gruppi con originale chiuso ma Shadow ancora attive: **0**
- Confronti completati: **121797**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3247 | 3313 | +€9,15 | 51,8% | 914 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3247 | 3313 | +€7,50 | 50,9% | 914 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3247 | 3313 | +€6,69 | 43,2% | 708 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3247 | 3313 | +€6,26 | 49,3% | 913 | 78 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3247 | 3313 | +€5,09 | 33,1% | 411 | 381 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3247 | 3313 | +€4,87 | 48,8% | 1017 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3247 | 3313 | +€4,84 | 42,7% | 684 | 126 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3247 | 3313 | +€4,63 | 49,2% | 856 | 138 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3247 | 3313 | +€4,51 | 41,2% | 776 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3247 | 3313 | +€4,18 | 41,8% | 599 | 215 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3247 | 3313 | +€3,79 | 35,6% | 198 | 622 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3247 | 3313 | +€2,29 | 40,1% | 517 | 371 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3247 | 3313 | €-0,33 | 31,5% | 368 | 692 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3247 | 3313 | €-1,01 | 28,9% | 311 | 824 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3247 | 3313 | €-1,07 | 39,7% | 400 | 732 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3247 | 3313 | €-1,44 | 45,7% | 670 | 490 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3247 | 3313 | €-3,75 | 33,2% | 547 | 707 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3247 | 3313 | €-4,54 | 31,8% | 187 | 998 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3247 | 3313 | €-5,37 | 27,2% | 260 | 907 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3247 | 3313 | €-8,70 | 22,6% | 260 | 1037 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
