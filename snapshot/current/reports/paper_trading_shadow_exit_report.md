# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T05:38:38+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **166**
- Scenari virtuali ancora attivi: **2135**
- Gruppi in attesa dell'uscita originale: **124**
- Gruppi con originale chiuso ma Shadow ancora attive: **42**
- Confronti completati: **2567**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 98 | 135 | +€10,96 | 48,9% | 26 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 98 | 135 | +€8,71 | 48,1% | 26 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 98 | 135 | +€6,42 | 46,7% | 27 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 98 | 135 | +€5,62 | 48,9% | 26 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 98 | 135 | +€5,41 | 45,9% | 23 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 98 | 142 | +€4,35 | 41,5% | 19 | 16 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 98 | 142 | €-1,41 | 43,0% | 27 | 11 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 97 | 134 | +€8,50 | 44,0% | 24 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 97 | 134 | +€6,23 | 44,8% | 23 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 95 | 132 | +€4,93 | 42,4% | 24 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 94 | 131 | +€1,82 | 42,0% | 21 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 93 | 130 | +€0,74 | 40,0% | 13 | 16 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 91 | 128 | €-6,84 | 35,2% | 7 | 24 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 90 | 127 | €-4,22 | 29,9% | 27 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 89 | 126 | +€2,35 | 31,7% | 15 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 85 | 121 | +€7,15 | 35,5% | 9 | 14 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 76 | 110 | €-4,51 | 34,5% | 4 | 15 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 75 | 119 | +€2,71 | 35,3% | 11 | 17 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 75 | 108 | €-6,36 | 27,8% | 3 | 21 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 75 | 108 | €-6,74 | 27,8% | 2 | 22 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
