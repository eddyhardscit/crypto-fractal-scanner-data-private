# Block 3 — Shadow Exit Engine

Generato: 2026-08-01T02:53:50+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **357**
- Scenari virtuali ancora attivi: **5671**
- Gruppi in attesa dell'uscita originale: **44**
- Gruppi con originale chiuso ma Shadow ancora attive: **313**
- Confronti completati: **113126**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 3154 | 3220 | €-1,19 | 39,7% | 393 | 720 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3154 | 3220 | €-1,50 | 46,0% | 659 | 477 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3154 | 3220 | €-4,69 | 31,9% | 181 | 980 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3113 | 3179 | +€8,98 | 52,2% | 890 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3113 | 3179 | +€7,32 | 51,3% | 892 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3113 | 3179 | +€4,92 | 49,3% | 989 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3112 | 3178 | +€5,27 | 49,8% | 899 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3110 | 3176 | +€3,77 | 49,5% | 844 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3066 | 3132 | +€6,47 | 44,0% | 696 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3066 | 3132 | +€4,59 | 43,6% | 673 | 117 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3066 | 3132 | +€4,48 | 41,9% | 762 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3065 | 3131 | +€3,01 | 43,0% | 588 | 194 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3062 | 3128 | +€1,23 | 40,9% | 509 | 356 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3051 | 3117 | €-1,65 | 32,1% | 365 | 662 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3048 | 3114 | €-2,22 | 29,3% | 308 | 795 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3040 | 3106 | +€4,99 | 33,5% | 410 | 359 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3030 | 3096 | €-6,76 | 27,5% | 257 | 866 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3013 | 3079 | +€3,80 | 36,3% | 198 | 577 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2957 | 3023 | €-6,91 | 33,1% | 540 | 615 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2910 | 2976 | €-12,69 | 22,0% | 256 | 939 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
