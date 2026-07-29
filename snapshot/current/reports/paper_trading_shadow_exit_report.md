# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T08:08:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **535**
- Scenari virtuali ancora attivi: **8125**
- Gruppi in attesa dell'uscita originale: **165**
- Gruppi con originale chiuso ma Shadow ancora attive: **370**
- Confronti completati: **108487**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3034 | 3099 | €-1,79 | 46,6% | 641 | 477 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3027 | 3092 | +€8,77 | 51,6% | 874 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3027 | 3092 | +€7,12 | 50,7% | 876 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3027 | 3092 | +€4,60 | 48,6% | 973 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3020 | 3085 | +€5,06 | 49,3% | 883 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3018 | 3083 | +€3,58 | 49,0% | 828 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3009 | 3074 | +€6,33 | 44,0% | 694 | 81 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3009 | 3074 | +€4,46 | 43,6% | 671 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3009 | 3074 | +€4,32 | 41,8% | 762 | 79 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3009 | 3074 | +€2,91 | 42,9% | 586 | 193 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3007 | 3072 | +€1,15 | 40,9% | 508 | 355 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3002 | 3067 | €-1,68 | 32,3% | 364 | 655 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2992 | 3057 | €-1,60 | 39,5% | 372 | 720 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2986 | 3051 | €-2,04 | 29,9% | 307 | 767 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2968 | 3033 | €-4,97 | 32,5% | 169 | 941 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2934 | 2999 | +€4,76 | 32,8% | 410 | 337 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2886 | 2951 | €-6,25 | 27,7% | 256 | 789 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2879 | 2944 | +€4,19 | 36,4% | 198 | 518 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2821 | 2886 | €-6,07 | 33,5% | 524 | 563 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2765 | 2830 | €-11,84 | 22,7% | 255 | 839 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
