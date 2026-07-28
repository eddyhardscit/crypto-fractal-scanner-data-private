# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T21:53:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **647**
- Scenari virtuali ancora attivi: **10274**
- Gruppi in attesa dell'uscita originale: **206**
- Gruppi con originale chiuso ma Shadow ancora attive: **441**
- Confronti completati: **102779**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2910 | 2975 | +€8,51 | 51,5% | 851 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2910 | 2975 | +€6,85 | 50,6% | 853 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2910 | 2975 | +€4,27 | 48,4% | 950 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2910 | 2975 | €-2,26 | 39,4% | 371 | 717 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2910 | 2975 | €-2,35 | 46,3% | 630 | 446 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2903 | 2968 | +€4,77 | 49,1% | 860 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2887 | 2952 | +€3,40 | 49,0% | 805 | 109 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2869 | 2934 | +€6,37 | 44,5% | 682 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2869 | 2934 | +€4,51 | 44,4% | 652 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2869 | 2934 | +€4,20 | 42,2% | 751 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2869 | 2934 | +€2,97 | 43,8% | 564 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2853 | 2918 | +€1,26 | 41,8% | 486 | 340 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2846 | 2911 | €-2,10 | 33,2% | 355 | 614 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2829 | 2894 | €-2,25 | 30,7% | 301 | 719 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2823 | 2888 | €-4,82 | 33,6% | 169 | 867 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2804 | 2869 | +€4,83 | 33,5% | 403 | 320 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2767 | 2832 | €-6,44 | 28,7% | 250 | 762 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2729 | 2794 | +€4,29 | 37,4% | 196 | 484 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2708 | 2773 | €-6,58 | 33,7% | 504 | 534 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2632 | 2697 | €-12,59 | 23,4% | 249 | 806 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
