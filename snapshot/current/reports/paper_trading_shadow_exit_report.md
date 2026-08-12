# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T07:25:09+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **319**
- Scenari virtuali ancora attivi: **7136**
- Gruppi in attesa dell'uscita originale: **183**
- Gruppi con originale chiuso ma Shadow ancora attive: **136**
- Confronti completati: **160237**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4037 | 4103 | +€8,13 | 49,9% | 1061 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4037 | 4103 | +€7,19 | 48,8% | 1049 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4037 | 4103 | +€6,62 | 42,6% | 832 | 96 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4037 | 4103 | +€5,87 | 47,1% | 1060 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4037 | 4103 | +€5,03 | 42,0% | 788 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4037 | 4103 | +€4,76 | 40,9% | 907 | 92 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4037 | 4103 | +€4,43 | 47,2% | 1176 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4037 | 4103 | +€4,19 | 41,3% | 695 | 258 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4036 | 4102 | +€4,55 | 47,4% | 997 | 165 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4036 | 4102 | €-0,23 | 46,2% | 799 | 575 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4033 | 4099 | +€1,10 | 33,1% | 414 | 774 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4029 | 4095 | +€2,58 | 40,0% | 593 | 424 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4027 | 4093 | €-0,32 | 30,2% | 327 | 966 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4025 | 4091 | €-4,99 | 27,2% | 276 | 1113 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4013 | 4079 | +€5,38 | 32,9% | 486 | 419 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3998 | 4064 | €-0,48 | 39,9% | 460 | 823 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3989 | 4055 | +€4,53 | 35,8% | 236 | 672 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3982 | 4048 | €-3,74 | 32,3% | 602 | 861 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3973 | 4039 | €-8,27 | 23,1% | 276 | 1219 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3971 | 4037 | €-5,24 | 31,2% | 209 | 1155 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
