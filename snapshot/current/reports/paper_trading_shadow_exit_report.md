# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T15:23:36+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **104**
- Scenari virtuali ancora attivi: **1153**
- Gruppi in attesa dell'uscita originale: **61**
- Gruppi con originale chiuso ma Shadow ancora attive: **43**
- Confronti completati: **1979**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 70 | 105 | +€7,11 | 42,9% | 23 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 70 | 105 | +€5,91 | 38,1% | 21 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 70 | 105 | +€4,75 | 41,9% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 70 | 105 | +€2,84 | 37,1% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 70 | 105 | +€2,57 | 40,0% | 25 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 70 | 105 | +€2,55 | 38,1% | 21 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 70 | 105 | +€2,02 | 39,0% | 21 | 6 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 70 | 105 | +€1,27 | 42,9% | 23 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 70 | 105 | €-0,23 | 36,2% | 20 | 4 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 70 | 105 | €-1,33 | 34,3% | 12 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 70 | 110 | €-3,83 | 35,5% | 25 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 69 | 93 | +€1,78 | 24,7% | 15 | 6 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 66 | 89 | +€7,57 | 28,1% | 9 | 7 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 63 | 98 | €-7,45 | 21,4% | 23 | 12 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 61 | 96 | €-5,59 | 30,2% | 7 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 57 | 97 | +€3,57 | 32,0% | 17 | 8 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 56 | 88 | €-6,35 | 27,3% | 3 | 15 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 55 | 87 | €-8,63 | 18,4% | 3 | 21 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 55 | 87 | €-9,10 | 18,4% | 2 | 22 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 47 | 84 | €-5,65 | 25,0% | 10 | 12 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
