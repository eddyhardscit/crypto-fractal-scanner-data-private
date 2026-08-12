# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T15:39:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **371**
- Scenari virtuali ancora attivi: **8532**
- Gruppi in attesa dell'uscita originale: **222**
- Gruppi con originale chiuso ma Shadow ancora attive: **149**
- Confronti completati: **168959**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4209 | 4275 | +€9,03 | 50,7% | 1074 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4209 | 4275 | +€8,12 | 49,7% | 1066 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4209 | 4275 | +€6,77 | 48,0% | 1077 | 114 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4209 | 4275 | +€5,49 | 48,2% | 1189 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4209 | 4275 | +€5,46 | 48,2% | 1014 | 166 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4207 | 4273 | +€6,81 | 42,3% | 841 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4207 | 4273 | +€5,22 | 41,8% | 797 | 169 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4207 | 4273 | +€5,03 | 40,7% | 916 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4207 | 4273 | +€4,37 | 41,1% | 704 | 264 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4201 | 4267 | +€2,75 | 39,8% | 602 | 433 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4200 | 4266 | +€1,17 | 33,1% | 414 | 790 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4196 | 4262 | €-0,25 | 30,3% | 327 | 985 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4191 | 4257 | €-4,78 | 27,2% | 276 | 1132 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4189 | 4255 | +€0,28 | 46,0% | 809 | 575 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4174 | 4240 | €-3,19 | 33,2% | 609 | 896 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4172 | 4238 | €-8,30 | 23,0% | 276 | 1274 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4169 | 4235 | +€4,83 | 32,2% | 486 | 446 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4163 | 4229 | €-0,45 | 39,3% | 462 | 863 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4141 | 4207 | +€3,91 | 34,9% | 236 | 704 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4136 | 4202 | €-5,53 | 30,5% | 209 | 1198 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
