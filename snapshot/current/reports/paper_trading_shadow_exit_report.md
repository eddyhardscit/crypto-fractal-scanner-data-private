# Block 3 — Shadow Exit Engine

Generato: 2026-07-28T17:39:25+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **690**
- Scenari virtuali ancora attivi: **12386**
- Gruppi in attesa dell'uscita originale: **251**
- Gruppi con originale chiuso ma Shadow ancora attive: **439**
- Confronti completati: **98976**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 2843 | 2908 | €-2,53 | 45,2% | 626 | 446 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 2826 | 2891 | +€8,25 | 50,5% | 843 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2826 | 2891 | +€6,59 | 49,5% | 845 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2826 | 2891 | +€3,97 | 47,3% | 941 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2819 | 2884 | +€4,49 | 48,0% | 852 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2815 | 2880 | €-2,39 | 38,5% | 367 | 690 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2803 | 2868 | +€3,07 | 47,9% | 797 | 109 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2784 | 2849 | +€6,45 | 43,5% | 674 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2784 | 2849 | +€4,55 | 43,3% | 644 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2784 | 2849 | +€4,19 | 41,1% | 743 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2782 | 2847 | +€3,01 | 42,7% | 556 | 190 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2774 | 2839 | €-2,30 | 31,9% | 355 | 613 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2765 | 2830 | +€1,25 | 40,7% | 478 | 337 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2758 | 2823 | €-2,46 | 29,3% | 301 | 719 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2719 | 2784 | +€4,72 | 32,1% | 403 | 320 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2706 | 2771 | €-5,05 | 31,9% | 169 | 840 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2696 | 2761 | €-6,77 | 27,2% | 250 | 762 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2653 | 2718 | +€4,32 | 36,1% | 196 | 479 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2638 | 2703 | €-7,18 | 32,3% | 504 | 534 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2558 | 2623 | €-13,29 | 21,5% | 249 | 806 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
