# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T23:24:54+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **391**
- Scenari virtuali ancora attivi: **11531**
- Gruppi in attesa dell'uscita originale: **257**
- Gruppi con originale chiuso ma Shadow ancora attive: **134**
- Confronti completati: **149197**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3829 | 3895 | +€7,77 | 50,4% | 1046 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3829 | 3895 | +€6,77 | 49,4% | 1032 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3829 | 3895 | +€6,51 | 42,9% | 817 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3829 | 3895 | +€5,43 | 47,5% | 1042 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3829 | 3895 | +€4,86 | 42,3% | 773 | 162 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3829 | 3895 | +€4,52 | 41,1% | 891 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3829 | 3895 | +€3,87 | 47,6% | 1160 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3828 | 3894 | +€4,03 | 41,6% | 679 | 257 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3826 | 3892 | +€0,91 | 32,9% | 414 | 759 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3810 | 3876 | +€4,05 | 47,7% | 980 | 161 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3807 | 3873 | €-1,23 | 45,3% | 775 | 573 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3805 | 3871 | +€5,32 | 33,0% | 475 | 418 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3799 | 3865 | +€4,46 | 35,8% | 227 | 671 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3799 | 3865 | +€2,26 | 40,0% | 592 | 403 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3798 | 3864 | €-0,39 | 30,1% | 325 | 929 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3791 | 3857 | €-0,81 | 40,2% | 450 | 812 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3791 | 3857 | €-5,29 | 26,8% | 274 | 1074 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3739 | 3805 | €-3,95 | 32,2% | 600 | 810 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3729 | 3795 | €-8,41 | 22,6% | 274 | 1166 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3703 | 3769 | €-5,40 | 30,9% | 200 | 1107 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
