# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T18:08:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **506**
- Scenari virtuali ancora attivi: **7624**
- Gruppi in attesa dell'uscita originale: **153**
- Gruppi con originale chiuso ma Shadow ancora attive: **353**
- Confronti completati: **109182**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3046 | 3111 | €-1,28 | 40,3% | 372 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3046 | 3111 | €-1,71 | 46,7% | 641 | 477 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3034 | 3099 | +€8,83 | 51,7% | 874 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3034 | 3099 | +€7,18 | 50,8% | 876 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3034 | 3099 | +€4,67 | 48,7% | 973 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3027 | 3092 | +€5,12 | 49,4% | 883 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3025 | 3090 | +€3,63 | 49,1% | 828 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3017 | 3082 | +€6,33 | 43,9% | 694 | 81 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3017 | 3082 | +€4,47 | 43,5% | 671 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3017 | 3082 | +€4,33 | 41,7% | 762 | 79 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3017 | 3082 | +€2,91 | 42,9% | 586 | 193 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3015 | 3080 | +€1,15 | 40,8% | 508 | 355 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3009 | 3074 | €-1,67 | 32,3% | 364 | 655 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3003 | 3068 | €-4,41 | 32,9% | 169 | 945 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2993 | 3058 | €-2,04 | 29,8% | 307 | 767 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2944 | 3009 | +€4,75 | 32,8% | 410 | 338 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2907 | 2972 | €-6,03 | 28,0% | 256 | 789 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2887 | 2952 | +€4,15 | 36,3% | 198 | 519 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2851 | 2916 | €-6,47 | 33,4% | 524 | 586 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2803 | 2868 | €-11,74 | 22,7% | 255 | 863 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
