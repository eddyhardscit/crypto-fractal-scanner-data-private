# Block 3 — Shadow Exit Engine

Generato: 2026-08-06T00:54:12+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **14**
- Scenari virtuali ancora attivi: **12**
- Gruppi in attesa dell'uscita originale: **11**
- Gruppi con originale chiuso ma Shadow ancora attive: **3**
- Confronti completati: **121935**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3250 | 3316 | +€9,14 | 51,8% | 916 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3250 | 3316 | +€7,49 | 50,9% | 916 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3250 | 3316 | +€6,68 | 43,2% | 710 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3250 | 3316 | +€6,25 | 49,3% | 916 | 78 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3250 | 3316 | +€5,09 | 33,1% | 411 | 381 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3250 | 3316 | +€4,87 | 48,8% | 1019 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3250 | 3316 | +€4,83 | 42,7% | 686 | 126 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3250 | 3316 | +€4,62 | 49,2% | 858 | 138 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3250 | 3316 | +€4,50 | 41,2% | 778 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3250 | 3316 | +€4,17 | 41,8% | 601 | 215 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3250 | 3316 | +€3,80 | 35,7% | 198 | 622 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3250 | 3316 | +€2,29 | 40,0% | 519 | 371 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3250 | 3316 | €-0,33 | 31,5% | 368 | 694 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3250 | 3316 | €-1,02 | 28,9% | 311 | 827 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3250 | 3316 | €-1,06 | 39,7% | 400 | 732 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3250 | 3316 | €-1,44 | 45,7% | 670 | 492 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3250 | 3316 | €-3,75 | 33,1% | 547 | 710 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3250 | 3316 | €-5,37 | 27,2% | 260 | 910 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3250 | 3316 | €-8,69 | 22,6% | 260 | 1040 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3247 | 3313 | €-4,54 | 31,8% | 187 | 998 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
