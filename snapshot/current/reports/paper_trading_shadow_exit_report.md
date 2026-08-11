# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T22:25:06+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **396**
- Scenari virtuali ancora attivi: **11224**
- Gruppi in attesa dell'uscita originale: **256**
- Gruppi con originale chiuso ma Shadow ancora attive: **140**
- Confronti completati: **148591**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3809 | 3875 | +€7,78 | 50,2% | 1044 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3809 | 3875 | +€4,39 | 40,8% | 891 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3809 | 3875 | +€3,86 | 47,4% | 1159 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3808 | 3874 | +€6,66 | 49,1% | 1032 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3808 | 3874 | +€5,35 | 47,3% | 1042 | 113 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3807 | 3873 | +€6,36 | 42,6% | 816 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3807 | 3873 | +€4,74 | 42,0% | 773 | 161 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3807 | 3873 | +€3,94 | 41,3% | 679 | 256 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3807 | 3873 | €-1,23 | 45,3% | 775 | 573 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3804 | 3870 | +€5,31 | 33,0% | 475 | 418 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3799 | 3865 | +€4,46 | 35,8% | 227 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3799 | 3865 | +€0,93 | 32,9% | 398 | 756 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3794 | 3860 | €-0,39 | 30,1% | 325 | 927 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3791 | 3857 | €-5,29 | 26,8% | 274 | 1074 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3789 | 3855 | +€4,00 | 47,4% | 980 | 160 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3780 | 3846 | €-0,65 | 40,2% | 450 | 805 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3778 | 3844 | +€2,20 | 39,7% | 592 | 402 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3739 | 3805 | €-3,95 | 32,2% | 600 | 810 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3729 | 3795 | €-8,41 | 22,6% | 274 | 1166 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3701 | 3767 | €-5,38 | 30,9% | 200 | 1105 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
