# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T00:38:36+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **151**
- Scenari virtuali ancora attivi: **1977**
- Gruppi in attesa dell'uscita originale: **105**
- Gruppi con originale chiuso ma Shadow ancora attive: **46**
- Confronti completati: **2318**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 86 | 123 | +€9,38 | 45,5% | 25 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 86 | 123 | +€7,09 | 44,7% | 25 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 86 | 123 | +€4,76 | 43,1% | 26 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 86 | 123 | +€3,83 | 42,3% | 22 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 86 | 123 | +€3,52 | 45,5% | 25 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 86 | 130 | €-2,67 | 39,2% | 26 | 11 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 83 | 120 | +€7,98 | 39,2% | 23 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 83 | 120 | +€5,29 | 40,0% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 83 | 120 | +€4,85 | 38,3% | 23 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 83 | 120 | +€1,83 | 38,3% | 20 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 83 | 120 | +€0,40 | 35,8% | 13 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 82 | 126 | +€2,54 | 36,5% | 18 | 15 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 78 | 115 | €-5,97 | 25,2% | 25 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 76 | 113 | +€0,46 | 25,7% | 15 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 75 | 106 | +€3,84 | 27,4% | 9 | 14 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 72 | 109 | €-4,48 | 33,0% | 7 | 15 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 67 | 101 | €-5,12 | 29,7% | 4 | 15 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 66 | 99 | €-7,16 | 22,2% | 3 | 21 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 66 | 99 | €-7,57 | 22,2% | 2 | 22 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 61 | 105 | +€2,90 | 30,5% | 11 | 14 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
