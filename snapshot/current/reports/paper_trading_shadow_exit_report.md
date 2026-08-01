# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T22:08:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **268**
- Scenari virtuali ancora attivi: **4273**
- Gruppi in attesa dell'uscita originale: **43**
- Gruppi con originale chiuso ma Shadow ancora attive: **225**
- Confronti completati: **115070**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3173 | 3239 | €-1,19 | 39,5% | 395 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3173 | 3239 | €-1,51 | 45,8% | 663 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3173 | 3239 | €-4,69 | 31,7% | 183 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3155 | 3221 | +€8,88 | 51,8% | 890 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3155 | 3221 | +€7,25 | 50,9% | 892 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3155 | 3221 | +€4,89 | 48,8% | 989 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3154 | 3220 | +€5,22 | 49,4% | 901 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3151 | 3217 | +€3,73 | 49,1% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3139 | 3205 | +€6,31 | 43,1% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3139 | 3205 | +€4,48 | 42,7% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3139 | 3205 | +€4,38 | 41,1% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3138 | 3204 | +€2,93 | 42,1% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3134 | 3200 | +€1,20 | 40,1% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3130 | 3196 | +€4,85 | 32,8% | 410 | 376 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3124 | 3190 | €-1,62 | 31,4% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3122 | 3188 | €-2,19 | 28,6% | 308 | 805 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3108 | 3174 | €-6,67 | 26,9% | 257 | 879 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3105 | 3171 | +€3,77 | 35,6% | 198 | 594 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3007 | 3073 | €-6,92 | 32,7% | 543 | 626 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2990 | 3056 | €-12,50 | 21,5% | 256 | 955 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
