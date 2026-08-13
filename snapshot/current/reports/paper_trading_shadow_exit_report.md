# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T02:54:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **495**
- Scenari virtuali ancora attivi: **11609**
- Gruppi in attesa dell'uscita originale: **286**
- Gruppi con originale chiuso ma Shadow ancora attive: **209**
- Confronti completati: **176251**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4372 | 4438 | +€8,00 | 50,2% | 1160 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4372 | 4438 | +€7,04 | 49,1% | 1152 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4372 | 4438 | +€6,53 | 42,5% | 903 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4372 | 4438 | +€4,97 | 41,8% | 871 | 171 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4372 | 4438 | +€4,45 | 40,5% | 1001 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4372 | 4438 | +€4,42 | 47,4% | 1288 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4367 | 4433 | +€5,74 | 47,4% | 1164 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4367 | 4433 | +€4,40 | 47,8% | 1092 | 171 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4363 | 4429 | +€4,15 | 41,0% | 762 | 279 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4357 | 4423 | +€2,44 | 39,8% | 639 | 468 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4350 | 4416 | +€5,14 | 32,7% | 540 | 446 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4346 | 4412 | +€0,24 | 46,2% | 826 | 622 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4342 | 4408 | +€0,76 | 33,2% | 454 | 821 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4342 | 4408 | €-0,13 | 31,0% | 327 | 1036 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4312 | 4378 | €-4,88 | 27,6% | 276 | 1179 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4310 | 4376 | +€4,62 | 35,7% | 253 | 705 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4306 | 4372 | +€0,21 | 40,3% | 470 | 876 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4299 | 4365 | €-3,98 | 33,2% | 640 | 926 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4266 | 4332 | €-8,44 | 23,5% | 276 | 1304 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4231 | 4297 | €-5,28 | 30,9% | 209 | 1225 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
