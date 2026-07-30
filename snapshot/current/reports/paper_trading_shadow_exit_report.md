# Block 3 — Shadow Exit Engine

Generato: 2026-07-30T01:23:54+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **472**
- Scenari virtuali ancora attivi: **6592**
- Gruppi in attesa dell'uscita originale: **128**
- Gruppi con originale chiuso ma Shadow ancora attive: **344**
- Confronti completati: **110735**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3071 | 3136 | €-1,29 | 40,3% | 388 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3071 | 3136 | €-1,69 | 46,6% | 656 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3071 | 3136 | €-4,80 | 32,7% | 176 | 980 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3059 | 3124 | +€8,87 | 51,6% | 889 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3059 | 3124 | +€7,21 | 50,7% | 891 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3059 | 3124 | +€4,74 | 48,6% | 988 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3052 | 3117 | +€5,17 | 49,3% | 898 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3050 | 3115 | +€3,67 | 49,0% | 843 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3043 | 3108 | +€6,36 | 44,0% | 695 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3043 | 3108 | +€4,49 | 43,6% | 672 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3043 | 3108 | +€4,36 | 41,9% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3043 | 3108 | +€2,93 | 43,0% | 587 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3041 | 3106 | +€1,16 | 40,9% | 509 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3036 | 3101 | €-1,66 | 32,2% | 365 | 662 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3006 | 3071 | €-2,03 | 29,7% | 308 | 769 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3002 | 3067 | +€4,72 | 33,1% | 410 | 357 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2942 | 3007 | +€4,09 | 36,5% | 198 | 540 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2933 | 2998 | €-6,16 | 27,7% | 257 | 804 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2878 | 2943 | €-6,46 | 33,4% | 539 | 588 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2831 | 2896 | €-11,79 | 22,5% | 256 | 879 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
