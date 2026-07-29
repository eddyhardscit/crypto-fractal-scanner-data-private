# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T20:23:55+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **476**
- Scenari virtuali ancora attivi: **6889**
- Gruppi in attesa dell'uscita originale: **144**
- Gruppi con originale chiuso ma Shadow ancora attive: **332**
- Confronti completati: **110024**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3055 | 3120 | €-1,18 | 40,5% | 372 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3055 | 3120 | €-1,63 | 46,8% | 641 | 477 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3043 | 3108 | +€8,94 | 51,9% | 874 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3043 | 3108 | +€7,28 | 50,9% | 876 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3043 | 3108 | +€4,78 | 48,8% | 973 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3036 | 3101 | +€5,23 | 49,5% | 883 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3034 | 3099 | +€3,74 | 49,2% | 828 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3031 | 3096 | €-4,71 | 32,6% | 169 | 963 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3027 | 3092 | +€6,31 | 43,8% | 694 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3027 | 3092 | +€4,45 | 43,4% | 671 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3027 | 3092 | +€4,31 | 41,6% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3027 | 3092 | +€2,90 | 42,7% | 586 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3025 | 3090 | +€1,15 | 40,6% | 508 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3020 | 3085 | €-1,67 | 32,2% | 364 | 656 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3004 | 3069 | €-2,04 | 29,7% | 307 | 769 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2997 | 3062 | +€4,70 | 33,0% | 410 | 357 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2932 | 2997 | +€4,06 | 36,3% | 198 | 538 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2931 | 2996 | €-6,17 | 27,7% | 256 | 804 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2862 | 2927 | €-6,38 | 33,6% | 524 | 588 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2829 | 2894 | €-11,80 | 22,5% | 255 | 879 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
