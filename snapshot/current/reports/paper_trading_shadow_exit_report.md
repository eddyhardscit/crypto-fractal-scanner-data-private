# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T13:38:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **205**
- Scenari virtuali ancora attivi: **2770**
- Gruppi in attesa dell'uscita originale: **167**
- Gruppi con originale chiuso ma Shadow ancora attive: **38**
- Confronti completati: **3528**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 146 | 184 | +€11,45 | 52,2% | 37 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 146 | 184 | +€9,65 | 51,6% | 37 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 146 | 184 | +€7,39 | 50,5% | 38 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 146 | 184 | +€6,68 | 52,2% | 37 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 146 | 184 | +€5,00 | 50,0% | 34 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 144 | 182 | +€9,34 | 49,5% | 32 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 144 | 182 | +€7,48 | 48,9% | 33 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 144 | 182 | +€7,06 | 47,8% | 33 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 144 | 182 | +€4,59 | 48,4% | 24 | 11 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 144 | 182 | €-10,56 | 32,4% | 38 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 142 | 187 | €-0,32 | 50,8% | 37 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 134 | 179 | +€4,84 | 45,8% | 22 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 132 | 170 | +€4,19 | 47,6% | 15 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 132 | 170 | +€2,06 | 37,1% | 21 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 131 | 169 | +€7,36 | 40,8% | 9 | 23 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 128 | 166 | €-2,71 | 40,4% | 7 | 25 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 128 | 166 | €-3,55 | 39,8% | 4 | 28 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 127 | 164 | €-14,16 | 31,7% | 3 | 40 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 127 | 164 | €-14,40 | 31,7% | 2 | 41 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 118 | 163 | €-1,04 | 39,9% | 11 | 31 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
