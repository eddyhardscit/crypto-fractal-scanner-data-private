# Block 3 — Shadow Exit Engine

Generato: 2026-07-31T18:38:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **403**
- Scenari virtuali ancora attivi: **5901**
- Gruppi in attesa dell'uscita originale: **66**
- Gruppi con originale chiuso ma Shadow ancora attive: **337**
- Confronti completati: **112198**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3132 | 3198 | €-1,21 | 39,8% | 393 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3132 | 3198 | €-1,56 | 46,1% | 658 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3132 | 3198 | €-4,73 | 32,1% | 181 | 980 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3101 | 3167 | +€8,95 | 52,2% | 890 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3101 | 3167 | +€7,29 | 51,3% | 892 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3101 | 3167 | +€4,88 | 49,2% | 989 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3100 | 3166 | +€5,24 | 49,7% | 899 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3098 | 3164 | +€3,74 | 49,5% | 844 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3062 | 3128 | +€6,47 | 44,1% | 696 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3062 | 3128 | +€4,60 | 43,7% | 673 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3062 | 3128 | +€4,49 | 42,0% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3061 | 3127 | +€3,01 | 43,0% | 588 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3058 | 3124 | +€1,23 | 41,0% | 509 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3047 | 3113 | €-1,65 | 32,2% | 365 | 662 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3035 | 3101 | +€5,01 | 33,5% | 410 | 358 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3033 | 3099 | €-2,04 | 29,5% | 308 | 784 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3002 | 3068 | €-6,34 | 27,7% | 257 | 844 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2995 | 3061 | +€3,98 | 36,4% | 198 | 566 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2923 | 2989 | €-6,39 | 33,3% | 540 | 591 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2876 | 2942 | €-12,12 | 22,2% | 256 | 911 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
