# Block 3 — Shadow Exit Engine

Generato: 2026-07-21T12:38:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **198**
- Scenari virtuali ancora attivi: **2724**
- Gruppi in attesa dell'uscita originale: **161**
- Gruppi con originale chiuso ma Shadow ancora attive: **37**
- Confronti completati: **3512**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 145 | 183 | +€11,93 | 52,5% | 36 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 145 | 183 | +€10,14 | 51,9% | 36 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 145 | 183 | +€7,89 | 50,8% | 37 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 145 | 183 | +€7,13 | 52,5% | 36 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 145 | 183 | +€5,50 | 50,3% | 33 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 143 | 181 | +€9,71 | 49,7% | 31 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 143 | 181 | +€7,80 | 49,2% | 32 | 3 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 143 | 181 | +€7,45 | 48,1% | 32 | 5 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 143 | 181 | +€4,99 | 48,6% | 23 | 11 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 143 | 181 | €-10,06 | 32,6% | 37 | 20 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 140 | 185 | +€0,27 | 51,4% | 36 | 11 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 133 | 178 | +€5,24 | 46,1% | 21 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 132 | 170 | +€4,19 | 47,6% | 15 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 130 | 168 | +€7,41 | 41,1% | 9 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 130 | 168 | +€2,05 | 36,9% | 20 | 20 | READY_FOR_BLOCK4_EVALUATION |
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
