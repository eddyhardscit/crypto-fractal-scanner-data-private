# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T19:40:14+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **544**
- Scenari virtuali ancora attivi: **9994**
- Gruppi in attesa dell'uscita originale: **348**
- Gruppi con originale chiuso ma Shadow ancora attive: **196**
- Confronti completati: **181494**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4466 | 4532 | +€7,94 | 50,2% | 1181 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4466 | 4532 | +€6,99 | 49,2% | 1173 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4466 | 4532 | +€6,52 | 42,6% | 924 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4466 | 4532 | +€5,03 | 42,0% | 885 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4466 | 4532 | +€4,46 | 40,6% | 1022 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4466 | 4532 | +€4,40 | 47,5% | 1309 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4466 | 4532 | €-0,38 | 46,0% | 846 | 649 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4466 | 4532 | €-0,71 | 40,1% | 482 | 940 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4465 | 4531 | +€5,72 | 47,6% | 1182 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4464 | 4530 | +€4,41 | 47,9% | 1109 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4459 | 4525 | +€5,29 | 33,1% | 551 | 447 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4458 | 4524 | +€4,26 | 41,3% | 772 | 284 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4458 | 4524 | +€2,53 | 40,2% | 648 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4450 | 4516 | +€5,20 | 36,7% | 256 | 706 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4447 | 4513 | +€0,88 | 33,7% | 464 | 833 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4443 | 4509 | €-5,01 | 32,0% | 209 | 1291 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4437 | 4503 | €-0,09 | 31,4% | 335 | 1048 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4402 | 4468 | €-4,74 | 28,1% | 278 | 1193 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4389 | 4455 | €-3,88 | 33,6% | 652 | 934 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4370 | 4436 | €-8,70 | 23,9% | 278 | 1336 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
