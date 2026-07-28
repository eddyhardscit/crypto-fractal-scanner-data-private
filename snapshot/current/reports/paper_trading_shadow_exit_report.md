# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T16:39:02+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **650**
- Scenari virtuali ancora attivi: **9982**
- Gruppi in attesa dell'uscita originale: **201**
- Gruppi con originale chiuso ma Shadow ancora attive: **449**
- Confronti completati: **98386**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2833 | 2898 | €-2,54 | 45,2% | 623 | 446 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2816 | 2881 | +€8,24 | 50,6% | 840 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2816 | 2881 | +€6,58 | 49,6% | 842 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2816 | 2881 | +€3,94 | 47,3% | 938 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2809 | 2874 | +€4,48 | 48,0% | 849 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2800 | 2865 | €-2,34 | 38,5% | 364 | 685 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2791 | 2856 | +€3,06 | 47,9% | 795 | 107 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2774 | 2839 | +€6,48 | 43,6% | 672 | 80 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2774 | 2839 | +€4,21 | 41,2% | 741 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2773 | 2838 | +€4,59 | 43,4% | 642 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2773 | 2838 | +€3,03 | 42,8% | 556 | 189 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2767 | 2832 | €-2,30 | 32,0% | 355 | 613 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2754 | 2819 | +€1,26 | 40,8% | 478 | 334 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2751 | 2816 | €-2,47 | 29,4% | 301 | 719 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2700 | 2765 | +€4,96 | 32,3% | 403 | 310 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2686 | 2751 | €-4,92 | 32,1% | 169 | 829 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2646 | 2711 | €-7,54 | 26,5% | 250 | 751 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2636 | 2701 | +€4,56 | 36,4% | 196 | 469 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2628 | 2693 | €-7,18 | 32,2% | 502 | 533 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2548 | 2613 | €-13,35 | 21,6% | 249 | 804 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
