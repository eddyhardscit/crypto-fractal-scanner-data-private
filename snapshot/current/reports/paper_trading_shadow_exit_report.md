# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T00:25:20+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **402**
- Scenari virtuali ancora attivi: **11907**
- Gruppi in attesa dell'uscita originale: **268**
- Gruppi con originale chiuso ma Shadow ancora attive: **134**
- Confronti completati: **149266**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3830 | 3896 | +€7,79 | 50,4% | 1046 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3830 | 3896 | +€6,79 | 49,4% | 1032 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3830 | 3896 | +€6,51 | 42,9% | 817 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3830 | 3896 | +€5,45 | 47,6% | 1042 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3830 | 3896 | +€4,86 | 42,3% | 773 | 162 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3830 | 3896 | +€4,52 | 41,1% | 891 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3830 | 3896 | +€3,88 | 47,6% | 1160 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3829 | 3895 | +€4,03 | 41,6% | 679 | 257 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3828 | 3894 | +€0,90 | 32,9% | 414 | 760 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3811 | 3877 | +€4,07 | 47,7% | 980 | 161 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3809 | 3875 | €-1,23 | 45,3% | 775 | 573 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3806 | 3872 | +€5,32 | 33,0% | 475 | 418 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3805 | 3871 | +€2,24 | 40,0% | 592 | 406 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3800 | 3866 | +€4,46 | 35,9% | 227 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3799 | 3865 | €-0,39 | 30,1% | 325 | 929 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3796 | 3862 | €-5,29 | 26,8% | 274 | 1076 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3792 | 3858 | €-0,81 | 40,2% | 450 | 812 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3740 | 3806 | €-3,94 | 32,2% | 600 | 810 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3730 | 3796 | €-8,41 | 22,6% | 274 | 1166 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3709 | 3775 | €-5,44 | 30,9% | 200 | 1112 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
