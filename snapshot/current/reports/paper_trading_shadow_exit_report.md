# Block 3 — Shadow Exit Engine

Generato: 2026-08-02T08:09:57+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **250**
- Scenari virtuali ancora attivi: **3706**
- Gruppi in attesa dell'uscita originale: **29**
- Gruppi con originale chiuso ma Shadow ancora attive: **221**
- Confronti completati: **115996**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3190 | 3256 | €-1,16 | 39,6% | 396 | 729 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3190 | 3256 | €-1,49 | 45,8% | 664 | 484 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3181 | 3247 | €-4,68 | 31,6% | 184 | 989 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3172 | 3238 | +€8,83 | 51,8% | 899 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3172 | 3238 | +€7,21 | 50,9% | 901 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3172 | 3238 | +€5,19 | 49,3% | 904 | 69 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3172 | 3238 | +€4,86 | 48,8% | 998 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3160 | 3226 | +€3,72 | 49,1% | 847 | 129 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3157 | 3223 | +€6,28 | 43,2% | 696 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3157 | 3223 | +€4,46 | 42,8% | 673 | 123 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3157 | 3223 | +€4,36 | 41,2% | 762 | 86 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3157 | 3223 | +€2,92 | 41,9% | 591 | 206 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3151 | 3217 | +€4,82 | 32,9% | 410 | 378 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3145 | 3211 | +€1,19 | 40,0% | 509 | 362 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3144 | 3210 | €-1,58 | 31,5% | 365 | 671 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3135 | 3201 | €-2,20 | 28,5% | 309 | 807 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3130 | 3196 | +€3,70 | 35,6% | 198 | 600 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3125 | 3191 | €-6,68 | 26,7% | 258 | 885 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3027 | 3093 | €-7,02 | 32,5% | 544 | 635 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3012 | 3078 | €-12,35 | 21,4% | 257 | 964 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
