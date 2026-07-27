# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T22:08:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **646**
- Scenari virtuali ancora attivi: **12403**
- Gruppi in attesa dell'uscita originale: **357**
- Gruppi con originale chiuso ma Shadow ancora attive: **289**
- Confronti completati: **75230**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2291 | 2356 | €-3,82 | 43,2% | 502 | 420 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2289 | 2354 | +€6,85 | 48,6% | 708 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2289 | 2354 | +€5,01 | 46,9% | 724 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2289 | 2354 | +€2,87 | 45,8% | 733 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2289 | 2354 | +€2,14 | 45,0% | 796 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2288 | 2353 | +€1,34 | 45,2% | 697 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2274 | 2339 | +€4,39 | 42,9% | 558 | 67 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2274 | 2339 | +€2,47 | 42,2% | 548 | 95 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2274 | 2339 | +€1,69 | 40,0% | 629 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2274 | 2339 | +€1,17 | 42,3% | 460 | 159 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2272 | 2337 | €-0,47 | 39,7% | 392 | 300 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2258 | 2323 | €-3,49 | 31,0% | 286 | 518 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2257 | 2322 | €-4,68 | 37,0% | 290 | 605 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2234 | 2299 | +€2,58 | 31,7% | 319 | 256 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2234 | 2299 | €-7,29 | 31,7% | 160 | 719 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2213 | 2278 | €-4,55 | 28,2% | 253 | 576 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2188 | 2253 | +€2,98 | 36,7% | 165 | 397 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2174 | 2239 | €-10,01 | 26,0% | 206 | 620 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2156 | 2221 | €-10,07 | 29,4% | 453 | 446 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2074 | 2139 | €-16,18 | 19,8% | 205 | 677 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
