# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T11:53:54+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **319**
- Scenari virtuali ancora attivi: **4676**
- Gruppi in attesa dell'uscita originale: **41**
- Gruppi con originale chiuso ma Shadow ancora attive: **278**
- Confronti completati: **114290**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3166 | 3232 | €-1,20 | 39,5% | 393 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3166 | 3232 | €-1,50 | 45,8% | 661 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3166 | 3232 | €-4,69 | 31,8% | 181 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3141 | 3207 | +€8,90 | 51,9% | 890 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3141 | 3207 | +€7,26 | 51,0% | 892 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3141 | 3207 | +€4,88 | 48,9% | 989 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3140 | 3206 | +€5,23 | 49,4% | 901 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3138 | 3204 | +€3,73 | 49,1% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3098 | 3164 | +€6,40 | 43,6% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3098 | 3164 | +€4,54 | 43,3% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3098 | 3164 | +€4,43 | 41,6% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3097 | 3163 | +€2,97 | 42,6% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3094 | 3160 | +€1,21 | 40,6% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3083 | 3149 | €-1,64 | 31,8% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3080 | 3146 | €-2,21 | 29,0% | 308 | 804 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3072 | 3138 | +€4,93 | 33,1% | 410 | 368 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3065 | 3131 | €-6,78 | 27,2% | 257 | 878 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3045 | 3111 | +€3,75 | 35,9% | 198 | 586 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2993 | 3059 | €-6,94 | 32,8% | 543 | 625 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2947 | 3013 | €-12,67 | 21,8% | 256 | 953 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
