# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T20:23:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **664**
- Scenari virtuali ancora attivi: **12716**
- Gruppi in attesa dell'uscita originale: **350**
- Gruppi con originale chiuso ma Shadow ancora attive: **314**
- Confronti completati: **74747**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2279 | 2344 | +€6,91 | 48,6% | 701 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2279 | 2344 | +€5,08 | 47,0% | 717 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2279 | 2344 | +€2,94 | 45,8% | 726 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2279 | 2344 | +€2,17 | 45,1% | 789 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2278 | 2343 | +€1,42 | 45,3% | 690 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2258 | 2323 | +€4,39 | 43,0% | 556 | 67 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2258 | 2323 | +€2,47 | 42,2% | 546 | 95 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2258 | 2323 | +€1,67 | 40,0% | 627 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2258 | 2323 | +€1,18 | 42,4% | 458 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2256 | 2321 | €-0,44 | 39,7% | 390 | 300 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2253 | 2318 | €-3,97 | 42,8% | 493 | 416 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2249 | 2314 | €-3,50 | 31,1% | 286 | 518 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2247 | 2312 | €-4,82 | 36,9% | 288 | 605 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2230 | 2295 | €-7,31 | 31,7% | 160 | 717 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2217 | 2282 | +€2,43 | 31,6% | 319 | 256 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2204 | 2269 | €-4,57 | 28,3% | 253 | 576 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2179 | 2244 | +€2,99 | 36,8% | 165 | 397 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2165 | 2230 | €-10,06 | 26,1% | 206 | 620 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2143 | 2208 | €-10,54 | 29,3% | 448 | 446 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2059 | 2124 | €-16,78 | 19,6% | 205 | 677 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
