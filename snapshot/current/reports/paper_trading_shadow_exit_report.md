# Block 3 — Shadow Exit Engine

Generato: 2026-08-09T20:39:06+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **7**
- Scenari virtuali ancora attivi: **144**
- Gruppi in attesa dell'uscita originale: **5**
- Gruppi con originale chiuso ma Shadow ancora attive: **2**
- Confronti completati: **124069**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3293 | 3359 | +€9,09 | 51,5% | 925 | 10 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3293 | 3359 | +€7,46 | 50,6% | 925 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3293 | 3359 | +€6,69 | 43,2% | 711 | 90 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3293 | 3359 | +€6,24 | 49,0% | 926 | 80 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3293 | 3359 | +€5,10 | 33,2% | 412 | 383 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3293 | 3359 | +€4,88 | 48,6% | 1028 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3293 | 3359 | +€4,85 | 42,7% | 687 | 128 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3293 | 3359 | +€4,63 | 48,9% | 868 | 140 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3293 | 3359 | +€4,54 | 41,2% | 779 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3293 | 3359 | +€4,20 | 41,7% | 604 | 217 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3293 | 3359 | +€3,82 | 35,7% | 199 | 624 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3293 | 3359 | +€2,33 | 40,0% | 520 | 377 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3293 | 3359 | €-0,27 | 31,5% | 369 | 699 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3293 | 3359 | €-0,95 | 28,8% | 312 | 837 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3293 | 3359 | €-0,98 | 39,7% | 402 | 737 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3293 | 3359 | €-1,37 | 45,4% | 672 | 502 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3293 | 3359 | €-3,67 | 32,9% | 557 | 715 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3293 | 3359 | €-4,42 | 31,8% | 189 | 1006 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3293 | 3359 | €-5,24 | 27,3% | 261 | 915 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3293 | 3359 | €-8,53 | 22,7% | 261 | 1048 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
