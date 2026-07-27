# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T18:23:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **732**
- Scenari virtuali ancora attivi: **11748**
- Gruppi in attesa dell'uscita originale: **342**
- Gruppi con originale chiuso ma Shadow ancora attive: **390**
- Confronti completati: **73018**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2245 | 2310 | +€7,08 | 48,9% | 680 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2245 | 2310 | +€5,25 | 47,2% | 696 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2245 | 2310 | +€3,09 | 46,0% | 707 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2245 | 2310 | +€2,29 | 45,3% | 768 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2244 | 2309 | +€1,58 | 45,5% | 670 | 89 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2240 | 2305 | €-4,09 | 42,5% | 492 | 416 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2224 | 2289 | +€4,44 | 43,0% | 549 | 67 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2224 | 2289 | +€2,55 | 42,2% | 539 | 95 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2224 | 2289 | +€1,79 | 40,1% | 619 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2224 | 2289 | +€1,31 | 42,5% | 452 | 158 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2222 | 2287 | €-0,28 | 39,9% | 381 | 299 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2206 | 2271 | €-3,46 | 31,1% | 282 | 505 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2204 | 2269 | €-4,35 | 37,4% | 288 | 579 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2190 | 2255 | €-4,67 | 28,4% | 253 | 576 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2167 | 2232 | €-5,81 | 32,5% | 160 | 668 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2157 | 2222 | +€3,01 | 31,7% | 315 | 230 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2152 | 2217 | €-10,12 | 26,3% | 206 | 620 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2127 | 2192 | €-10,75 | 29,0% | 448 | 443 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2115 | 2180 | +€3,92 | 37,4% | 165 | 361 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2034 | 2099 | €-17,87 | 19,4% | 205 | 674 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
