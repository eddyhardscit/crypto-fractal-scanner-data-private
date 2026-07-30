# Block 3 — Shadow Exit Engine

Generato: 2026-07-30T13:08:53+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **465**
- Scenari virtuali ancora attivi: **6443**
- Gruppi in attesa dell'uscita originale: **117**
- Gruppi con originale chiuso ma Shadow ancora attive: **348**
- Confronti completati: **110981**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3082 | 3147 | €-1,28 | 40,2% | 388 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3082 | 3147 | €-1,69 | 46,5% | 656 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3082 | 3147 | €-4,79 | 32,6% | 176 | 980 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3068 | 3133 | +€8,90 | 51,7% | 889 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3068 | 3133 | +€7,24 | 50,8% | 891 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3068 | 3133 | +€4,78 | 48,7% | 988 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3060 | 3125 | +€5,19 | 49,4% | 898 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3058 | 3123 | +€3,69 | 49,1% | 843 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3046 | 3111 | +€6,39 | 44,0% | 695 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3046 | 3111 | +€4,52 | 43,7% | 672 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3046 | 3111 | +€4,39 | 41,9% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3045 | 3110 | +€2,94 | 43,0% | 587 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3042 | 3107 | +€1,16 | 40,9% | 509 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3037 | 3102 | €-1,66 | 32,2% | 365 | 662 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3016 | 3081 | +€4,81 | 33,4% | 410 | 357 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3015 | 3080 | €-2,04 | 29,6% | 308 | 777 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2958 | 3023 | +€4,42 | 36,8% | 198 | 540 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2934 | 2999 | €-6,16 | 27,7% | 257 | 804 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2886 | 2951 | €-6,38 | 33,3% | 539 | 588 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2833 | 2898 | €-11,72 | 22,5% | 256 | 879 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
