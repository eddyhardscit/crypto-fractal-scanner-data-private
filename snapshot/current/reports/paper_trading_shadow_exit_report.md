# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T06:38:39+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **181**
- Scenari virtuali ancora attivi: **2474**
- Gruppi in attesa dell'uscita originale: **144**
- Gruppi con originale chiuso ma Shadow ancora attive: **37**
- Confronti completati: **3008**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 119 | 156 | +€9,67 | 48,1% | 31 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 119 | 156 | +€7,80 | 44,2% | 28 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 119 | 156 | +€7,55 | 47,4% | 31 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 119 | 156 | +€5,50 | 44,9% | 27 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 119 | 156 | +€5,39 | 46,2% | 32 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 119 | 156 | +€4,79 | 48,1% | 31 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 119 | 156 | +€4,37 | 45,5% | 28 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 119 | 163 | €-0,41 | 47,2% | 32 | 11 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 117 | 154 | +€4,44 | 42,9% | 28 | 4 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 117 | 154 | +€0,83 | 32,5% | 19 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 114 | 158 | +€5,30 | 43,0% | 19 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 113 | 150 | +€3,03 | 43,3% | 21 | 6 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 112 | 148 | +€4,84 | 35,8% | 9 | 21 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 111 | 148 | +€2,03 | 41,9% | 13 | 17 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 111 | 148 | €-5,34 | 31,8% | 31 | 13 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 108 | 145 | €-5,05 | 37,2% | 7 | 25 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 108 | 145 | €-5,91 | 36,6% | 4 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 99 | 143 | +€1,11 | 36,4% | 11 | 24 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 97 | 130 | €-6,67 | 30,0% | 3 | 27 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 97 | 130 | €-6,98 | 30,0% | 2 | 28 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
