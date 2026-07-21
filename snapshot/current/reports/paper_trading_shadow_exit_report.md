# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T20:53:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **255**
- Scenari virtuali ancora attivi: **3020**
- Gruppi in attesa dell'uscita originale: **155**
- Gruppi con originale chiuso ma Shadow ancora attive: **100**
- Confronti completati: **5280**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 246 | 292 | +€6,67 | 47,9% | 71 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 246 | 292 | +€4,59 | 45,9% | 70 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 246 | 292 | +€2,57 | 44,9% | 71 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 246 | 292 | +€1,98 | 44,9% | 80 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 235 | 281 | +€0,74 | 45,2% | 66 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 231 | 277 | +€5,09 | 42,2% | 59 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 231 | 277 | +€3,00 | 39,0% | 59 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 231 | 277 | +€3,00 | 40,1% | 65 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 231 | 277 | +€0,88 | 40,8% | 45 | 19 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 228 | 274 | €-5,50 | 27,7% | 17 | 73 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 221 | 272 | €-2,97 | 48,5% | 67 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 215 | 266 | +€1,98 | 37,6% | 31 | 40 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 212 | 258 | +€0,99 | 38,8% | 22 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 211 | 257 | +€1,53 | 32,3% | 29 | 20 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 208 | 254 | €-8,14 | 28,0% | 50 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 195 | 241 | +€6,13 | 38,2% | 12 | 23 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 190 | 236 | €-6,53 | 28,0% | 12 | 49 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 175 | 226 | €-0,35 | 35,4% | 14 | 36 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 174 | 220 | €-12,31 | 24,1% | 9 | 48 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 174 | 219 | €-12,71 | 23,7% | 8 | 49 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
