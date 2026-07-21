# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T18:53:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **237**
- Scenari virtuali ancora attivi: **2832**
- Gruppi in attesa dell'uscita originale: **154**
- Gruppi con originale chiuso ma Shadow ancora attive: **83**
- Confronti completati: **5015**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 228 | 272 | +€7,48 | 46,0% | 67 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 228 | 272 | +€5,51 | 43,8% | 66 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 228 | 272 | +€3,02 | 43,8% | 73 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 223 | 267 | +€6,21 | 41,9% | 55 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 223 | 267 | +€4,30 | 40,1% | 60 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 222 | 266 | +€4,15 | 38,3% | 55 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 222 | 266 | +€3,57 | 43,6% | 68 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 222 | 266 | +€1,40 | 43,2% | 64 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 219 | 268 | €-2,28 | 48,9% | 65 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 216 | 260 | +€2,13 | 41,2% | 42 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 210 | 259 | +€2,43 | 37,1% | 29 | 40 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 205 | 249 | +€2,71 | 32,1% | 25 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 196 | 240 | +€3,13 | 40,8% | 20 | 25 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 196 | 240 | €-3,48 | 30,0% | 11 | 50 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 195 | 239 | €-7,31 | 29,7% | 46 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 187 | 231 | +€7,10 | 37,7% | 10 | 23 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 187 | 231 | €-5,29 | 28,6% | 8 | 49 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 172 | 221 | +€0,25 | 35,3% | 12 | 36 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 171 | 215 | €-11,11 | 24,7% | 5 | 48 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 171 | 214 | €-11,51 | 24,3% | 4 | 49 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
