# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T04:08:39+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **269**
- Scenari virtuali ancora attivi: **2984**
- Gruppi in attesa dell'uscita originale: **160**
- Gruppi con originale chiuso ma Shadow ancora attive: **109**
- Confronti completati: **6450**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 296 | 346 | +€6,87 | 49,4% | 82 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 296 | 346 | +€4,86 | 47,7% | 81 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 296 | 346 | +€2,92 | 46,8% | 82 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 296 | 346 | +€2,53 | 46,8% | 91 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 296 | 346 | +€0,81 | 45,7% | 77 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 292 | 347 | €-4,83 | 44,4% | 72 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 283 | 333 | +€0,67 | 39,3% | 73 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 281 | 331 | +€2,58 | 41,7% | 64 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 281 | 331 | +€0,73 | 39,0% | 64 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 281 | 331 | €-1,19 | 39,6% | 51 | 31 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 280 | 330 | €-6,76 | 27,9% | 26 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 278 | 328 | €-1,83 | 36,0% | 27 | 66 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 276 | 331 | +€0,31 | 39,3% | 34 | 59 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 271 | 321 | €-9,73 | 24,9% | 21 | 93 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 256 | 306 | €-7,57 | 29,1% | 61 | 31 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 255 | 305 | €-1,11 | 31,5% | 32 | 30 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 237 | 287 | +€2,78 | 37,3% | 15 | 33 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 234 | 284 | €-15,02 | 22,9% | 18 | 73 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 228 | 283 | €-3,78 | 32,5% | 17 | 61 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 223 | 272 | €-13,55 | 23,5% | 17 | 63 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
