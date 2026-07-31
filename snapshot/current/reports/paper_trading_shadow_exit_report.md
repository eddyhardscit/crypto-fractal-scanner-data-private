# Block 3 — Shadow Exit Engine

Generato: 2026-07-31T14:38:57+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **403**
- Scenari virtuali ancora attivi: **5928**
- Gruppi in attesa dell'uscita originale: **73**
- Gruppi con originale chiuso ma Shadow ancora attive: **330**
- Confronti completati: **112110**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3125 | 3191 | €-1,21 | 39,9% | 392 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3125 | 3191 | €-1,56 | 46,2% | 657 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3125 | 3191 | €-4,74 | 32,2% | 180 | 980 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3099 | 3165 | +€8,94 | 52,2% | 890 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3099 | 3165 | +€7,28 | 51,2% | 892 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3099 | 3165 | +€4,87 | 49,2% | 989 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3098 | 3164 | +€5,23 | 49,7% | 899 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3096 | 3162 | +€3,73 | 49,4% | 844 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3061 | 3127 | +€6,46 | 44,0% | 696 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3061 | 3127 | +€4,59 | 43,7% | 673 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3061 | 3127 | +€4,48 | 42,0% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3060 | 3126 | +€3,00 | 43,0% | 588 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3057 | 3123 | +€1,23 | 41,0% | 509 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3046 | 3112 | €-1,65 | 32,1% | 365 | 662 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3035 | 3101 | +€5,01 | 33,5% | 410 | 358 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3032 | 3098 | €-2,04 | 29,5% | 308 | 784 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3001 | 3067 | €-6,34 | 27,7% | 257 | 844 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2995 | 3061 | +€3,98 | 36,4% | 198 | 566 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2921 | 2987 | €-6,39 | 33,3% | 540 | 591 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2875 | 2941 | €-12,12 | 22,2% | 256 | 911 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
