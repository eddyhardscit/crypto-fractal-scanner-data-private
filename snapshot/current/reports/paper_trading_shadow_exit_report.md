# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T03:54:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **478**
- Scenari virtuali ancora attivi: **10998**
- Gruppi in attesa dell'uscita originale: **278**
- Gruppi con originale chiuso ma Shadow ancora attive: **200**
- Confronti completati: **178830**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4421 | 4487 | +€8,04 | 50,3% | 1160 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4421 | 4487 | +€7,09 | 49,3% | 1152 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4421 | 4487 | +€6,59 | 42,7% | 903 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4421 | 4487 | +€5,04 | 42,0% | 871 | 171 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4421 | 4487 | +€4,53 | 40,7% | 1001 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4421 | 4487 | +€4,50 | 47,6% | 1288 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4419 | 4485 | +€5,80 | 47,6% | 1164 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4419 | 4485 | +€4,48 | 48,0% | 1092 | 171 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4419 | 4485 | +€4,29 | 41,4% | 762 | 279 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4416 | 4482 | +€2,56 | 40,2% | 639 | 470 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4405 | 4471 | +€0,88 | 33,6% | 454 | 827 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4405 | 4471 | €-0,03 | 31,4% | 327 | 1042 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4401 | 4467 | +€5,21 | 33,0% | 540 | 446 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4395 | 4461 | +€0,37 | 46,4% | 826 | 622 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4363 | 4429 | +€0,37 | 40,6% | 470 | 880 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4361 | 4427 | €-4,70 | 28,0% | 276 | 1179 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4359 | 4425 | +€4,70 | 36,0% | 253 | 705 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4348 | 4414 | €-3,81 | 33,6% | 640 | 926 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4315 | 4381 | €-8,21 | 23,9% | 276 | 1304 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4280 | 4346 | €-5,09 | 31,3% | 209 | 1225 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
