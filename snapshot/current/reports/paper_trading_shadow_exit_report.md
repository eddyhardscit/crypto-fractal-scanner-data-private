# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T14:23:34+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **106**
- Scenari virtuali ancora attivi: **1216**
- Gruppi in attesa dell'uscita originale: **64**
- Gruppi con originale chiuso ma Shadow ancora attive: **42**
- Confronti completati: **1864**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 65 | 100 | +€7,47 | 45,0% | 23 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 65 | 100 | +€6,20 | 40,0% | 21 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 65 | 100 | +€4,99 | 44,0% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 65 | 100 | +€2,98 | 39,0% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 65 | 100 | +€2,70 | 42,0% | 25 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 65 | 100 | +€2,68 | 40,0% | 21 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 65 | 100 | +€2,12 | 41,0% | 21 | 6 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 65 | 100 | +€1,34 | 45,0% | 23 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 65 | 100 | €-0,24 | 38,0% | 20 | 4 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 65 | 100 | €-1,39 | 36,0% | 12 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 64 | 88 | +€1,88 | 26,1% | 15 | 6 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 61 | 84 | +€8,02 | 29,8% | 9 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 60 | 99 | €-4,71 | 34,3% | 25 | 10 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 57 | 92 | €-7,13 | 22,8% | 23 | 11 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 56 | 91 | €-5,90 | 31,9% | 7 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 51 | 90 | +€2,68 | 33,3% | 17 | 8 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 49 | 81 | €-5,18 | 29,6% | 3 | 13 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 49 | 81 | €-8,35 | 19,8% | 3 | 20 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 49 | 81 | €-8,86 | 19,8% | 2 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 42 | 77 | €-5,81 | 27,3% | 10 | 11 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
