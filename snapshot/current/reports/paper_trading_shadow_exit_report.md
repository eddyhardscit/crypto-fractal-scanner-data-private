# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T12:08:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **525**
- Scenari virtuali ancora attivi: **7805**
- Gruppi in attesa dell'uscita originale: **157**
- Gruppi con originale chiuso ma Shadow ancora attive: **368**
- Confronti completati: **108889**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3042 | 3107 | €-1,29 | 40,3% | 372 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3042 | 3107 | €-1,74 | 46,6% | 641 | 477 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3030 | 3095 | +€8,81 | 51,7% | 874 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3030 | 3095 | +€7,15 | 50,7% | 876 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3030 | 3095 | +€4,64 | 48,6% | 973 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3023 | 3088 | +€5,10 | 49,3% | 883 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3021 | 3086 | +€3,61 | 49,0% | 828 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3012 | 3077 | +€6,33 | 43,9% | 694 | 81 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3012 | 3077 | +€4,46 | 43,5% | 671 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3012 | 3077 | +€4,32 | 41,8% | 762 | 79 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3012 | 3077 | +€2,91 | 42,9% | 586 | 193 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3010 | 3075 | +€1,15 | 40,8% | 508 | 355 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3005 | 3070 | €-1,68 | 32,3% | 364 | 655 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2989 | 3054 | €-2,04 | 29,8% | 307 | 767 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2978 | 3043 | €-4,93 | 32,5% | 169 | 943 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2938 | 3003 | +€4,73 | 32,8% | 410 | 338 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2889 | 2954 | €-6,24 | 27,7% | 256 | 789 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2883 | 2948 | +€4,16 | 36,4% | 198 | 519 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2838 | 2903 | €-6,18 | 33,4% | 524 | 577 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2788 | 2853 | €-11,61 | 22,7% | 255 | 854 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
