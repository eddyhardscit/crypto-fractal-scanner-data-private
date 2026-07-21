# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T21:53:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **267**
- Scenari virtuali ancora attivi: **3180**
- Gruppi in attesa dell'uscita originale: **159**
- Gruppi con originale chiuso ma Shadow ancora attive: **108**
- Confronti completati: **5386**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 254 | 300 | +€6,97 | 49,0% | 72 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 254 | 300 | +€4,86 | 47,0% | 71 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 254 | 300 | +€2,81 | 46,0% | 72 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 254 | 300 | +€2,39 | 46,0% | 81 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 254 | 300 | +€0,49 | 44,7% | 67 | 18 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 232 | 278 | +€5,12 | 42,4% | 59 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 232 | 278 | +€3,04 | 39,2% | 59 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 232 | 278 | +€2,96 | 39,9% | 66 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 232 | 278 | +€0,89 | 41,0% | 45 | 19 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 232 | 278 | €-5,09 | 28,8% | 17 | 73 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 227 | 273 | +€0,25 | 36,6% | 22 | 52 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 226 | 277 | €-2,98 | 48,4% | 67 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 218 | 269 | +€2,02 | 38,3% | 31 | 40 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 215 | 261 | €-7,92 | 27,2% | 50 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 212 | 258 | +€1,59 | 32,6% | 29 | 20 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 202 | 248 | €-7,72 | 26,6% | 12 | 61 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 196 | 242 | +€6,28 | 38,4% | 12 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 178 | 229 | €-0,97 | 34,9% | 14 | 39 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 174 | 220 | €-12,31 | 24,1% | 9 | 48 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 174 | 219 | €-12,71 | 23,7% | 8 | 49 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
