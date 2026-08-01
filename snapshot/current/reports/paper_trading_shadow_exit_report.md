# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T19:08:57+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **276**
- Scenari virtuali ancora attivi: **4536**
- Gruppi in attesa dell'uscita originale: **44**
- Gruppi con originale chiuso ma Shadow ancora attive: **232**
- Confronti completati: **114913**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3172 | 3238 | €-1,19 | 39,5% | 395 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3172 | 3238 | €-1,51 | 45,8% | 663 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3172 | 3238 | €-4,69 | 31,7% | 183 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3154 | 3220 | +€8,89 | 51,8% | 890 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3154 | 3220 | +€7,25 | 50,9% | 892 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3154 | 3220 | +€4,89 | 48,8% | 989 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3153 | 3219 | +€5,22 | 49,4% | 901 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3151 | 3217 | +€3,73 | 49,1% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3131 | 3197 | +€6,33 | 43,2% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3131 | 3197 | +€4,49 | 42,8% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3131 | 3197 | +€4,39 | 41,2% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3130 | 3196 | +€2,94 | 42,2% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3127 | 3193 | +€1,20 | 40,2% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3121 | 3187 | +€4,88 | 32,9% | 410 | 375 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3117 | 3183 | €-1,62 | 31,4% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3114 | 3180 | €-2,19 | 28,7% | 308 | 804 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3100 | 3166 | €-6,67 | 26,9% | 257 | 878 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3097 | 3163 | +€3,79 | 35,7% | 198 | 593 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3006 | 3072 | €-6,91 | 32,7% | 543 | 625 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2982 | 3048 | €-12,52 | 21,5% | 256 | 954 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
