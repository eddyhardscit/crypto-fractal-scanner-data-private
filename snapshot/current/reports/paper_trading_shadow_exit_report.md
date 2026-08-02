# Block 3 — Shadow Exit Engine

Generato: 2026-08-02T13:25:46+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **250**
- Scenari virtuali ancora attivi: **3780**
- Gruppi in attesa dell'uscita originale: **32**
- Gruppi con originale chiuso ma Shadow ancora attive: **218**
- Confronti completati: **116222**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3193 | 3259 | €-1,49 | 45,8% | 665 | 486 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3190 | 3256 | €-1,16 | 39,6% | 396 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3181 | 3247 | €-4,68 | 31,6% | 184 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3177 | 3243 | +€8,82 | 51,7% | 902 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3177 | 3243 | +€7,19 | 50,8% | 904 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3177 | 3243 | +€5,18 | 49,2% | 907 | 69 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3177 | 3243 | +€4,85 | 48,7% | 1001 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3174 | 3240 | +€3,72 | 49,2% | 850 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3162 | 3228 | +€6,27 | 43,2% | 698 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3162 | 3228 | +€4,45 | 42,8% | 675 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3162 | 3228 | +€4,35 | 41,1% | 764 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3162 | 3228 | +€2,91 | 41,8% | 594 | 206 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3159 | 3225 | +€1,20 | 40,1% | 512 | 362 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3156 | 3222 | +€4,81 | 32,9% | 410 | 378 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3146 | 3212 | €-1,58 | 31,5% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3146 | 3212 | €-2,16 | 28,7% | 309 | 807 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3136 | 3202 | €-6,64 | 26,9% | 258 | 885 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3132 | 3198 | +€3,70 | 35,6% | 198 | 600 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3029 | 3095 | €-7,01 | 32,4% | 544 | 635 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3014 | 3080 | €-12,34 | 21,4% | 257 | 964 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
