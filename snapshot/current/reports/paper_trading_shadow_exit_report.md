# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T07:38:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **191**
- Scenari virtuali ancora attivi: **2636**
- Gruppi in attesa dell'uscita originale: **155**
- Gruppi con originale chiuso ma Shadow ancora attive: **36**
- Confronti completati: **3035**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 119 | 157 | +€9,61 | 47,8% | 31 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 119 | 157 | +€7,75 | 43,9% | 28 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 119 | 157 | +€7,50 | 47,1% | 31 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 119 | 157 | +€5,46 | 44,6% | 27 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 119 | 157 | +€5,36 | 45,9% | 32 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 119 | 157 | +€4,76 | 47,8% | 31 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 119 | 157 | +€4,34 | 45,2% | 28 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 119 | 164 | €-0,21 | 47,6% | 32 | 11 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 117 | 155 | +€4,41 | 42,6% | 28 | 4 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 117 | 155 | +€0,82 | 32,3% | 19 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 114 | 159 | +€5,47 | 43,4% | 19 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 113 | 151 | +€3,01 | 43,0% | 21 | 6 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 112 | 149 | +€4,81 | 35,6% | 9 | 21 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 111 | 149 | +€2,02 | 41,6% | 13 | 17 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 111 | 149 | €-5,31 | 31,5% | 31 | 13 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 109 | 147 | €-4,70 | 37,4% | 7 | 25 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 109 | 147 | €-5,66 | 36,7% | 4 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 102 | 147 | +€3,31 | 38,1% | 11 | 24 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 98 | 132 | €-6,53 | 30,3% | 3 | 27 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 98 | 132 | €-6,83 | 30,3% | 2 | 28 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
