# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T22:53:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **654**
- Scenari virtuali ancora attivi: **10893**
- Gruppi in attesa dell'uscita originale: **226**
- Gruppi con originale chiuso ma Shadow ancora attive: **428**
- Confronti completati: **103272**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2917 | 2982 | +€8,49 | 51,4% | 851 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2917 | 2982 | +€6,84 | 50,4% | 853 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2917 | 2982 | +€4,26 | 48,3% | 950 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2917 | 2982 | €-2,26 | 39,3% | 371 | 717 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2917 | 2982 | €-2,32 | 46,4% | 630 | 446 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2910 | 2975 | +€4,76 | 48,9% | 860 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2908 | 2973 | +€3,32 | 48,6% | 805 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2881 | 2946 | +€6,35 | 44,3% | 682 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2881 | 2946 | +€4,49 | 44,2% | 652 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2881 | 2946 | +€4,18 | 42,1% | 751 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2881 | 2946 | +€2,96 | 43,6% | 564 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2879 | 2944 | +€1,20 | 41,4% | 486 | 354 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2858 | 2923 | €-2,10 | 33,1% | 355 | 614 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2841 | 2906 | €-2,24 | 30,6% | 301 | 719 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2836 | 2901 | €-4,80 | 33,4% | 169 | 873 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2820 | 2885 | +€4,80 | 33,3% | 403 | 324 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2779 | 2844 | €-6,42 | 28,6% | 250 | 762 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2745 | 2810 | +€4,27 | 37,2% | 196 | 488 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2719 | 2784 | €-6,35 | 33,7% | 504 | 534 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2648 | 2713 | €-12,30 | 23,4% | 249 | 806 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
