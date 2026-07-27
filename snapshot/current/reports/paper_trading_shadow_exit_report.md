# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T14:23:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **748**
- Scenari virtuali ancora attivi: **10890**
- Gruppi in attesa dell'uscita originale: **332**
- Gruppi con originale chiuso ma Shadow ancora attive: **416**
- Confronti completati: **69440**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2170 | 2235 | +€6,56 | 48,3% | 673 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2170 | 2235 | +€4,78 | 46,6% | 689 | 17 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2170 | 2235 | +€2,64 | 45,4% | 700 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2170 | 2235 | +€1,83 | 44,6% | 761 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2169 | 2234 | +€1,17 | 44,8% | 663 | 89 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2167 | 2232 | €-4,16 | 43,2% | 492 | 383 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2151 | 2216 | +€4,19 | 43,1% | 542 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2151 | 2216 | +€2,32 | 42,3% | 532 | 93 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2151 | 2216 | +€1,34 | 40,0% | 612 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2151 | 2216 | +€1,12 | 42,5% | 445 | 156 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2146 | 2211 | €-0,45 | 39,8% | 374 | 296 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2141 | 2206 | €-3,57 | 31,9% | 279 | 503 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2128 | 2193 | €-3,83 | 38,2% | 284 | 544 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2123 | 2188 | €-4,86 | 29,0% | 250 | 574 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2105 | 2170 | +€3,06 | 32,3% | 315 | 224 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2080 | 2145 | €-10,40 | 26,9% | 203 | 612 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2062 | 2127 | €-5,30 | 33,4% | 160 | 618 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2047 | 2112 | €-12,21 | 28,8% | 445 | 439 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2043 | 2108 | +€4,77 | 38,4% | 165 | 330 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1939 | 2004 | €-18,93 | 19,7% | 202 | 651 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
