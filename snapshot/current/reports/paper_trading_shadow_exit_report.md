# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T10:08:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **876**
- Scenari virtuali ancora attivi: **14367**
- Gruppi in attesa dell'uscita originale: **384**
- Gruppi con originale chiuso ma Shadow ancora attive: **492**
- Confronti completati: **63453**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 2066 | 2131 | +€4,76 | 46,6% | 671 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 2066 | 2131 | +€3,00 | 44,8% | 687 | 17 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 2066 | 2131 | €-0,02 | 42,7% | 758 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 2065 | 2130 | +€0,89 | 43,6% | 697 | 38 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 2064 | 2129 | €-0,52 | 43,0% | 660 | 88 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 2040 | 2105 | €-4,01 | 41,7% | 489 | 354 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 2031 | 2096 | +€4,34 | 42,1% | 542 | 47 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 2031 | 2096 | +€2,41 | 41,3% | 532 | 75 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 2031 | 2096 | +€1,32 | 38,9% | 612 | 45 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 2029 | 2094 | +€1,20 | 41,6% | 445 | 136 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 2023 | 2088 | €-0,39 | 38,8% | 373 | 274 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 2004 | 2069 | €-3,46 | 31,0% | 279 | 460 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1998 | 2063 | +€3,40 | 31,4% | 315 | 201 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1983 | 2048 | €-4,65 | 28,5% | 240 | 527 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1978 | 2043 | €-2,32 | 38,1% | 283 | 480 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1941 | 2006 | +€5,26 | 37,9% | 165 | 307 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1935 | 2000 | €-10,53 | 26,1% | 191 | 566 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1917 | 1982 | €-13,62 | 27,5% | 428 | 407 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1909 | 1974 | €-4,00 | 33,2% | 160 | 550 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1794 | 1859 | €-19,43 | 18,6% | 190 | 598 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
