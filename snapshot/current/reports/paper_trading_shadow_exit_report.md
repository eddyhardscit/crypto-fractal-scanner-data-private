# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T11:38:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **194**
- Scenari virtuali ancora attivi: **2699**
- Gruppi in attesa dell'uscita originale: **161**
- Gruppi con originale chiuso ma Shadow ancora attive: **33**
- Confronti completati: **3456**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 141 | 179 | +€11,96 | 51,4% | 36 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 141 | 179 | +€10,15 | 50,8% | 36 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 141 | 179 | +€7,87 | 49,7% | 37 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 141 | 179 | +€7,05 | 51,4% | 36 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 141 | 179 | +€5,45 | 49,2% | 33 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 140 | 178 | +€9,72 | 48,9% | 31 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 140 | 178 | +€7,77 | 48,3% | 32 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 140 | 178 | +€7,44 | 47,2% | 32 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 140 | 178 | +€4,95 | 47,8% | 23 | 11 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 139 | 184 | +€0,31 | 51,6% | 35 | 11 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 138 | 176 | €-10,34 | 31,8% | 36 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 130 | 168 | +€7,41 | 41,1% | 9 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 130 | 175 | +€5,25 | 45,7% | 20 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 130 | 168 | +€2,05 | 36,9% | 20 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 129 | 167 | +€4,13 | 46,7% | 15 | 17 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 125 | 163 | €-2,84 | 39,3% | 7 | 25 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 125 | 163 | €-3,70 | 38,7% | 4 | 28 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 124 | 161 | €-14,51 | 30,4% | 3 | 40 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 124 | 161 | €-14,76 | 30,4% | 2 | 41 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 118 | 163 | €-1,04 | 39,9% | 11 | 31 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
