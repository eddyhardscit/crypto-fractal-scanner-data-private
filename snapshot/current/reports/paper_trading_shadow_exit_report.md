# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T09:38:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **190**
- Scenari virtuali ancora attivi: **2781**
- Gruppi in attesa dell'uscita originale: **167**
- Gruppi con originale chiuso ma Shadow ancora attive: **23**
- Confronti completati: **3160**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 124 | 162 | +€9,69 | 47,5% | 34 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 124 | 162 | +€7,93 | 45,1% | 29 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 124 | 162 | +€7,51 | 46,9% | 34 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 124 | 162 | +€5,52 | 44,4% | 30 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 124 | 162 | +€5,31 | 45,7% | 35 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 124 | 162 | +€4,68 | 47,5% | 34 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 124 | 162 | +€4,19 | 45,1% | 31 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 123 | 168 | €-0,29 | 48,2% | 33 | 11 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 122 | 160 | €-11,63 | 30,6% | 34 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 121 | 159 | +€4,94 | 42,8% | 30 | 4 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 121 | 159 | +€2,68 | 43,4% | 21 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 121 | 159 | +€0,97 | 33,3% | 20 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 120 | 158 | +€6,20 | 37,3% | 9 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 120 | 165 | +€4,68 | 43,0% | 20 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 113 | 151 | +€2,62 | 42,4% | 13 | 17 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 111 | 149 | €-4,23 | 38,3% | 7 | 25 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 111 | 149 | €-5,17 | 37,6% | 4 | 28 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 110 | 155 | €-2,43 | 36,8% | 11 | 31 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 110 | 147 | €-17,02 | 28,6% | 3 | 40 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 110 | 147 | €-17,30 | 28,6% | 2 | 41 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
