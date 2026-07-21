# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T03:38:36+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **150**
- Scenari virtuali ancora attivi: **1917**
- Gruppi in attesa dell'uscita originale: **110**
- Gruppi con originale chiuso ma Shadow ancora attive: **40**
- Confronti completati: **2371**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 88 | 125 | +€9,47 | 45,6% | 25 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 88 | 125 | +€7,19 | 44,8% | 25 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 88 | 125 | +€4,87 | 43,2% | 26 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 88 | 125 | +€3,93 | 42,4% | 22 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 88 | 125 | +€3,71 | 45,6% | 25 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 88 | 132 | €-2,56 | 39,4% | 26 | 11 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 86 | 123 | +€8,56 | 39,8% | 23 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 86 | 123 | +€5,97 | 40,7% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 86 | 130 | +€2,78 | 36,9% | 18 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 84 | 121 | +€4,81 | 38,0% | 23 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 84 | 121 | +€1,81 | 38,0% | 20 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 84 | 121 | +€0,40 | 35,5% | 13 | 16 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 82 | 119 | €-7,66 | 30,3% | 7 | 24 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 80 | 117 | €-5,82 | 25,6% | 25 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 77 | 114 | +€0,46 | 25,4% | 15 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 76 | 112 | +€7,31 | 30,4% | 9 | 14 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 68 | 102 | €-5,07 | 29,4% | 4 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 67 | 111 | +€2,71 | 30,6% | 11 | 17 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 67 | 100 | €-7,09 | 22,0% | 3 | 21 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 67 | 100 | €-7,49 | 22,0% | 2 | 22 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
