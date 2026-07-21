# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T19:53:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **250**
- Scenari virtuali ancora attivi: **2993**
- Gruppi in attesa dell'uscita originale: **163**
- Gruppi con originale chiuso ma Shadow ancora attive: **87**
- Confronti completati: **5124**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 232 | 278 | +€6,27 | 46,0% | 70 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 232 | 278 | +€4,23 | 43,9% | 69 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 232 | 278 | +€2,21 | 42,8% | 70 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 232 | 278 | +€1,31 | 42,8% | 79 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 227 | 273 | +€5,00 | 42,1% | 58 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 227 | 273 | +€2,95 | 38,8% | 58 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 227 | 273 | +€2,90 | 39,9% | 64 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 227 | 273 | +€0,84 | 40,7% | 44 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 222 | 268 | +€0,24 | 42,9% | 66 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 219 | 270 | €-3,02 | 48,5% | 67 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 213 | 264 | +€1,91 | 37,5% | 31 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 209 | 255 | +€1,64 | 32,5% | 28 | 20 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 207 | 253 | €-4,88 | 29,6% | 14 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 196 | 242 | +€1,84 | 40,5% | 22 | 25 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 195 | 241 | €-8,53 | 29,5% | 48 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 192 | 238 | +€6,02 | 38,2% | 12 | 23 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 187 | 233 | €-6,56 | 28,3% | 10 | 49 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 172 | 223 | €-0,67 | 35,0% | 14 | 36 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 171 | 217 | €-12,42 | 24,4% | 7 | 48 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 171 | 216 | €-12,83 | 24,1% | 6 | 49 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
