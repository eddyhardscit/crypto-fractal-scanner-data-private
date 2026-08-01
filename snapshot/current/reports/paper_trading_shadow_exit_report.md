# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T07:53:52+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **340**
- Scenari virtuali ancora attivi: **5223**
- Gruppi in attesa dell'uscita originale: **43**
- Gruppi con originale chiuso ma Shadow ancora attive: **297**
- Confronti completati: **113737**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3161 | 3227 | €-1,20 | 39,6% | 393 | 726 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3161 | 3227 | €-1,50 | 45,9% | 661 | 481 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3161 | 3227 | €-4,69 | 31,8% | 181 | 986 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3123 | 3189 | +€8,95 | 52,2% | 890 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3123 | 3189 | +€7,30 | 51,3% | 892 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3123 | 3189 | +€4,91 | 49,2% | 989 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3122 | 3188 | +€5,25 | 49,7% | 901 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3120 | 3186 | +€3,76 | 49,4% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3080 | 3146 | +€6,43 | 43,9% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3080 | 3146 | +€4,57 | 43,5% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3080 | 3146 | +€4,46 | 41,8% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3079 | 3145 | +€2,99 | 42,9% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3076 | 3142 | +€1,22 | 40,8% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3065 | 3131 | €-1,65 | 32,0% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3062 | 3128 | €-2,22 | 29,2% | 308 | 804 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3051 | 3117 | +€4,97 | 33,3% | 410 | 365 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3047 | 3113 | €-6,82 | 27,4% | 257 | 878 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3024 | 3090 | +€3,78 | 36,2% | 198 | 583 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2975 | 3041 | €-6,98 | 32,9% | 543 | 625 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2929 | 2995 | €-12,74 | 21,9% | 256 | 953 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
