# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T10:54:01+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **324**
- Scenari virtuali ancora attivi: **4891**
- Gruppi in attesa dell'uscita originale: **41**
- Gruppi con originale chiuso ma Shadow ancora attive: **283**
- Confronti completati: **114075**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3166 | 3232 | €-1,20 | 39,5% | 393 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3166 | 3232 | €-1,50 | 45,8% | 661 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3166 | 3232 | €-4,69 | 31,8% | 181 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3136 | 3202 | +€8,91 | 52,0% | 890 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3136 | 3202 | +€7,27 | 51,1% | 892 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3136 | 3202 | +€4,89 | 49,0% | 989 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3135 | 3201 | +€5,23 | 49,5% | 901 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3133 | 3199 | +€3,74 | 49,2% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3093 | 3159 | +€6,41 | 43,7% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3093 | 3159 | +€4,55 | 43,3% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3093 | 3159 | +€4,44 | 41,7% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3092 | 3158 | +€2,98 | 42,7% | 588 | 200 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3089 | 3155 | +€1,22 | 40,7% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3078 | 3144 | €-1,64 | 31,8% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3075 | 3141 | €-2,21 | 29,1% | 308 | 804 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3067 | 3133 | +€4,94 | 33,2% | 410 | 368 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3060 | 3126 | €-6,80 | 27,3% | 257 | 878 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3040 | 3106 | +€3,76 | 36,0% | 198 | 586 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2988 | 3054 | €-6,95 | 32,8% | 543 | 625 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2942 | 3008 | €-12,69 | 21,8% | 256 | 953 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
