# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T17:53:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **222**
- Scenari virtuali ancora attivi: **2751**
- Gruppi in attesa dell'uscita originale: **149**
- Gruppi con originale chiuso ma Shadow ancora attive: **73**
- Confronti completati: **4810**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R050 | 217 | 261 | +€3,71 | 44,4% | 66 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 214 | 258 | +€4,47 | 40,3% | 55 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 211 | 255 | +€8,48 | 45,5% | 60 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 211 | 255 | +€6,73 | 45,5% | 59 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 211 | 255 | +€4,58 | 44,3% | 61 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 211 | 255 | +€2,42 | 43,9% | 57 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 210 | 259 | €-1,25 | 49,8% | 59 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 207 | 251 | +€6,61 | 41,0% | 49 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 206 | 250 | +€4,85 | 39,6% | 50 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 206 | 250 | +€2,76 | 41,6% | 37 | 11 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 200 | 249 | +€2,89 | 36,9% | 25 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 198 | 242 | +€2,41 | 31,0% | 24 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 191 | 235 | +€3,21 | 41,3% | 17 | 25 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 190 | 234 | €-7,37 | 29,9% | 44 | 26 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 181 | 225 | €-3,53 | 31,1% | 8 | 41 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 180 | 224 | €-4,89 | 29,5% | 7 | 44 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 171 | 215 | +€6,16 | 34,0% | 10 | 23 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 168 | 211 | €-11,35 | 24,6% | 4 | 47 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 168 | 211 | €-11,54 | 24,6% | 3 | 48 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 166 | 215 | +€0,07 | 34,4% | 12 | 35 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
