# Block 3 — Shadow Exit Engine

Generato: 2026-07-30T17:08:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **455**
- Scenari virtuali ancora attivi: **6273**
- Gruppi in attesa dell'uscita originale: **115**
- Gruppi con originale chiuso ma Shadow ancora attive: **340**
- Confronti completati: **111146**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3084 | 3149 | €-1,28 | 40,1% | 388 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3084 | 3149 | €-1,68 | 46,5% | 656 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3084 | 3149 | €-4,78 | 32,6% | 176 | 980 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3069 | 3134 | +€8,90 | 51,7% | 889 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3069 | 3134 | +€7,24 | 50,8% | 891 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3069 | 3134 | +€4,78 | 48,7% | 988 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3061 | 3126 | +€5,19 | 49,4% | 898 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3059 | 3124 | +€3,69 | 49,1% | 843 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3047 | 3112 | +€6,38 | 44,0% | 695 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3047 | 3112 | +€4,51 | 43,6% | 672 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3047 | 3112 | +€4,39 | 41,9% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3046 | 3111 | +€2,94 | 43,0% | 587 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3043 | 3108 | +€1,16 | 40,9% | 509 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3038 | 3103 | €-1,66 | 32,2% | 365 | 662 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3022 | 3087 | €-2,05 | 29,5% | 308 | 783 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3018 | 3083 | +€4,82 | 33,4% | 410 | 357 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2972 | 3037 | €-6,01 | 27,9% | 257 | 824 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2969 | 3034 | +€4,22 | 36,7% | 198 | 549 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2887 | 2952 | €-6,38 | 33,3% | 539 | 588 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2846 | 2911 | €-11,75 | 22,4% | 256 | 891 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
