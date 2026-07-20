# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T13:23:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **103**
- Scenari virtuali ancora attivi: **1204**
- Gruppi in attesa dell'uscita originale: **62**
- Gruppi con originale chiuso ma Shadow ancora attive: **41**
- Confronti completati: **1751**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 61 | 96 | +€7,78 | 46,9% | 23 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 61 | 96 | +€6,46 | 41,7% | 21 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 61 | 96 | +€5,19 | 45,8% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 61 | 96 | +€3,10 | 40,6% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 61 | 96 | +€2,79 | 41,7% | 21 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 61 | 96 | +€1,39 | 46,9% | 23 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 60 | 95 | +€3,04 | 44,2% | 25 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 60 | 84 | +€1,97 | 27,4% | 15 | 6 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 60 | 95 | €-0,05 | 40,0% | 20 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 57 | 80 | +€8,42 | 31,2% | 9 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 55 | 90 | +€4,49 | 45,6% | 21 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 55 | 90 | +€0,58 | 40,0% | 12 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 53 | 91 | €-4,48 | 36,3% | 25 | 8 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 53 | 88 | €-7,46 | 23,9% | 23 | 11 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 50 | 85 | €-5,11 | 34,1% | 7 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 46 | 84 | +€1,43 | 34,5% | 17 | 8 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 45 | 77 | €-5,45 | 31,2% | 3 | 13 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 45 | 73 | €-8,74 | 21,9% | 3 | 16 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 45 | 73 | €-9,29 | 21,9% | 2 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 38 | 70 | €-5,46 | 30,0% | 10 | 9 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
