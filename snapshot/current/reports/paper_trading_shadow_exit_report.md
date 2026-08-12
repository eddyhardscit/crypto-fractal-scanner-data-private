# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T14:39:17+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **397**
- Scenari virtuali ancora attivi: **9274**
- Gruppi in attesa dell'uscita originale: **247**
- Gruppi con originale chiuso ma Shadow ancora attive: **150**
- Confronti completati: **165874**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4151 | 4217 | +€8,70 | 50,7% | 1071 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4151 | 4217 | +€7,79 | 49,6% | 1063 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4151 | 4217 | +€6,44 | 47,9% | 1074 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4151 | 4217 | +€5,13 | 48,2% | 1011 | 166 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4151 | 4217 | +€5,09 | 48,1% | 1186 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4145 | 4211 | +€6,94 | 42,9% | 838 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4145 | 4211 | +€5,33 | 42,4% | 794 | 165 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4145 | 4211 | +€5,13 | 41,2% | 913 | 94 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4145 | 4211 | +€4,47 | 41,7% | 701 | 260 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4141 | 4207 | +€2,82 | 40,3% | 602 | 429 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4135 | 4201 | +€1,22 | 33,5% | 414 | 786 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4133 | 4199 | €-0,20 | 30,7% | 327 | 980 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4130 | 4196 | €-4,80 | 27,5% | 276 | 1127 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4115 | 4181 | €-0,08 | 46,2% | 809 | 575 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4110 | 4176 | €-3,51 | 32,9% | 609 | 887 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4108 | 4174 | €-0,57 | 39,7% | 462 | 863 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4104 | 4170 | +€4,95 | 32,6% | 486 | 442 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4104 | 4170 | €-8,35 | 23,4% | 276 | 1261 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4079 | 4145 | +€4,02 | 35,3% | 236 | 700 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4077 | 4143 | €-5,56 | 30,9% | 209 | 1194 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
