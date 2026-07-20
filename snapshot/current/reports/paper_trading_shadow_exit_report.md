# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T08:23:44+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **94**
- Scenari virtuali ancora attivi: **1274**
- Gruppi in attesa dell'uscita originale: **67**
- Gruppi con originale chiuso ma Shadow ancora attive: **27**
- Confronti completati: **1233**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 35 | 67 | +€15,24 | 53,7% | 12 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 35 | 66 | +€12,64 | 48,5% | 11 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 35 | 67 | +€12,26 | 53,7% | 12 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 35 | 67 | +€9,65 | 50,7% | 14 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 35 | 66 | +€9,04 | 47,0% | 12 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 35 | 67 | +€8,96 | 53,7% | 12 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 35 | 66 | +€8,10 | 48,5% | 11 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 35 | 67 | +€7,48 | 49,3% | 15 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 35 | 66 | +€5,44 | 45,5% | 11 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 35 | 66 | +€2,02 | 43,9% | 11 | 5 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 34 | 58 | +€4,66 | 32,8% | 7 | 6 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 34 | 68 | €-6,01 | 36,8% | 20 | 7 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 34 | 65 | €-6,86 | 35,4% | 7 | 11 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 33 | 60 | €-5,55 | 26,7% | 15 | 5 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 29 | 63 | €-3,29 | 36,5% | 15 | 8 | PRELIMINARY_SAMPLE |
| ATR20_R100 | 29 | 52 | €-6,95 | 32,7% | 2 | 8 | PRELIMINARY_SAMPLE |
| ATR30_R100 | 29 | 50 | €-8,72 | 28,0% | 3 | 7 | PRELIMINARY_SAMPLE |
| BE_R100 | 29 | 50 | €-9,00 | 28,0% | 2 | 8 | PRELIMINARY_SAMPLE |
| TP_R200 | 28 | 51 | +€1,89 | 29,4% | 4 | 7 | PRELIMINARY_SAMPLE |
| TIME_24H | 24 | 51 | €-8,25 | 33,3% | 9 | 8 | PRELIMINARY_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
