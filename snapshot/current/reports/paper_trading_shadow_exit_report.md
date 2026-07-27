# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T09:08:56+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **877**
- Scenari virtuali ancora attivi: **15241**
- Gruppi in attesa dell'uscita originale: **409**
- Gruppi con originale chiuso ma Shadow ancora attive: **468**
- Confronti completati: **59066**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R050 | 1976 | 2041 | €-0,75 | 42,3% | 750 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 1975 | 2040 | +€4,08 | 46,3% | 663 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1975 | 2040 | +€2,29 | 44,4% | 680 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1975 | 2040 | +€0,16 | 43,1% | 690 | 38 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1974 | 2039 | €-1,26 | 42,5% | 653 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1956 | 2021 | +€4,44 | 43,2% | 541 | 45 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1956 | 2021 | +€2,41 | 42,4% | 532 | 72 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1956 | 2021 | +€1,30 | 39,9% | 611 | 43 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1955 | 2020 | +€1,18 | 42,6% | 445 | 134 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1949 | 2014 | €-0,45 | 39,8% | 373 | 272 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1946 | 2011 | €-4,13 | 42,2% | 489 | 331 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1937 | 2002 | €-3,56 | 31,9% | 279 | 458 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1926 | 1991 | +€3,44 | 32,2% | 315 | 199 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1915 | 1980 | €-4,81 | 29,3% | 240 | 524 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1914 | 1979 | €-2,54 | 38,3% | 283 | 480 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1876 | 1941 | +€5,46 | 39,2% | 165 | 305 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1845 | 1910 | €-10,37 | 27,1% | 191 | 542 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1844 | 1909 | €-4,10 | 34,4% | 160 | 547 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1802 | 1867 | €-13,90 | 26,6% | 428 | 374 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1693 | 1758 | €-19,43 | 19,6% | 190 | 561 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
