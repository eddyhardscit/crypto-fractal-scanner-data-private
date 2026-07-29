# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T02:53:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **670**
- Scenari virtuali ancora attivi: **10988**
- Gruppi in attesa dell'uscita originale: **237**
- Gruppi con originale chiuso ma Shadow ancora attive: **433**
- Confronti completati: **104702**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2949 | 3014 | +€8,30 | 51,3% | 861 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2949 | 3014 | +€6,65 | 50,3% | 863 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2949 | 3014 | +€4,08 | 48,1% | 960 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2948 | 3013 | €-2,33 | 46,3% | 635 | 457 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2942 | 3007 | +€4,57 | 48,9% | 870 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2940 | 3005 | +€3,12 | 48,6% | 815 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2932 | 2997 | €-2,23 | 39,2% | 371 | 720 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2917 | 2982 | +€6,22 | 44,1% | 692 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2917 | 2982 | +€4,35 | 44,0% | 662 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2917 | 2982 | +€4,10 | 41,9% | 761 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2917 | 2982 | +€2,81 | 43,4% | 574 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2915 | 2980 | +€1,05 | 41,2% | 496 | 354 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2902 | 2967 | €-5,00 | 33,1% | 169 | 917 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2887 | 2952 | €-2,10 | 32,8% | 360 | 621 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2871 | 2936 | €-2,28 | 30,3% | 306 | 727 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2853 | 2918 | +€4,65 | 33,0% | 410 | 330 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2806 | 2871 | €-6,36 | 28,3% | 255 | 767 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2794 | 2859 | +€4,37 | 37,1% | 198 | 496 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2743 | 2808 | €-6,23 | 33,6% | 509 | 539 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2676 | 2741 | €-12,12 | 23,2% | 254 | 811 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
