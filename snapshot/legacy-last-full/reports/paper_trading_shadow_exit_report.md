# Block 3 — Shadow Exit Engine

Generato: 2026-08-14T11:09:20+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **647**
- Scenari virtuali ancora attivi: **12041**
- Gruppi in attesa dell'uscita originale: **382**
- Gruppi con originale chiuso ma Shadow ancora attive: **265**
- Confronti completati: **190027**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4647 | 4713 | +€7,76 | 50,8% | 1239 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4647 | 4713 | +€6,85 | 50,0% | 1226 | 58 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4647 | 4713 | +€4,05 | 48,0% | 1377 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4646 | 4712 | +€5,52 | 48,3% | 1240 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4645 | 4711 | +€4,14 | 48,6% | 1168 | 176 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4642 | 4708 | €-0,55 | 46,7% | 876 | 669 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4639 | 4705 | +€6,72 | 43,7% | 970 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4639 | 4705 | +€5,51 | 43,3% | 920 | 173 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4639 | 4705 | +€4,48 | 41,5% | 1082 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4637 | 4703 | +€4,62 | 42,5% | 818 | 284 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4634 | 4700 | +€5,41 | 33,8% | 590 | 456 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4631 | 4697 | +€2,68 | 41,3% | 696 | 476 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4625 | 4691 | +€5,53 | 37,5% | 279 | 715 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4610 | 4676 | €-0,44 | 41,2% | 487 | 957 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4602 | 4668 | €-4,66 | 32,9% | 212 | 1329 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4580 | 4646 | +€1,15 | 35,0% | 488 | 833 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4580 | 4646 | +€0,29 | 32,8% | 354 | 1049 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4572 | 4638 | €-4,20 | 29,7% | 301 | 1207 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4563 | 4629 | €-4,32 | 33,9% | 704 | 964 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4500 | 4566 | €-8,53 | 24,8% | 295 | 1367 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
