# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T16:53:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **222**
- Scenari virtuali ancora attivi: **2937**
- Gruppi in attesa dell'uscita originale: **157**
- Gruppi con originale chiuso ma Shadow ancora attive: **65**
- Confronti completati: **4715**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 208 | 251 | +€9,14 | 46,2% | 56 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 208 | 251 | +€7,40 | 46,2% | 55 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 208 | 251 | +€5,61 | 46,2% | 56 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 208 | 251 | +€5,26 | 45,0% | 57 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 208 | 251 | +€3,11 | 44,6% | 53 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 208 | 257 | €-0,92 | 50,2% | 57 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 205 | 248 | +€6,88 | 40,7% | 48 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 205 | 248 | +€5,51 | 41,1% | 47 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 204 | 247 | +€4,94 | 39,3% | 49 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 204 | 247 | +€2,90 | 41,3% | 36 | 11 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 189 | 232 | +€3,46 | 40,9% | 16 | 25 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 189 | 232 | +€2,47 | 31,5% | 23 | 20 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 188 | 231 | €-6,85 | 30,3% | 41 | 26 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 180 | 223 | €-3,25 | 31,4% | 7 | 40 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 180 | 223 | €-4,68 | 29,6% | 6 | 44 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 179 | 228 | +€4,06 | 39,5% | 25 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 170 | 213 | +€6,34 | 33,8% | 9 | 23 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 168 | 210 | €-11,15 | 24,8% | 3 | 47 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 168 | 210 | €-11,35 | 24,8% | 2 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 162 | 211 | +€0,09 | 33,6% | 12 | 34 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
