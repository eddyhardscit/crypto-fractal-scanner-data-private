# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T00:53:39+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **261**
- Scenari virtuali ancora attivi: **3030**
- Gruppi in attesa dell'uscita originale: **160**
- Gruppi con originale chiuso ma Shadow ancora attive: **101**
- Confronti completati: **6131**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 280 | 329 | +€6,91 | 48,6% | 77 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 280 | 329 | +€4,92 | 46,8% | 76 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 280 | 329 | +€2,98 | 45,9% | 77 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 280 | 329 | +€2,71 | 45,9% | 86 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 280 | 329 | +€0,88 | 44,7% | 72 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 278 | 332 | €-4,50 | 44,0% | 70 | 43 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 267 | 316 | +€2,00 | 39,9% | 62 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 267 | 316 | +€0,11 | 37,7% | 69 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 265 | 314 | +€0,17 | 36,6% | 62 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 265 | 314 | €-1,73 | 38,2% | 48 | 29 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 265 | 314 | €-7,03 | 27,4% | 20 | 83 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 262 | 311 | €-2,29 | 34,4% | 25 | 63 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 256 | 305 | €-10,09 | 24,3% | 15 | 90 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 252 | 306 | +€0,06 | 36,9% | 34 | 51 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 245 | 294 | €-1,29 | 30,6% | 32 | 30 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 239 | 288 | €-7,28 | 28,8% | 53 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 229 | 278 | +€2,62 | 35,6% | 15 | 33 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 220 | 274 | €-3,73 | 31,4% | 17 | 58 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 219 | 268 | €-15,64 | 22,0% | 12 | 70 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 208 | 256 | €-14,12 | 22,7% | 11 | 60 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
