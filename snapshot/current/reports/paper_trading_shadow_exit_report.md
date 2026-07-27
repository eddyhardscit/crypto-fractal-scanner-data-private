# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T13:22:42+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **804**
- Scenari virtuali ancora attivi: **12137**
- Gruppi in attesa dell'uscita originale: **349**
- Gruppi con originale chiuso ma Shadow ancora attive: **455**
- Confronti completati: **68118**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2143 | 2208 | €-4,26 | 42,9% | 492 | 382 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2142 | 2207 | +€6,55 | 47,9% | 672 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2142 | 2207 | +€4,75 | 46,2% | 688 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2142 | 2207 | +€2,59 | 44,9% | 699 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2142 | 2207 | +€1,75 | 44,2% | 760 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2140 | 2205 | +€1,13 | 44,4% | 662 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2124 | 2189 | +€4,16 | 43,3% | 542 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2124 | 2189 | +€2,29 | 42,5% | 532 | 93 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2124 | 2189 | +€1,27 | 40,2% | 612 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2124 | 2189 | +€1,09 | 42,8% | 445 | 156 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2117 | 2182 | €-0,48 | 40,1% | 374 | 294 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2117 | 2182 | €-3,62 | 32,2% | 279 | 501 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2097 | 2162 | €-4,88 | 29,3% | 250 | 571 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2087 | 2152 | €-3,47 | 38,9% | 284 | 525 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2080 | 2145 | +€3,08 | 32,6% | 315 | 221 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2051 | 2116 | €-10,55 | 27,1% | 203 | 608 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2036 | 2101 | €-5,38 | 33,7% | 160 | 614 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2024 | 2089 | €-12,38 | 28,4% | 444 | 439 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2019 | 2084 | +€4,83 | 38,8% | 165 | 327 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1915 | 1980 | €-19,16 | 19,9% | 202 | 648 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
