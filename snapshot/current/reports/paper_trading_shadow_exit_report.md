# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T15:09:10+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **276**
- Scenari virtuali ancora attivi: **4261**
- Gruppi in attesa dell'uscita originale: **35**
- Gruppi con originale chiuso ma Shadow ancora attive: **241**
- Confronti completati: **114793**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3172 | 3238 | €-1,19 | 39,5% | 395 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3172 | 3238 | €-1,51 | 45,8% | 663 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3172 | 3238 | €-4,69 | 31,7% | 183 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3153 | 3219 | +€8,89 | 51,8% | 890 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3153 | 3219 | +€7,25 | 50,9% | 892 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3153 | 3219 | +€4,89 | 48,8% | 989 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3152 | 3218 | +€5,22 | 49,4% | 901 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3150 | 3216 | +€3,73 | 49,1% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3127 | 3193 | +€6,34 | 43,3% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3127 | 3193 | +€4,50 | 42,9% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3127 | 3193 | +€4,39 | 41,2% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3126 | 3192 | +€2,95 | 42,2% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3123 | 3189 | +€1,20 | 40,2% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3114 | 3180 | +€4,85 | 32,9% | 410 | 375 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3113 | 3179 | €-1,63 | 31,5% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3110 | 3176 | €-2,19 | 28,7% | 308 | 804 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3095 | 3161 | €-6,72 | 27,0% | 257 | 878 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3088 | 3154 | +€3,68 | 35,6% | 198 | 593 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3005 | 3071 | €-6,91 | 32,7% | 543 | 625 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2977 | 3043 | €-12,54 | 21,6% | 256 | 953 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
