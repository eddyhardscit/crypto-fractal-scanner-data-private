# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T23:53:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **692**
- Scenari virtuali ancora attivi: **12541**
- Gruppi in attesa dell'uscita originale: **265**
- Gruppi con originale chiuso ma Shadow ancora attive: **427**
- Confronti completati: **103508**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2931 | 2996 | €-2,37 | 46,4% | 630 | 454 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2920 | 2985 | +€8,48 | 51,5% | 851 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2920 | 2985 | +€6,83 | 50,5% | 853 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2920 | 2985 | +€4,26 | 48,3% | 950 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2917 | 2982 | €-2,26 | 39,3% | 371 | 717 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2913 | 2978 | +€4,76 | 49,0% | 860 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2911 | 2976 | +€3,32 | 48,7% | 805 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2888 | 2953 | +€6,34 | 44,3% | 682 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2888 | 2953 | +€4,48 | 44,2% | 652 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2888 | 2953 | +€4,17 | 42,1% | 751 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2888 | 2953 | +€2,95 | 43,6% | 564 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2886 | 2951 | +€1,20 | 41,4% | 486 | 354 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2869 | 2934 | €-4,84 | 33,4% | 169 | 897 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2868 | 2933 | €-2,13 | 33,0% | 358 | 617 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2852 | 2917 | €-2,31 | 30,5% | 304 | 723 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2824 | 2889 | +€4,80 | 33,3% | 403 | 324 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2787 | 2852 | €-6,41 | 28,5% | 253 | 763 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2749 | 2814 | +€4,26 | 37,1% | 196 | 488 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2723 | 2788 | €-6,35 | 33,6% | 507 | 535 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2656 | 2721 | €-12,28 | 23,3% | 252 | 807 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
