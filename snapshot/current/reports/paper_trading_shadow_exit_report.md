# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T08:39:18+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **317**
- Scenari virtuali ancora attivi: **6857**
- Gruppi in attesa dell'uscita originale: **181**
- Gruppi con originale chiuso ma Shadow ancora attive: **136**
- Confronti completati: **160445**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4041 | 4107 | +€8,12 | 49,8% | 1061 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4041 | 4107 | +€7,18 | 48,8% | 1049 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4041 | 4107 | +€6,61 | 42,6% | 832 | 96 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4041 | 4107 | +€5,86 | 47,0% | 1060 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4041 | 4107 | +€5,02 | 42,0% | 788 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4041 | 4107 | +€4,75 | 40,8% | 907 | 92 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4041 | 4107 | +€4,54 | 47,3% | 997 | 166 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4041 | 4107 | +€4,42 | 47,1% | 1176 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4041 | 4107 | +€4,19 | 41,3% | 695 | 258 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4040 | 4106 | €-0,23 | 46,1% | 799 | 575 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4037 | 4103 | +€1,10 | 33,1% | 414 | 774 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4034 | 4100 | +€2,57 | 40,0% | 593 | 425 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4031 | 4097 | €-0,32 | 30,2% | 327 | 966 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4029 | 4095 | €-4,98 | 27,1% | 276 | 1113 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4017 | 4083 | +€5,38 | 32,9% | 486 | 419 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4002 | 4068 | €-0,48 | 39,8% | 460 | 823 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3993 | 4059 | +€4,53 | 35,7% | 236 | 672 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3986 | 4052 | €-3,74 | 32,2% | 602 | 861 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3979 | 4045 | €-5,22 | 31,2% | 209 | 1156 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3977 | 4043 | €-8,27 | 23,1% | 276 | 1219 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
