# Block 3 — Shadow Exit Engine

Generato: 2026-08-02T01:09:01+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **259**
- Scenari virtuali ancora attivi: **4035**
- Gruppi in attesa dell'uscita originale: **28**
- Gruppi con originale chiuso ma Shadow ancora attive: **231**
- Confronti completati: **115504**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3179 | 3245 | €-1,19 | 39,4% | 395 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3179 | 3245 | €-1,50 | 45,7% | 663 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3179 | 3245 | €-4,68 | 31,6% | 183 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3170 | 3236 | +€8,84 | 51,8% | 899 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3170 | 3236 | +€7,21 | 50,9% | 901 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3170 | 3236 | +€4,86 | 48,8% | 998 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3169 | 3235 | +€5,20 | 49,3% | 904 | 69 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3157 | 3223 | +€3,73 | 49,1% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3148 | 3214 | +€6,30 | 43,3% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3148 | 3214 | +€4,47 | 42,9% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3148 | 3214 | +€4,37 | 41,3% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3147 | 3213 | +€2,93 | 42,0% | 591 | 206 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3134 | 3200 | +€1,20 | 40,1% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3132 | 3198 | +€4,84 | 32,8% | 410 | 378 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3124 | 3190 | €-1,62 | 31,4% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3124 | 3190 | €-2,20 | 28,6% | 308 | 807 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3114 | 3180 | €-6,70 | 26,8% | 257 | 885 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3111 | 3177 | +€3,71 | 35,5% | 198 | 600 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3015 | 3081 | €-7,02 | 32,6% | 543 | 634 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2999 | 3065 | €-12,53 | 21,4% | 256 | 963 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
