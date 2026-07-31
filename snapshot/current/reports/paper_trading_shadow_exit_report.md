# Block 3 — Shadow Exit Engine

Generato: 2026-07-31T20:38:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **390**
- Scenari virtuali ancora attivi: **6141**
- Gruppi in attesa dell'uscita originale: **52**
- Gruppi con originale chiuso ma Shadow ancora attive: **338**
- Confronti completati: **112620**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3152 | 3218 | €-1,19 | 39,7% | 393 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3152 | 3218 | €-1,50 | 46,0% | 659 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3152 | 3218 | €-4,70 | 31,9% | 181 | 980 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3107 | 3173 | +€8,98 | 52,3% | 890 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3107 | 3173 | +€7,32 | 51,4% | 892 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3107 | 3173 | +€4,92 | 49,3% | 989 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3106 | 3172 | +€5,27 | 49,8% | 899 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3104 | 3170 | +€3,77 | 49,6% | 844 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3062 | 3128 | +€6,47 | 44,1% | 696 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3062 | 3128 | +€4,60 | 43,7% | 673 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3062 | 3128 | +€4,49 | 42,0% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3061 | 3127 | +€3,01 | 43,0% | 588 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3058 | 3124 | +€1,23 | 41,0% | 509 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3047 | 3113 | €-1,65 | 32,2% | 365 | 662 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3036 | 3102 | +€5,00 | 33,5% | 410 | 359 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3034 | 3100 | €-2,04 | 29,5% | 308 | 785 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3003 | 3069 | €-6,35 | 27,7% | 257 | 845 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2999 | 3065 | +€4,02 | 36,5% | 198 | 567 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2930 | 2996 | €-6,38 | 33,4% | 540 | 592 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2877 | 2943 | €-12,12 | 22,2% | 256 | 912 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
