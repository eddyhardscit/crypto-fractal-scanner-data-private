# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T16:23:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **734**
- Scenari virtuali ancora attivi: **12110**
- Gruppi in attesa dell'uscita originale: **352**
- Gruppi con originale chiuso ma Shadow ancora attive: **382**
- Confronti completati: **72750**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2236 | 2301 | €-4,14 | 42,4% | 492 | 416 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2232 | 2297 | +€7,21 | 48,9% | 673 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2232 | 2297 | +€5,40 | 47,2% | 689 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2232 | 2297 | +€3,24 | 46,0% | 700 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2232 | 2297 | +€2,41 | 45,3% | 761 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2231 | 2296 | +€1,74 | 45,5% | 663 | 89 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2215 | 2280 | +€4,50 | 43,1% | 542 | 67 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2215 | 2280 | +€2,64 | 42,3% | 532 | 95 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2215 | 2280 | +€1,84 | 40,1% | 612 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2215 | 2280 | +€1,41 | 42,5% | 445 | 158 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2213 | 2278 | €-0,16 | 39,9% | 374 | 299 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2206 | 2271 | €-3,46 | 31,1% | 282 | 505 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2199 | 2264 | €-4,42 | 37,5% | 284 | 579 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2190 | 2255 | €-4,67 | 28,4% | 253 | 576 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2156 | 2221 | €-5,83 | 32,6% | 160 | 662 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2152 | 2217 | €-10,12 | 26,3% | 206 | 620 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2148 | 2213 | +€2,97 | 31,8% | 315 | 230 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2120 | 2185 | €-10,92 | 29,0% | 448 | 442 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2115 | 2180 | +€3,92 | 37,4% | 165 | 361 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2031 | 2096 | €-18,04 | 19,3% | 205 | 673 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
