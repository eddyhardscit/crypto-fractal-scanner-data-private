# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T20:23:37+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **120**
- Scenari virtuali ancora attivi: **1387**
- Gruppi in attesa dell'uscita originale: **74**
- Gruppi con originale chiuso ma Shadow ancora attive: **46**
- Confronti completati: **2282**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 85 | 122 | +€9,28 | 45,1% | 25 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 85 | 122 | +€7,00 | 44,3% | 25 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 85 | 122 | +€4,68 | 42,6% | 26 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 85 | 122 | +€3,77 | 41,8% | 22 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 85 | 122 | +€3,41 | 45,1% | 25 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 82 | 119 | +€7,76 | 38,7% | 23 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 82 | 119 | +€4,98 | 39,5% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 82 | 119 | +€4,65 | 37,8% | 23 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 82 | 119 | +€1,65 | 37,8% | 20 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 82 | 119 | +€0,26 | 35,3% | 13 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 82 | 125 | €-2,63 | 38,4% | 26 | 10 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 77 | 114 | €-5,94 | 25,4% | 24 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 76 | 113 | +€0,46 | 25,7% | 15 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 74 | 105 | +€3,64 | 26,7% | 9 | 14 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 72 | 109 | €-4,48 | 33,0% | 7 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 70 | 113 | +€2,33 | 31,0% | 18 | 14 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 67 | 101 | €-5,12 | 29,7% | 4 | 15 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 66 | 99 | €-7,16 | 22,2% | 3 | 21 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 66 | 99 | €-7,57 | 22,2% | 2 | 22 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 56 | 99 | €-1,18 | 27,3% | 11 | 14 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
