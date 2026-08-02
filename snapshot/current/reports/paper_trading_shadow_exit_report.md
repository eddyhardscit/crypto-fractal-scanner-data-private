# Block 3 — Shadow Exit Engine

Generato: 2026-08-02T19:24:01+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **201**
- Scenari virtuali ancora attivi: **2567**
- Gruppi in attesa dell'uscita originale: **29**
- Gruppi con originale chiuso ma Shadow ancora attive: **172**
- Confronti completati: **117497**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3199 | 3265 | €-1,48 | 45,8% | 665 | 488 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3197 | 3263 | +€9,20 | 52,0% | 902 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3197 | 3263 | +€7,53 | 51,1% | 906 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3197 | 3263 | +€6,19 | 49,5% | 907 | 71 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3197 | 3263 | +€4,91 | 49,0% | 1003 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3194 | 3260 | +€4,56 | 49,4% | 850 | 131 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3193 | 3259 | €-1,17 | 39,5% | 396 | 732 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3190 | 3256 | +€6,73 | 43,5% | 698 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3190 | 3256 | +€4,86 | 43,0% | 677 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3190 | 3256 | +€4,54 | 41,4% | 766 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3190 | 3256 | +€4,11 | 42,1% | 594 | 208 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3187 | 3253 | +€2,21 | 40,4% | 512 | 364 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3186 | 3252 | +€5,11 | 33,2% | 410 | 380 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3184 | 3250 | €-0,43 | 31,7% | 365 | 677 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3184 | 3250 | €-4,68 | 31,6% | 184 | 992 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3178 | 3244 | €-1,14 | 28,9% | 309 | 811 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3172 | 3238 | +€4,10 | 35,8% | 198 | 606 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3168 | 3234 | €-5,83 | 27,1% | 258 | 889 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3064 | 3130 | €-5,15 | 32,7% | 544 | 651 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3062 | 3128 | €-10,38 | 21,6% | 257 | 981 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
