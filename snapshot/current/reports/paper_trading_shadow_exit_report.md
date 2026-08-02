# Block 3 — Shadow Exit Engine

Generato: 2026-08-02T16:24:10+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **221**
- Scenari virtuali ancora attivi: **2825**
- Gruppi in attesa dell'uscita originale: **28**
- Gruppi con originale chiuso ma Shadow ancora attive: **193**
- Confronti completati: **117083**

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
| TP_R150 | 3179 | 3245 | +€5,11 | 33,1% | 410 | 380 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3177 | 3243 | €-0,44 | 31,7% | 365 | 675 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3177 | 3243 | €-1,14 | 28,9% | 309 | 811 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3167 | 3233 | €-5,83 | 27,2% | 258 | 889 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3162 | 3228 | +€4,10 | 35,7% | 198 | 603 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3047 | 3113 | €-5,31 | 32,7% | 544 | 638 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3044 | 3110 | €-10,56 | 21,6% | 257 | 968 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
