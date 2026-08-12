# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T05:24:22+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **383**
- Scenari virtuali ancora attivi: **9749**
- Gruppi in attesa dell'uscita originale: **234**
- Gruppi con originale chiuso ma Shadow ancora attive: **149**
- Confronti completati: **152865**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3907 | 3973 | +€7,47 | 49,7% | 1060 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3907 | 3973 | +€6,47 | 48,7% | 1046 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3907 | 3973 | +€5,15 | 46,9% | 1056 | 114 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3907 | 3973 | +€3,64 | 46,9% | 1174 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3907 | 3973 | €-0,73 | 45,9% | 789 | 575 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3906 | 3972 | +€6,27 | 42,3% | 831 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3906 | 3972 | +€4,64 | 41,7% | 787 | 162 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3906 | 3972 | +€4,35 | 40,6% | 905 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3905 | 3971 | +€3,80 | 41,0% | 693 | 257 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3890 | 3956 | +€0,89 | 32,6% | 414 | 760 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3888 | 3954 | +€3,79 | 47,0% | 994 | 161 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3882 | 3948 | +€5,22 | 32,6% | 476 | 418 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3870 | 3936 | €-0,81 | 39,8% | 450 | 821 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3868 | 3934 | +€2,20 | 39,6% | 593 | 406 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3862 | 3928 | +€4,40 | 35,5% | 227 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3861 | 3927 | €-0,38 | 29,8% | 325 | 929 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3858 | 3924 | €-5,20 | 26,6% | 274 | 1076 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3828 | 3894 | €-5,10 | 31,0% | 200 | 1136 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3803 | 3869 | €-3,87 | 32,0% | 600 | 810 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3792 | 3858 | €-8,27 | 22,5% | 274 | 1166 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
