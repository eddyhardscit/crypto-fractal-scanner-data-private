# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T16:23:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **108**
- Scenari virtuali ancora attivi: **1279**
- Gruppi in attesa dell'uscita originale: **71**
- Gruppi con originale chiuso ma Shadow ancora attive: **37**
- Confronti completati: **2106**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 76 | 111 | +€7,08 | 41,4% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 76 | 111 | +€5,47 | 36,0% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 76 | 111 | +€2,19 | 36,0% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 76 | 111 | +€1,46 | 41,4% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 76 | 107 | €-2,19 | 22,4% | 15 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 75 | 110 | +€5,19 | 40,9% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 75 | 110 | +€3,08 | 39,1% | 25 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 75 | 110 | +€2,71 | 35,5% | 22 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 75 | 110 | +€2,53 | 38,2% | 21 | 6 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 75 | 110 | €-0,22 | 34,5% | 20 | 4 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 75 | 110 | €-1,27 | 32,7% | 12 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 75 | 115 | €-3,28 | 34,8% | 25 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 74 | 103 | +€2,88 | 26,2% | 9 | 14 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 68 | 103 | €-6,59 | 21,4% | 23 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 66 | 106 | +€2,38 | 30,2% | 17 | 12 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 66 | 101 | €-5,32 | 28,7% | 7 | 15 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 61 | 93 | €-6,01 | 25,8% | 3 | 15 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 60 | 92 | €-8,16 | 17,4% | 3 | 21 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 60 | 92 | €-8,60 | 17,4% | 2 | 22 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 53 | 90 | €-6,03 | 23,3% | 10 | 13 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
