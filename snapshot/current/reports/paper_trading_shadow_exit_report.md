# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T15:08:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **514**
- Scenari virtuali ancora attivi: **7769**
- Gruppi in attesa dell'uscita originale: **156**
- Gruppi con originale chiuso ma Shadow ancora attive: **358**
- Confronti completati: **108961**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3043 | 3108 | €-1,28 | 40,3% | 372 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3043 | 3108 | €-1,72 | 46,6% | 641 | 477 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3031 | 3096 | +€8,81 | 51,7% | 874 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3031 | 3096 | +€7,16 | 50,7% | 876 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3031 | 3096 | +€4,65 | 48,6% | 973 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3024 | 3089 | +€5,10 | 49,3% | 883 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3022 | 3087 | +€3,62 | 49,0% | 828 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3013 | 3078 | +€6,34 | 44,0% | 694 | 81 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3013 | 3078 | +€4,47 | 43,6% | 671 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3013 | 3078 | +€4,33 | 41,8% | 762 | 79 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3013 | 3078 | +€2,92 | 42,9% | 586 | 193 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3011 | 3076 | +€1,16 | 40,8% | 508 | 355 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3005 | 3070 | €-1,68 | 32,3% | 364 | 655 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2989 | 3054 | €-2,04 | 29,8% | 307 | 767 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2979 | 3044 | €-4,93 | 32,5% | 169 | 943 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2940 | 3005 | +€4,75 | 32,8% | 410 | 338 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2903 | 2968 | €-6,04 | 28,0% | 256 | 789 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2883 | 2948 | +€4,16 | 36,4% | 198 | 519 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2848 | 2913 | €-6,47 | 33,3% | 524 | 586 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2799 | 2864 | €-11,75 | 22,7% | 255 | 863 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
