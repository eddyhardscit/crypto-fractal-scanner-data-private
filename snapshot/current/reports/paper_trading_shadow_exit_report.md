# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T10:39:59+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **382**
- Scenari virtuali ancora attivi: **9150**
- Gruppi in attesa dell'uscita originale: **242**
- Gruppi con originale chiuso ma Shadow ancora attive: **140**
- Confronti completati: **161182**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4056 | 4122 | +€8,13 | 49,9% | 1061 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4056 | 4122 | +€7,19 | 48,9% | 1049 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4056 | 4122 | +€5,87 | 47,1% | 1060 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4056 | 4122 | +€4,55 | 47,4% | 997 | 166 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4056 | 4122 | +€4,44 | 47,2% | 1176 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4055 | 4121 | €-0,21 | 46,2% | 803 | 575 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4054 | 4120 | +€6,60 | 42,6% | 832 | 96 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4054 | 4120 | +€5,02 | 42,1% | 788 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4054 | 4120 | +€4,75 | 40,9% | 907 | 92 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4054 | 4120 | +€4,18 | 41,3% | 695 | 258 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4051 | 4117 | +€1,09 | 33,1% | 414 | 777 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4051 | 4117 | €-0,70 | 39,6% | 460 | 861 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4047 | 4113 | +€2,57 | 40,1% | 593 | 425 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4044 | 4110 | €-0,32 | 30,2% | 327 | 968 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4042 | 4108 | €-4,97 | 27,2% | 276 | 1115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4028 | 4094 | +€5,37 | 33,0% | 486 | 419 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4004 | 4070 | +€4,52 | 35,8% | 236 | 672 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4001 | 4067 | €-3,72 | 32,3% | 604 | 861 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3994 | 4060 | €-5,20 | 31,3% | 209 | 1158 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3990 | 4056 | €-8,24 | 23,1% | 276 | 1221 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
