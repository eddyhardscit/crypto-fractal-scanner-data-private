# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T11:08:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **831**
- Scenari virtuali ancora attivi: **14207**
- Gruppi in attesa dell'uscita originale: **379**
- Gruppi con originale chiuso ma Shadow ancora attive: **452**
- Confronti completati: **65495**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2098 | 2163 | +€5,92 | 47,4% | 671 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2098 | 2163 | +€4,13 | 45,6% | 687 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2098 | 2163 | +€1,06 | 43,6% | 758 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2097 | 2162 | +€1,99 | 44,4% | 697 | 38 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2096 | 2161 | +€0,53 | 43,8% | 660 | 88 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2095 | 2160 | €-4,44 | 42,0% | 489 | 380 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2078 | 2143 | +€4,04 | 42,6% | 542 | 65 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2078 | 2143 | +€2,16 | 41,8% | 532 | 93 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2078 | 2143 | +€1,09 | 39,4% | 612 | 63 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2076 | 2141 | +€0,97 | 42,0% | 445 | 154 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2070 | 2135 | €-0,59 | 39,3% | 373 | 292 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2051 | 2116 | €-3,59 | 31,7% | 279 | 478 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 2045 | 2110 | +€3,12 | 32,1% | 315 | 219 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 2041 | 2106 | €-3,19 | 38,4% | 283 | 514 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 2030 | 2095 | €-4,76 | 29,2% | 240 | 545 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1988 | 2053 | +€4,93 | 38,5% | 165 | 325 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1987 | 2052 | €-5,13 | 33,6% | 160 | 594 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1982 | 2047 | €-10,50 | 26,9% | 191 | 584 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1951 | 2016 | €-12,61 | 28,5% | 430 | 410 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1845 | 1910 | €-19,15 | 19,7% | 190 | 619 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
