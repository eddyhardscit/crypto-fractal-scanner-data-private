# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T15:53:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **206**
- Scenari virtuali ancora attivi: **2699**
- Gruppi in attesa dell'uscita originale: **150**
- Gruppi con originale chiuso ma Shadow ancora attive: **56**
- Confronti completati: **4466**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 195 | 236 | +€10,17 | 47,5% | 47 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 195 | 236 | +€8,52 | 47,5% | 46 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 195 | 236 | +€6,60 | 47,5% | 47 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 195 | 236 | +€6,44 | 46,2% | 48 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 195 | 236 | +€4,34 | 45,8% | 44 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 195 | 242 | +€1,26 | 51,7% | 48 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 192 | 233 | +€8,22 | 43,3% | 39 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 192 | 233 | +€6,83 | 43,8% | 38 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 191 | 232 | +€6,35 | 41,8% | 40 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 191 | 232 | +€4,35 | 44,0% | 27 | 11 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 184 | 225 | €-7,92 | 29,3% | 41 | 26 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 179 | 220 | +€4,52 | 43,2% | 16 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 176 | 217 | +€2,64 | 33,6% | 23 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 175 | 222 | +€4,17 | 40,5% | 25 | 20 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 168 | 209 | €-2,24 | 33,5% | 7 | 32 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 168 | 209 | €-3,21 | 31,6% | 6 | 36 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 164 | 205 | +€6,35 | 34,1% | 9 | 23 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 164 | 204 | €-11,48 | 25,5% | 3 | 47 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 164 | 204 | €-11,68 | 25,5% | 2 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 152 | 199 | €-0,86 | 33,7% | 12 | 32 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
