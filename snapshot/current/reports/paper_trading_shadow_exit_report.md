# Block 3 — Shadow Exit Engine

Generato: 2026-07-29T06:53:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **564**
- Scenari virtuali ancora attivi: **8473**
- Gruppi in attesa dell'uscita originale: **177**
- Gruppi con originale chiuso ma Shadow ancora attive: **387**
- Confronti completati: **107950**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 3022 | 3087 | €-1,86 | 46,7% | 641 | 477 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 3018 | 3083 | +€8,68 | 51,5% | 874 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3018 | 3083 | +€7,03 | 50,6% | 876 | 21 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3018 | 3083 | +€4,49 | 48,4% | 973 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3011 | 3076 | +€4,98 | 49,1% | 883 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3009 | 3074 | +€3,49 | 48,8% | 828 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2986 | 3051 | +€6,38 | 44,2% | 694 | 80 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2986 | 3051 | +€4,50 | 43,8% | 671 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2986 | 3051 | +€4,36 | 42,0% | 762 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2986 | 3051 | +€2,93 | 43,2% | 586 | 192 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2984 | 3049 | +€1,16 | 41,1% | 508 | 354 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2979 | 3044 | €-1,67 | 39,6% | 371 | 720 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2979 | 3044 | €-1,69 | 32,5% | 364 | 654 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2953 | 3018 | €-2,00 | 30,0% | 307 | 759 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 2938 | 3003 | €-4,96 | 32,7% | 169 | 924 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2908 | 2973 | +€4,80 | 33,0% | 410 | 333 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 2863 | 2928 | €-6,30 | 27,8% | 256 | 788 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 2853 | 2918 | +€4,23 | 36,6% | 198 | 514 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 2817 | 2882 | €-6,13 | 33,4% | 524 | 563 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 2739 | 2804 | €-12,11 | 22,7% | 255 | 838 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
