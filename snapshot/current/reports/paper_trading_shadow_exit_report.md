# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T09:23:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **92**
- Scenari virtuali ancora attivi: **1162**
- Gruppi in attesa dell'uscita originale: **65**
- Gruppi con originale chiuso ma Shadow ancora attive: **27**
- Confronti completati: **1275**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 37 | 69 | +€14,91 | 55,1% | 12 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 37 | 68 | +€12,38 | 50,0% | 11 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 37 | 69 | +€12,01 | 55,1% | 12 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 37 | 69 | +€9,48 | 52,2% | 14 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 37 | 68 | +€8,89 | 48,5% | 12 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 37 | 69 | +€8,81 | 55,1% | 12 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 37 | 68 | +€7,98 | 50,0% | 11 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 37 | 69 | +€7,37 | 50,7% | 15 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 37 | 68 | +€5,39 | 47,1% | 11 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 37 | 68 | +€2,07 | 45,6% | 11 | 5 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 36 | 60 | +€4,63 | 35,0% | 7 | 6 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 36 | 70 | €-5,73 | 38,6% | 20 | 7 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 36 | 67 | €-6,55 | 37,3% | 7 | 11 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 35 | 62 | €-5,25 | 29,0% | 15 | 5 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 31 | 65 | €-3,07 | 38,5% | 15 | 8 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 31 | 56 | €-6,44 | 35,7% | 2 | 9 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 31 | 52 | €-8,24 | 30,8% | 3 | 7 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 31 | 52 | €-8,51 | 30,8% | 2 | 8 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 30 | 53 | +€1,96 | 32,1% | 4 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 26 | 53 | €-7,79 | 35,8% | 9 | 8 | PRELIMINARY_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
