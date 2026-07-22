# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T23:53:39+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **256**
- Scenari virtuali ancora attivi: **3066**
- Gruppi in attesa dell'uscita originale: **158**
- Gruppi con originale chiuso ma Shadow ancora attive: **98**
- Confronti completati: **6047**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 275 | 324 | +€6,87 | 48,5% | 75 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 275 | 324 | +€4,86 | 46,6% | 74 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 275 | 324 | +€2,91 | 45,7% | 75 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 275 | 324 | +€2,64 | 45,7% | 84 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 275 | 324 | +€0,79 | 44,4% | 70 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 268 | 322 | €-4,19 | 44,4% | 70 | 36 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 263 | 312 | +€1,96 | 39,1% | 62 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 263 | 312 | +€0,10 | 36,2% | 62 | 22 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 263 | 312 | +€0,03 | 36,9% | 69 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 263 | 312 | €-1,81 | 37,8% | 48 | 29 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 263 | 312 | €-7,14 | 26,9% | 20 | 83 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 260 | 309 | €-2,37 | 34,0% | 25 | 63 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 248 | 302 | +€0,17 | 36,8% | 34 | 49 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 243 | 292 | €-1,38 | 30,1% | 32 | 30 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 241 | 290 | €-9,52 | 24,8% | 15 | 77 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 237 | 286 | €-7,40 | 28,3% | 53 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 227 | 276 | +€2,56 | 35,1% | 15 | 33 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 217 | 266 | €-15,84 | 21,4% | 12 | 70 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 216 | 270 | €-3,79 | 31,1% | 17 | 56 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 206 | 254 | €-14,31 | 22,0% | 11 | 60 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
