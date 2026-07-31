# Block 3 — Shadow Exit Engine

Generato: 2026-07-31T13:38:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **403**
- Scenari virtuali ancora attivi: **5951**
- Gruppi in attesa dell'uscita originale: **79**
- Gruppi con originale chiuso ma Shadow ancora attive: **324**
- Confronti completati: **111878**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3119 | 3185 | €-1,28 | 39,7% | 392 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3119 | 3185 | €-1,65 | 46,1% | 657 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3119 | 3185 | €-4,74 | 32,2% | 180 | 980 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3093 | 3159 | +€8,92 | 52,1% | 890 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3093 | 3159 | +€7,26 | 51,2% | 892 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3093 | 3159 | +€4,83 | 49,1% | 989 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3092 | 3158 | +€5,21 | 49,6% | 899 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3090 | 3156 | +€3,71 | 49,3% | 844 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3055 | 3121 | +€6,39 | 43,9% | 696 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3055 | 3121 | +€4,52 | 43,5% | 673 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3055 | 3121 | +€4,39 | 41,8% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3054 | 3120 | +€2,94 | 42,9% | 588 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3051 | 3117 | +€1,17 | 40,8% | 509 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3046 | 3112 | €-1,65 | 32,1% | 365 | 662 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3032 | 3098 | €-2,04 | 29,5% | 308 | 784 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3027 | 3093 | +€4,83 | 33,3% | 410 | 358 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3001 | 3067 | €-6,34 | 27,7% | 257 | 844 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2995 | 3061 | +€3,98 | 36,4% | 198 | 566 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2915 | 2981 | €-6,41 | 33,2% | 540 | 591 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2875 | 2941 | €-12,12 | 22,2% | 256 | 911 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
