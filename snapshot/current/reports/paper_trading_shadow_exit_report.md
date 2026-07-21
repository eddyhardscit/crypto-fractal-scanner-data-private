# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T14:53:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **196**
- Scenari virtuali ancora attivi: **2604**
- Gruppi in attesa dell'uscita originale: **155**
- Gruppi con originale chiuso ma Shadow ancora attive: **41**
- Confronti completati: **3900**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 163 | 204 | +€11,54 | 50,5% | 41 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 163 | 204 | +€9,77 | 50,0% | 41 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 163 | 204 | +€7,58 | 49,0% | 42 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 163 | 204 | +€7,36 | 50,5% | 41 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 163 | 204 | +€5,31 | 48,5% | 38 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 161 | 202 | +€7,64 | 44,6% | 36 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 161 | 202 | +€5,99 | 44,1% | 37 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 160 | 201 | +€5,79 | 43,3% | 36 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 160 | 201 | +€3,46 | 43,8% | 27 | 11 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 160 | 207 | +€0,47 | 52,7% | 41 | 12 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 159 | 200 | €-8,61 | 33,0% | 40 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 152 | 193 | +€1,74 | 34,2% | 23 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 149 | 196 | +€3,79 | 41,8% | 24 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 147 | 188 | +€6,92 | 37,2% | 9 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 145 | 186 | +€3,83 | 43,5% | 15 | 17 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 142 | 183 | €-2,40 | 37,2% | 7 | 25 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 141 | 182 | €-3,24 | 36,3% | 4 | 28 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 140 | 180 | €-12,90 | 28,9% | 3 | 40 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 140 | 180 | €-13,12 | 28,9% | 2 | 41 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 132 | 179 | €-1,03 | 36,3% | 12 | 31 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
