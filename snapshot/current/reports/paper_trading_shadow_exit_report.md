# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T07:08:59+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **810**
- Scenari virtuali ancora attivi: **12012**
- Gruppi in attesa dell'uscita originale: **337**
- Gruppi con originale chiuso ma Shadow ancora attive: **473**
- Confronti completati: **55541**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1913 | 1978 | +€4,18 | 47,0% | 654 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1913 | 1978 | +€2,37 | 45,0% | 671 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1913 | 1978 | +€0,17 | 43,7% | 681 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1913 | 1978 | €-0,77 | 43,0% | 737 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1911 | 1976 | €-1,25 | 43,1% | 643 | 87 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1895 | 1960 | +€4,49 | 43,7% | 538 | 45 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1895 | 1960 | +€1,24 | 40,4% | 606 | 43 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1894 | 1959 | +€2,44 | 43,0% | 525 | 71 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1878 | 1943 | +€1,10 | 42,8% | 443 | 131 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1866 | 1931 | +€3,42 | 32,4% | 315 | 195 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1859 | 1924 | €-4,17 | 43,0% | 483 | 309 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1858 | 1923 | €-0,32 | 40,6% | 366 | 249 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1855 | 1920 | €-3,48 | 32,9% | 276 | 431 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1852 | 1917 | €-2,45 | 39,2% | 279 | 466 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1829 | 1894 | +€5,64 | 40,0% | 165 | 301 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1813 | 1878 | €-6,10 | 29,4% | 237 | 497 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1779 | 1844 | €-4,08 | 35,1% | 160 | 532 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1777 | 1842 | €-10,72 | 27,5% | 189 | 532 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1727 | 1792 | €-13,77 | 27,3% | 423 | 352 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1600 | 1665 | €-19,44 | 20,5% | 188 | 517 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
