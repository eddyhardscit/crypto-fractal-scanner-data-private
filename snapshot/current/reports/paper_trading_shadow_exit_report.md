# Block 3 — Shadow Exit Engine

Generato: 2026-08-02T00:08:57+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **263**
- Scenari virtuali ancora attivi: **4192**
- Gruppi in attesa dell'uscita originale: **31**
- Gruppi con originale chiuso ma Shadow ancora attive: **232**
- Confronti completati: **115332**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3179 | 3245 | €-1,19 | 39,4% | 395 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3179 | 3245 | €-1,50 | 45,7% | 663 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3179 | 3245 | €-4,68 | 31,6% | 183 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3167 | 3233 | +€8,85 | 51,8% | 896 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3167 | 3233 | +€7,22 | 50,9% | 898 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3167 | 3233 | +€4,87 | 48,8% | 995 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3160 | 3226 | +€5,21 | 49,5% | 901 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3157 | 3223 | +€3,73 | 49,1% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3139 | 3205 | +€6,31 | 43,1% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3139 | 3205 | +€4,48 | 42,7% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3139 | 3205 | +€4,38 | 41,1% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3138 | 3204 | +€2,93 | 42,1% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3134 | 3200 | +€1,20 | 40,1% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3132 | 3198 | +€4,84 | 32,8% | 410 | 378 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3124 | 3190 | €-1,62 | 31,4% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3124 | 3190 | €-2,20 | 28,6% | 308 | 807 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3110 | 3176 | €-6,67 | 26,9% | 257 | 881 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3107 | 3173 | +€3,75 | 35,6% | 198 | 596 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3011 | 3077 | €-6,99 | 32,6% | 543 | 630 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2995 | 3061 | €-12,51 | 21,5% | 256 | 959 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
