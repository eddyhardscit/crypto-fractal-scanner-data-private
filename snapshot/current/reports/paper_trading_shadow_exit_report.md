# Block 3 — Shadow Exit Engine

Generato: 2026-07-31T21:38:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **381**
- Scenari virtuali ancora attivi: **6059**
- Gruppi in attesa dell'uscita originale: **50**
- Gruppi con originale chiuso ma Shadow ancora attive: **331**
- Confronti completati: **112738**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3154 | 3220 | €-1,19 | 39,7% | 393 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3154 | 3220 | €-1,50 | 46,0% | 659 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3154 | 3220 | €-4,69 | 31,9% | 181 | 980 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3109 | 3175 | +€8,99 | 52,3% | 890 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3109 | 3175 | +€7,33 | 51,4% | 892 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3109 | 3175 | +€4,93 | 49,3% | 989 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3108 | 3174 | +€5,28 | 49,9% | 899 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3106 | 3172 | +€3,78 | 49,6% | 844 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3062 | 3128 | +€6,47 | 44,1% | 696 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3062 | 3128 | +€4,60 | 43,7% | 673 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3062 | 3128 | +€4,49 | 42,0% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3061 | 3127 | +€3,01 | 43,0% | 588 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3058 | 3124 | +€1,23 | 41,0% | 509 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3047 | 3113 | €-1,65 | 32,2% | 365 | 662 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3038 | 3104 | €-2,12 | 29,4% | 308 | 789 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3036 | 3102 | +€5,00 | 33,5% | 410 | 359 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3012 | 3078 | €-6,47 | 27,7% | 257 | 852 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3003 | 3069 | +€3,93 | 36,4% | 198 | 571 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2934 | 3000 | €-6,45 | 33,4% | 540 | 596 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2886 | 2952 | €-12,24 | 22,2% | 256 | 919 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
