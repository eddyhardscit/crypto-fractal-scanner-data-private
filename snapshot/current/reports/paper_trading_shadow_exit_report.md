# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T12:23:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **105**
- Scenari virtuali ancora attivi: **1225**
- Gruppi in attesa dell'uscita originale: **65**
- Gruppi con originale chiuso ma Shadow ancora attive: **40**
- Confronti completati: **1657**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 59 | 91 | +€5,87 | 44,0% | 23 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 59 | 91 | +€5,83 | 40,7% | 21 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 59 | 91 | +€3,35 | 42,9% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 59 | 91 | +€2,43 | 39,6% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 59 | 91 | +€1,67 | 40,7% | 21 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 59 | 91 | €-0,61 | 44,0% | 23 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 58 | 82 | +€2,02 | 28,0% | 15 | 6 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 58 | 90 | +€1,26 | 41,1% | 25 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 58 | 90 | €-0,74 | 38,9% | 20 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 55 | 78 | +€8,63 | 32,1% | 9 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 53 | 85 | +€2,91 | 42,4% | 21 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 51 | 86 | €-5,06 | 36,0% | 22 | 8 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 51 | 83 | €-8,68 | 22,9% | 20 | 11 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 49 | 81 | +€2,06 | 40,7% | 12 | 5 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 48 | 80 | €-5,84 | 32,5% | 7 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 44 | 79 | +€1,74 | 35,4% | 15 | 8 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 43 | 71 | €-6,20 | 29,6% | 2 | 13 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 43 | 71 | €-8,99 | 22,5% | 3 | 16 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 43 | 71 | €-9,55 | 22,5% | 2 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 36 | 64 | €-6,45 | 29,7% | 9 | 8 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
