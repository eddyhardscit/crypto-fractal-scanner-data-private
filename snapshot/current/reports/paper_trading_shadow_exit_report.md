# Block 3 — Shadow Exit Engine

Generato: 2026-08-02T14:23:55+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **238**
- Scenari virtuali ancora attivi: **3064**
- Gruppi in attesa dell'uscita originale: **32**
- Gruppi con originale chiuso ma Shadow ancora attive: **206**
- Confronti completati: **116838**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3193 | 3259 | €-1,49 | 45,8% | 665 | 486 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3191 | 3257 | +€9,21 | 51,9% | 902 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3191 | 3257 | +€7,54 | 51,0% | 904 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3191 | 3257 | +€6,20 | 49,5% | 907 | 69 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3191 | 3257 | +€4,92 | 48,9% | 1001 | 7 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3190 | 3256 | €-1,16 | 39,6% | 396 | 729 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3188 | 3254 | +€4,57 | 49,4% | 850 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3183 | 3249 | +€6,74 | 43,4% | 698 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3183 | 3249 | +€4,87 | 43,0% | 675 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3183 | 3249 | +€4,54 | 41,4% | 764 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3183 | 3249 | +€4,12 | 42,0% | 594 | 206 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3181 | 3247 | €-4,68 | 31,6% | 184 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3180 | 3246 | +€2,21 | 40,3% | 512 | 362 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3177 | 3243 | +€5,11 | 33,1% | 410 | 378 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3177 | 3243 | €-0,44 | 31,7% | 365 | 675 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3174 | 3240 | €-1,14 | 29,0% | 309 | 808 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3164 | 3230 | €-5,83 | 27,2% | 258 | 886 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3160 | 3226 | +€4,11 | 35,8% | 198 | 601 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3029 | 3095 | €-7,01 | 32,4% | 544 | 635 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3026 | 3092 | €-12,30 | 21,3% | 257 | 965 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
