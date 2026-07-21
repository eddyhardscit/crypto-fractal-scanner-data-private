# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T10:38:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **191**
- Scenari virtuali ancora attivi: **2797**
- Gruppi in attesa dell'uscita originale: **168**
- Gruppi con originale chiuso ma Shadow ancora attive: **23**
- Confronti completati: **3300**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 131 | 169 | +€11,54 | 49,7% | 34 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 131 | 169 | +€9,40 | 49,1% | 34 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 131 | 169 | +€8,59 | 47,3% | 29 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 131 | 169 | +€7,29 | 47,9% | 35 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 131 | 169 | +€6,81 | 49,7% | 34 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 131 | 169 | +€6,27 | 46,7% | 30 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 131 | 169 | +€5,00 | 47,3% | 31 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 130 | 175 | +€0,67 | 50,3% | 33 | 11 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 129 | 167 | €-10,14 | 33,5% | 34 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 128 | 166 | +€5,73 | 45,2% | 30 | 4 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 128 | 166 | +€3,57 | 45,8% | 21 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 128 | 166 | +€1,93 | 36,1% | 20 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 127 | 165 | +€6,94 | 40,0% | 9 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 127 | 172 | +€5,46 | 45,3% | 20 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 120 | 158 | +€3,56 | 44,9% | 13 | 17 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 118 | 156 | €-2,97 | 41,0% | 7 | 25 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 118 | 156 | €-3,87 | 40,4% | 4 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 117 | 162 | €-1,30 | 39,5% | 11 | 31 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 117 | 154 | €-15,17 | 31,8% | 3 | 40 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 117 | 154 | €-15,43 | 31,8% | 2 | 41 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
