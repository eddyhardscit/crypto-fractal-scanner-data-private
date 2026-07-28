# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T18:53:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **684**
- Scenari virtuali ancora attivi: **12014**
- Gruppi in attesa dell'uscita originale: **239**
- Gruppi con originale chiuso ma Shadow ancora attive: **445**
- Confronti completati: **99295**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2847 | 2912 | €-2,55 | 45,2% | 630 | 446 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2839 | 2904 | +€8,17 | 50,5% | 851 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2839 | 2904 | +€6,50 | 49,5% | 853 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2839 | 2904 | +€3,84 | 47,2% | 950 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2832 | 2897 | +€4,39 | 47,9% | 860 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2827 | 2892 | €-2,42 | 38,3% | 371 | 698 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2816 | 2881 | +€2,98 | 47,9% | 805 | 109 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2797 | 2862 | +€6,34 | 43,3% | 682 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2797 | 2862 | +€4,43 | 43,2% | 652 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2797 | 2862 | +€4,10 | 41,0% | 751 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2797 | 2862 | +€2,87 | 42,5% | 564 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2781 | 2846 | +€1,11 | 40,5% | 486 | 340 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2779 | 2844 | €-2,31 | 31,8% | 355 | 614 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2762 | 2827 | €-2,46 | 29,3% | 301 | 719 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2732 | 2797 | +€4,71 | 32,0% | 403 | 320 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2710 | 2775 | €-5,04 | 31,9% | 169 | 840 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2700 | 2765 | €-6,76 | 27,1% | 250 | 762 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2657 | 2722 | +€4,31 | 36,1% | 196 | 479 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2642 | 2707 | €-7,17 | 32,2% | 504 | 534 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2565 | 2630 | €-13,07 | 21,6% | 249 | 806 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
