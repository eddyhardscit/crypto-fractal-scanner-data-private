# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T01:24:27+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **406**
- Scenari virtuali ancora attivi: **11735**
- Gruppi in attesa dell'uscita originale: **272**
- Gruppi con originale chiuso ma Shadow ancora attive: **134**
- Confronti completati: **149589**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3836 | 3902 | +€7,78 | 50,5% | 1046 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3836 | 3902 | +€6,78 | 49,5% | 1032 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3836 | 3902 | +€6,50 | 43,0% | 817 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3836 | 3902 | +€5,44 | 47,6% | 1042 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3836 | 3902 | +€4,86 | 42,4% | 773 | 162 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3836 | 3902 | +€4,51 | 41,2% | 891 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3836 | 3902 | +€3,88 | 47,7% | 1160 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3835 | 3901 | +€4,02 | 41,7% | 679 | 257 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3834 | 3900 | +€0,90 | 33,0% | 414 | 760 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3817 | 3883 | +€4,06 | 47,8% | 980 | 161 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3815 | 3881 | €-1,22 | 45,4% | 775 | 573 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3812 | 3878 | +€5,32 | 33,1% | 475 | 418 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3811 | 3877 | +€2,24 | 40,1% | 592 | 406 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3806 | 3872 | +€4,46 | 36,0% | 227 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3805 | 3871 | €-0,39 | 30,2% | 325 | 929 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3802 | 3868 | €-5,28 | 26,9% | 274 | 1076 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3800 | 3866 | €-0,82 | 40,2% | 450 | 814 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3746 | 3812 | €-3,93 | 32,3% | 600 | 810 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3736 | 3802 | €-8,39 | 22,8% | 274 | 1166 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3733 | 3799 | €-5,09 | 31,3% | 200 | 1112 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
