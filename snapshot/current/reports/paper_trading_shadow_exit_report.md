# Block 3 — Shadow Exit Engine

Generato: 2026-08-03T00:39:03+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **136**
- Scenari virtuali ancora attivi: **1721**
- Gruppi in attesa dell'uscita originale: **21**
- Gruppi con originale chiuso ma Shadow ancora attive: **115**
- Confronti completati: **118654**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3208 | 3274 | +€9,20 | 51,9% | 907 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3208 | 3274 | +€7,53 | 51,0% | 911 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3208 | 3274 | +€6,24 | 49,4% | 910 | 73 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3208 | 3274 | +€4,91 | 48,9% | 1008 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3207 | 3273 | €-1,14 | 39,6% | 398 | 732 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3207 | 3273 | €-1,49 | 45,7% | 667 | 488 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3204 | 3270 | +€4,61 | 49,4% | 852 | 133 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3202 | 3268 | +€6,73 | 43,4% | 703 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3202 | 3268 | +€4,86 | 42,9% | 682 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3202 | 3268 | +€4,54 | 41,4% | 769 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3202 | 3268 | +€4,16 | 42,0% | 597 | 210 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3201 | 3267 | €-4,64 | 31,7% | 186 | 992 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3198 | 3264 | +€5,13 | 33,3% | 410 | 380 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3198 | 3264 | +€2,25 | 40,3% | 514 | 366 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3198 | 3264 | €-0,39 | 31,6% | 367 | 682 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3195 | 3261 | +€3,83 | 35,7% | 198 | 619 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3195 | 3261 | €-1,09 | 29,0% | 311 | 813 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3185 | 3251 | €-5,77 | 27,3% | 260 | 891 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3118 | 3184 | €-4,52 | 32,9% | 546 | 675 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3117 | 3183 | €-9,67 | 22,0% | 259 | 1005 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
