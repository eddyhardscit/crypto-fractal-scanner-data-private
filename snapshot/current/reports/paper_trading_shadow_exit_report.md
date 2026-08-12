# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T22:40:27+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **442**
- Scenari virtuali ancora attivi: **10120**
- Gruppi in attesa dell'uscita originale: **250**
- Gruppi con originale chiuso ma Shadow ancora attive: **192**
- Confronti completati: **172103**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4286 | 4352 | +€8,35 | 50,3% | 1121 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4286 | 4352 | +€7,40 | 49,2% | 1113 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4286 | 4352 | +€6,70 | 42,4% | 865 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4286 | 4352 | +€6,02 | 47,3% | 1134 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4286 | 4352 | +€5,02 | 41,6% | 836 | 169 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4286 | 4352 | +€4,78 | 47,4% | 1249 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4286 | 4352 | +€4,71 | 47,7% | 1062 | 167 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4286 | 4352 | +€4,61 | 40,4% | 962 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4282 | 4348 | +€4,11 | 40,8% | 749 | 264 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4282 | 4348 | +€0,09 | 45,7% | 820 | 616 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4276 | 4342 | +€2,44 | 39,7% | 631 | 442 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4267 | 4333 | +€0,69 | 32,7% | 450 | 802 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4266 | 4332 | +€5,13 | 32,4% | 513 | 446 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4242 | 4308 | €-0,38 | 30,2% | 327 | 1008 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4226 | 4292 | +€4,40 | 35,2% | 242 | 705 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4220 | 4286 | €-3,65 | 32,9% | 637 | 897 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4215 | 4281 | €-0,04 | 39,5% | 470 | 864 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4212 | 4278 | €-4,76 | 27,2% | 276 | 1133 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4190 | 4256 | €-8,27 | 23,0% | 276 | 1275 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4180 | 4246 | €-5,54 | 30,4% | 209 | 1221 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
