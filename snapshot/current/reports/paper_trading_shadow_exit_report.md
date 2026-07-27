# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T19:23:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **654**
- Scenari virtuali ancora attivi: **12100**
- Gruppi in attesa dell'uscita originale: **349**
- Gruppi con originale chiuso ma Shadow ancora attive: **305**
- Confronti completati: **74245**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2263 | 2328 | +€7,08 | 49,0% | 686 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2263 | 2328 | +€5,25 | 47,3% | 702 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2263 | 2328 | +€3,11 | 46,1% | 711 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2263 | 2328 | +€2,31 | 45,4% | 774 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2260 | 2325 | +€1,61 | 45,6% | 674 | 89 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2252 | 2317 | €-3,96 | 42,8% | 492 | 416 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2245 | 2310 | €-4,84 | 36,9% | 288 | 605 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2242 | 2307 | +€4,32 | 42,7% | 554 | 67 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2242 | 2307 | +€2,43 | 42,0% | 544 | 95 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2242 | 2307 | +€1,68 | 39,8% | 624 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2242 | 2307 | +€1,17 | 42,1% | 456 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2238 | 2303 | €-0,40 | 39,6% | 385 | 299 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2229 | 2294 | €-7,31 | 31,7% | 160 | 717 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2218 | 2283 | €-3,45 | 31,0% | 282 | 505 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2202 | 2267 | €-4,65 | 28,2% | 253 | 576 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2201 | 2266 | +€2,33 | 31,2% | 319 | 256 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2176 | 2241 | +€2,96 | 36,8% | 165 | 397 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2164 | 2229 | €-10,06 | 26,1% | 206 | 620 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2142 | 2207 | €-10,54 | 29,3% | 448 | 446 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2056 | 2121 | €-16,95 | 19,5% | 205 | 677 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
