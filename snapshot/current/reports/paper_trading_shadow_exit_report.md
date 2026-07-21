# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T08:38:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **185**
- Scenari virtuali ancora attivi: **2768**
- Gruppi in attesa dell'uscita originale: **165**
- Gruppi con originale chiuso ma Shadow ancora attive: **20**
- Confronti completati: **3091**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 120 | 158 | +€9,13 | 47,5% | 32 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 120 | 158 | +€7,34 | 43,7% | 29 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 120 | 158 | +€7,01 | 46,8% | 32 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 120 | 158 | +€5,11 | 44,3% | 28 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 120 | 158 | +€4,85 | 45,6% | 33 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 120 | 158 | +€4,26 | 47,5% | 32 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 120 | 158 | +€3,82 | 44,9% | 29 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 120 | 165 | €-0,80 | 47,3% | 33 | 11 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 118 | 156 | +€0,66 | 32,1% | 20 | 20 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 118 | 156 | €-11,84 | 30,1% | 32 | 19 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 117 | 155 | +€5,67 | 36,1% | 9 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 117 | 155 | +€4,41 | 42,6% | 28 | 4 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 115 | 160 | +€5,14 | 43,1% | 20 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 113 | 151 | +€3,01 | 43,0% | 21 | 6 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 111 | 149 | +€2,02 | 41,6% | 13 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 109 | 154 | €-2,61 | 36,4% | 11 | 31 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 109 | 147 | €-4,70 | 37,4% | 7 | 25 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 109 | 147 | €-5,66 | 36,7% | 4 | 28 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 108 | 145 | €-17,68 | 27,6% | 3 | 40 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 108 | 145 | €-17,96 | 27,6% | 2 | 41 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
