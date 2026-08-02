# Block 3 — Shadow Exit Engine

Generato: 2026-08-02T20:24:06+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **161**
- Scenari virtuali ancora attivi: **2011**
- Gruppi in attesa dell'uscita originale: **28**
- Gruppi con originale chiuso ma Shadow ancora attive: **133**
- Confronti completati: **118049**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3200 | 3266 | €-1,48 | 45,8% | 665 | 488 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3198 | 3264 | +€9,23 | 52,0% | 902 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3198 | 3264 | +€7,55 | 51,1% | 906 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3198 | 3264 | +€6,25 | 49,5% | 907 | 71 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3198 | 3264 | +€4,92 | 49,0% | 1003 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3195 | 3261 | +€4,62 | 49,5% | 850 | 131 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3194 | 3260 | €-1,17 | 39,5% | 396 | 732 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3194 | 3260 | €-4,65 | 31,8% | 184 | 992 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3192 | 3258 | +€6,75 | 43,5% | 698 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3192 | 3258 | +€4,88 | 43,0% | 677 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3192 | 3258 | +€4,55 | 41,4% | 766 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3192 | 3258 | +€4,17 | 42,1% | 594 | 208 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3189 | 3255 | +€2,26 | 40,4% | 512 | 364 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3188 | 3254 | +€5,13 | 33,3% | 410 | 380 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3187 | 3253 | +€3,84 | 35,7% | 198 | 619 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3186 | 3252 | €-0,37 | 31,7% | 365 | 677 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3180 | 3246 | €-1,09 | 28,9% | 309 | 811 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3170 | 3236 | €-5,79 | 27,2% | 258 | 889 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3100 | 3166 | €-4,49 | 33,0% | 544 | 665 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3099 | 3165 | €-9,65 | 22,1% | 257 | 995 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
