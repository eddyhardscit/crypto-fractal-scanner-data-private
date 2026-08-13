# Block 3 — Shadow Exit Engine

Generato: 2026-08-13T10:06:59+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **504**
- Scenari virtuali ancora attivi: **11356**
- Gruppi in attesa dell'uscita originale: **308**
- Gruppi con originale chiuso ma Shadow ancora attive: **196**
- Confronti completati: **180584**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4453 | 4519 | +€8,04 | 50,3% | 1174 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4453 | 4519 | +€7,09 | 49,2% | 1166 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4453 | 4519 | +€6,56 | 42,6% | 917 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4453 | 4519 | +€5,02 | 41,9% | 883 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4453 | 4519 | +€4,51 | 40,6% | 1015 | 98 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4453 | 4519 | +€4,49 | 47,5% | 1302 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4453 | 4519 | €-0,33 | 46,0% | 839 | 649 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4447 | 4513 | +€5,84 | 47,6% | 1175 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4447 | 4513 | +€4,51 | 48,0% | 1103 | 171 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4447 | 4513 | +€4,27 | 41,3% | 772 | 279 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4447 | 4513 | +€2,55 | 40,2% | 648 | 471 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4441 | 4507 | +€5,28 | 33,0% | 549 | 446 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4437 | 4503 | €-0,75 | 40,0% | 481 | 930 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4434 | 4500 | +€5,19 | 36,6% | 255 | 705 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4429 | 4495 | +€0,84 | 33,5% | 463 | 830 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4425 | 4491 | €-0,07 | 31,4% | 335 | 1042 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4392 | 4458 | €-4,74 | 28,1% | 278 | 1189 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4371 | 4437 | €-3,81 | 33,6% | 647 | 930 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4357 | 4423 | €-8,72 | 23,8% | 278 | 1332 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4346 | 4412 | €-5,91 | 31,2% | 209 | 1260 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
