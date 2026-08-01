# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T05:53:59+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **346**
- Scenari virtuali ancora attivi: **5422**
- Gruppi in attesa dell'uscita originale: **47**
- Gruppi con originale chiuso ma Shadow ancora attive: **299**
- Confronti completati: **113436**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3160 | 3226 | €-1,20 | 39,6% | 393 | 726 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3160 | 3226 | €-1,50 | 45,9% | 661 | 481 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3160 | 3226 | €-4,69 | 31,8% | 181 | 986 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3119 | 3185 | +€8,95 | 52,2% | 890 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3119 | 3185 | +€7,30 | 51,2% | 892 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3119 | 3185 | +€4,91 | 49,2% | 989 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3118 | 3184 | +€5,26 | 49,7% | 899 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3116 | 3182 | +€3,76 | 49,4% | 844 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3072 | 3138 | +€6,45 | 43,9% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3072 | 3138 | +€4,58 | 43,5% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3072 | 3138 | +€4,47 | 41,8% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3071 | 3137 | +€3,00 | 42,9% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3068 | 3134 | +€1,22 | 40,8% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3057 | 3123 | €-1,65 | 32,1% | 365 | 668 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3054 | 3120 | €-2,23 | 29,3% | 308 | 801 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3046 | 3112 | +€4,98 | 33,4% | 410 | 365 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3038 | 3104 | €-6,82 | 27,4% | 257 | 874 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3019 | 3085 | +€3,79 | 36,2% | 198 | 583 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2967 | 3033 | €-7,00 | 33,0% | 540 | 625 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2920 | 2986 | €-12,76 | 22,0% | 256 | 949 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
