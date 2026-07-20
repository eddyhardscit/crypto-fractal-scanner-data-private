# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T10:23:36+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **99**
- Scenari virtuali ancora attivi: **1224**
- Gruppi in attesa dell'uscita originale: **66**
- Gruppi con originale chiuso ma Shadow ancora attive: **33**
- Confronti completati: **1348**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 43 | 75 | +€10,33 | 50,7% | 18 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 43 | 74 | +€8,30 | 47,3% | 16 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 43 | 75 | +€7,38 | 50,7% | 18 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 43 | 74 | +€4,76 | 45,9% | 17 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 43 | 75 | +€4,48 | 48,0% | 20 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 43 | 74 | +€3,60 | 47,3% | 16 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 43 | 75 | +€2,42 | 50,7% | 18 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 43 | 74 | +€0,92 | 44,6% | 16 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 42 | 65 | +€10,13 | 36,9% | 8 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 42 | 66 | +€2,90 | 33,3% | 12 | 6 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 38 | 70 | +€6,99 | 50,0% | 16 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 37 | 68 | +€2,07 | 45,6% | 11 | 5 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 37 | 71 | €-5,76 | 38,0% | 20 | 8 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 37 | 68 | €-6,88 | 36,8% | 7 | 12 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 36 | 63 | €-5,70 | 28,6% | 16 | 5 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 31 | 65 | €-3,07 | 38,5% | 15 | 8 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 31 | 59 | €-6,37 | 35,6% | 2 | 11 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 31 | 52 | €-8,24 | 30,8% | 3 | 7 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 31 | 52 | €-8,51 | 30,8% | 2 | 8 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 26 | 53 | €-7,79 | 35,8% | 9 | 8 | PRELIMINARY_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
