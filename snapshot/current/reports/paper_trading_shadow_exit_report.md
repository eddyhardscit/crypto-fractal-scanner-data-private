# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T19:39:17+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **384**
- Scenari virtuali ancora attivi: **8250**
- Gruppi in attesa dell'uscita originale: **235**
- Gruppi con originale chiuso ma Shadow ancora attive: **149**
- Confronti completati: **169654**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4225 | 4291 | +€8,91 | 50,6% | 1084 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4225 | 4291 | +€7,99 | 49,5% | 1076 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4225 | 4291 | +€6,75 | 42,2% | 850 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4225 | 4291 | +€6,65 | 47,8% | 1088 | 114 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4225 | 4291 | +€5,38 | 48,0% | 1200 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4225 | 4291 | +€5,34 | 48,1% | 1023 | 167 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4225 | 4291 | +€5,15 | 41,7% | 806 | 169 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4225 | 4291 | +€4,98 | 40,6% | 925 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4225 | 4291 | +€4,29 | 41,0% | 714 | 264 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4219 | 4285 | +€2,69 | 39,7% | 603 | 442 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4217 | 4283 | +€5,34 | 32,7% | 486 | 446 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4215 | 4281 | +€0,45 | 46,3% | 809 | 575 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4206 | 4272 | +€1,16 | 33,1% | 414 | 791 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4202 | 4268 | €-0,24 | 30,3% | 327 | 985 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4196 | 4262 | €-4,77 | 27,1% | 276 | 1132 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4180 | 4246 | €-3,18 | 33,1% | 610 | 896 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4177 | 4243 | €-8,29 | 23,0% | 276 | 1274 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4175 | 4241 | €-0,45 | 39,4% | 462 | 864 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4153 | 4219 | €-5,53 | 30,4% | 209 | 1208 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4148 | 4214 | +€3,94 | 34,9% | 236 | 704 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
