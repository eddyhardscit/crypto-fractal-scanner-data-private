# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T09:53:59+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **334**
- Scenari virtuali ancora attivi: **5061**
- Gruppi in attesa dell'uscita originale: **43**
- Gruppi con originale chiuso ma Shadow ancora attive: **291**
- Confronti completati: **113899**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3164 | 3230 | €-1,20 | 39,5% | 393 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3164 | 3230 | €-1,50 | 45,8% | 661 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3164 | 3230 | €-4,69 | 31,8% | 181 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3126 | 3192 | +€8,94 | 52,2% | 890 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3126 | 3192 | +€7,29 | 51,3% | 892 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3126 | 3192 | +€4,91 | 49,1% | 989 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3125 | 3191 | +€5,25 | 49,7% | 901 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3123 | 3189 | +€3,75 | 49,4% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3083 | 3149 | +€6,43 | 43,9% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3083 | 3149 | +€4,56 | 43,5% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3083 | 3149 | +€4,46 | 41,8% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3082 | 3148 | +€2,99 | 42,8% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3079 | 3145 | +€1,22 | 40,8% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3068 | 3134 | €-1,65 | 31,9% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3065 | 3131 | €-2,22 | 29,2% | 308 | 804 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3057 | 3123 | +€4,95 | 33,3% | 410 | 368 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3050 | 3116 | €-6,82 | 27,3% | 257 | 878 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3030 | 3096 | +€3,77 | 36,1% | 198 | 586 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2978 | 3044 | €-6,97 | 32,9% | 543 | 625 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2932 | 2998 | €-12,73 | 21,9% | 256 | 953 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
