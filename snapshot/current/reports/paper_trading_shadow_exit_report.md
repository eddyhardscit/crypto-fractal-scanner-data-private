# Block 3 — Shadow Exit Engine

Generato: 2026-07-22T02:53:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **268**
- Scenari virtuali ancora attivi: **3034**
- Gruppi in attesa dell'uscita originale: **163**
- Gruppi con originale chiuso ma Shadow ancora attive: **105**
- Confronti completati: **6203**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 284 | 333 | +€6,87 | 48,3% | 80 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 284 | 333 | +€4,87 | 46,5% | 79 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 284 | 333 | +€2,92 | 45,6% | 80 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 284 | 333 | +€2,57 | 45,6% | 89 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 284 | 333 | +€0,81 | 44,4% | 75 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 281 | 335 | €-4,46 | 43,9% | 70 | 45 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 271 | 320 | +€2,02 | 40,0% | 64 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 271 | 320 | +€0,19 | 37,2% | 64 | 22 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 271 | 320 | +€0,09 | 37,8% | 71 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 271 | 320 | €-1,72 | 37,8% | 51 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 268 | 317 | €-2,30 | 34,1% | 27 | 66 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 268 | 317 | €-7,03 | 27,4% | 22 | 83 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 259 | 308 | €-10,12 | 24,4% | 17 | 90 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 254 | 308 | +€0,01 | 37,0% | 34 | 52 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 248 | 297 | €-1,22 | 30,6% | 32 | 30 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 242 | 291 | €-7,41 | 28,9% | 55 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 232 | 281 | +€2,75 | 36,3% | 15 | 33 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 222 | 271 | €-15,69 | 22,1% | 14 | 70 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 220 | 274 | €-3,73 | 31,4% | 17 | 58 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 211 | 259 | €-14,19 | 22,8% | 13 | 60 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
