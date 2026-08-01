# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T13:08:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **300**
- Scenari virtuali ancora attivi: **4467**
- Gruppi in attesa dell'uscita originale: **41**
- Gruppi con originale chiuso ma Shadow ancora attive: **259**
- Confronti completati: **114499**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3166 | 3232 | €-1,20 | 39,5% | 393 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3166 | 3232 | €-1,50 | 45,8% | 661 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3166 | 3232 | €-4,69 | 31,8% | 181 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3141 | 3207 | +€8,90 | 51,9% | 890 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3141 | 3207 | +€7,26 | 51,0% | 892 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3141 | 3207 | +€4,88 | 48,9% | 989 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3140 | 3206 | +€5,23 | 49,4% | 901 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3138 | 3204 | +€3,73 | 49,1% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3117 | 3183 | +€6,36 | 43,4% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3117 | 3183 | +€4,51 | 43,0% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3117 | 3183 | +€4,41 | 41,3% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3116 | 3182 | +€2,95 | 42,4% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3113 | 3179 | +€1,21 | 40,4% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3102 | 3168 | €-1,63 | 31,6% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3099 | 3165 | €-2,20 | 28,8% | 308 | 804 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3091 | 3157 | +€4,90 | 32,9% | 410 | 368 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3084 | 3150 | €-6,74 | 27,0% | 257 | 878 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3064 | 3130 | +€3,73 | 35,7% | 198 | 586 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2993 | 3059 | €-6,94 | 32,8% | 543 | 625 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2966 | 3032 | €-12,59 | 21,6% | 256 | 953 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
