# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T21:23:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **640**
- Scenari virtuali ancora attivi: **12430**
- Gruppi in attesa dell'uscita originale: **350**
- Gruppi con originale chiuso ma Shadow ancora attive: **290**
- Confronti completati: **74983**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2283 | 2348 | +€6,87 | 48,6% | 703 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2283 | 2348 | +€5,04 | 47,0% | 719 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2283 | 2348 | +€2,90 | 45,8% | 728 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2283 | 2348 | +€2,14 | 45,1% | 791 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2282 | 2347 | +€1,37 | 45,3% | 692 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2269 | 2334 | +€4,35 | 42,8% | 558 | 67 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2269 | 2334 | +€2,43 | 42,1% | 548 | 95 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2269 | 2334 | +€1,64 | 39,8% | 629 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2269 | 2334 | +€1,15 | 42,2% | 460 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2267 | 2332 | €-0,48 | 39,6% | 392 | 300 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2258 | 2323 | €-3,49 | 31,0% | 286 | 518 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2257 | 2322 | €-4,00 | 42,8% | 496 | 416 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2249 | 2314 | €-4,82 | 36,9% | 288 | 605 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2234 | 2299 | +€2,58 | 31,7% | 319 | 256 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2232 | 2297 | €-7,30 | 31,7% | 160 | 717 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2213 | 2278 | €-4,55 | 28,2% | 253 | 576 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2188 | 2253 | +€2,98 | 36,7% | 165 | 397 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2174 | 2239 | €-10,01 | 26,0% | 206 | 620 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2145 | 2210 | €-10,52 | 29,3% | 448 | 446 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2068 | 2133 | €-16,71 | 19,5% | 205 | 677 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
