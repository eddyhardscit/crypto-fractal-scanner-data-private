# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T08:08:39+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **252**
- Scenari virtuali ancora attivi: **2907**
- Gruppi in attesa dell'uscita originale: **160**
- Gruppi con originale chiuso ma Shadow ancora attive: **92**
- Confronti completati: **8062**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 369 | 423 | +€6,96 | 45,6% | 99 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 369 | 423 | +€5,11 | 44,2% | 98 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 369 | 423 | +€3,25 | 43,5% | 99 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 369 | 423 | +€3,00 | 43,5% | 108 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 369 | 423 | +€1,31 | 42,6% | 94 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 369 | 424 | €-1,04 | 50,2% | 87 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 367 | 421 | €-0,21 | 34,0% | 90 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 366 | 420 | +€1,63 | 35,5% | 83 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 359 | 413 | +€0,35 | 33,9% | 76 | 25 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 354 | 409 | +€6,85 | 48,9% | 34 | 63 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 352 | 406 | €-1,35 | 26,6% | 42 | 46 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 347 | 401 | €-1,50 | 33,7% | 56 | 36 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 345 | 399 | €-2,01 | 30,8% | 32 | 71 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 341 | 395 | €-5,66 | 24,3% | 28 | 89 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 337 | 391 | +€3,25 | 33,5% | 18 | 49 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 335 | 389 | €-8,24 | 21,6% | 23 | 99 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 334 | 387 | €-7,67 | 28,2% | 67 | 47 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 321 | 376 | €-5,94 | 28,2% | 17 | 95 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 308 | 362 | €-12,77 | 19,9% | 20 | 86 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 302 | 354 | €-14,54 | 18,6% | 19 | 84 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
