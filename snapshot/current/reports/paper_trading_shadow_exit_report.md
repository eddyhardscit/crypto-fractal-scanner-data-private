# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T03:24:15+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **420**
- Scenari virtuali ancora attivi: **11594**
- Gruppi in attesa dell'uscita originale: **284**
- Gruppi con originale chiuso ma Shadow ancora attive: **136**
- Confronti completati: **150004**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3844 | 3910 | +€7,76 | 50,4% | 1047 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3844 | 3910 | +€6,76 | 49,4% | 1033 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3844 | 3910 | +€5,42 | 47,6% | 1043 | 114 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3844 | 3910 | +€3,87 | 47,6% | 1161 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3843 | 3909 | +€6,48 | 42,9% | 818 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3843 | 3909 | +€4,84 | 42,3% | 774 | 162 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3843 | 3909 | +€4,50 | 41,1% | 892 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3842 | 3908 | +€4,00 | 41,6% | 680 | 257 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3840 | 3906 | +€0,90 | 32,9% | 414 | 760 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3825 | 3891 | +€4,05 | 47,7% | 981 | 161 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3822 | 3888 | €-1,23 | 45,3% | 776 | 573 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3819 | 3885 | +€5,31 | 33,1% | 476 | 418 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3818 | 3884 | +€2,22 | 40,1% | 593 | 406 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3813 | 3879 | €-0,84 | 40,1% | 450 | 821 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3812 | 3878 | +€4,45 | 35,9% | 227 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3811 | 3877 | €-0,38 | 30,2% | 325 | 929 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3808 | 3874 | €-5,27 | 26,9% | 274 | 1076 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3765 | 3831 | €-5,15 | 31,2% | 200 | 1132 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3753 | 3819 | €-3,92 | 32,3% | 600 | 810 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3742 | 3808 | €-8,38 | 22,7% | 274 | 1166 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
