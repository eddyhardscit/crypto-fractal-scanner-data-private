# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T15:23:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **711**
- Scenari virtuali ancora attivi: **11281**
- Gruppi in attesa dell'uscita originale: **323**
- Gruppi con originale chiuso ma Shadow ancora attive: **388**
- Confronti completati: **72482**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2228 | 2293 | +€7,22 | 48,9% | 673 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2228 | 2293 | +€5,40 | 47,2% | 689 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2228 | 2293 | +€3,24 | 46,1% | 700 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2228 | 2293 | +€2,41 | 45,3% | 761 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2227 | 2292 | +€1,74 | 45,5% | 663 | 89 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2211 | 2276 | +€4,51 | 43,1% | 542 | 67 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2211 | 2276 | +€2,64 | 42,4% | 532 | 95 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2211 | 2276 | +€1,85 | 40,2% | 612 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2211 | 2276 | +€1,41 | 42,6% | 445 | 158 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2209 | 2274 | €-0,16 | 40,0% | 374 | 299 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2202 | 2267 | €-3,47 | 31,1% | 282 | 505 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2200 | 2265 | €-3,99 | 43,0% | 492 | 384 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2187 | 2252 | €-4,32 | 37,6% | 284 | 571 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2186 | 2251 | €-4,68 | 28,4% | 253 | 576 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2148 | 2213 | €-10,14 | 26,3% | 206 | 620 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2144 | 2209 | +€2,97 | 31,8% | 315 | 230 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2136 | 2201 | €-6,04 | 32,3% | 160 | 660 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2111 | 2176 | +€3,93 | 37,4% | 165 | 361 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2110 | 2175 | €-11,54 | 28,8% | 448 | 442 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2021 | 2086 | €-18,72 | 19,1% | 205 | 673 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
