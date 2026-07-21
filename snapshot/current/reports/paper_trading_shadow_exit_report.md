# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T22:53:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **259**
- Scenari virtuali ancora attivi: **3079**
- Gruppi in attesa dell'uscita originale: **158**
- Gruppi con originale chiuso ma Shadow ancora attive: **101**
- Confronti completati: **5895**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 270 | 319 | +€5,80 | 47,6% | 75 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 270 | 319 | +€3,81 | 45,8% | 74 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 270 | 319 | +€1,87 | 44,8% | 75 | 9 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 270 | 319 | +€1,51 | 44,8% | 84 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 270 | 319 | €-0,32 | 43,6% | 70 | 18 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 262 | 316 | €-4,90 | 43,7% | 70 | 35 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 255 | 304 | +€2,51 | 40,1% | 62 | 10 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 255 | 304 | +€0,61 | 37,2% | 62 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 255 | 304 | +€0,53 | 37,8% | 69 | 10 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 255 | 304 | €-1,35 | 38,8% | 48 | 26 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 255 | 304 | €-6,83 | 27,6% | 20 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 251 | 300 | €-1,86 | 35,0% | 25 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 241 | 295 | +€0,12 | 36,3% | 34 | 47 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 235 | 284 | €-0,88 | 31,0% | 32 | 27 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 233 | 282 | €-9,25 | 25,5% | 15 | 74 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 232 | 281 | €-8,43 | 27,0% | 53 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 219 | 268 | +€3,21 | 36,2% | 15 | 30 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 207 | 261 | €-3,09 | 32,2% | 17 | 52 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 198 | 247 | €-13,79 | 23,1% | 12 | 56 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 198 | 246 | €-14,16 | 22,8% | 11 | 57 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
