# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T08:08:52+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **890**
- Scenari virtuali ancora attivi: **15471**
- Gruppi in attesa dell'uscita originale: **399**
- Gruppi con originale chiuso ma Shadow ancora attive: **491**
- Confronti completati: **56221**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1931 | 1996 | +€4,11 | 47,0% | 663 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1931 | 1996 | +€2,29 | 45,0% | 680 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1931 | 1996 | +€0,11 | 43,7% | 690 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1931 | 1996 | €-0,85 | 42,9% | 750 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1930 | 1995 | €-1,34 | 43,2% | 652 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1912 | 1977 | +€4,52 | 44,0% | 541 | 45 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1912 | 1977 | +€2,44 | 43,1% | 532 | 72 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1912 | 1977 | +€1,31 | 40,6% | 611 | 43 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1911 | 1976 | +€1,18 | 43,4% | 445 | 134 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1905 | 1970 | €-0,48 | 40,5% | 373 | 272 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1886 | 1951 | €-4,07 | 43,2% | 488 | 315 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1879 | 1944 | +€3,57 | 32,9% | 315 | 195 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1861 | 1926 | €-3,51 | 32,8% | 279 | 431 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1856 | 1921 | €-2,46 | 39,1% | 282 | 466 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1829 | 1894 | +€5,64 | 40,0% | 165 | 301 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1820 | 1885 | €-6,07 | 29,3% | 240 | 497 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1783 | 1848 | €-4,03 | 35,2% | 160 | 532 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1782 | 1847 | €-10,71 | 27,4% | 191 | 532 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1735 | 1800 | €-13,75 | 27,3% | 427 | 352 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1605 | 1670 | €-19,41 | 20,4% | 190 | 517 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
