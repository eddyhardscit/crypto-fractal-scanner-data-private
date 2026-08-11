# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T00:09:55+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **161**
- Scenari virtuali ancora attivi: **7732**
- Gruppi in attesa dell'uscita originale: **161**
- Gruppi con originale chiuso ma Shadow ancora attive: **0**
- Confronti completati: **125268**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3317 | 3383 | +€9,10 | 51,8% | 925 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3317 | 3383 | +€7,48 | 50,8% | 925 | 35 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3317 | 3383 | +€6,72 | 43,5% | 711 | 93 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3317 | 3383 | +€6,27 | 49,2% | 926 | 83 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3317 | 3383 | +€5,14 | 33,6% | 412 | 386 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3317 | 3383 | +€4,92 | 48,9% | 1028 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3317 | 3383 | +€4,90 | 43,0% | 687 | 131 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3317 | 3383 | +€4,67 | 49,2% | 868 | 143 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3317 | 3383 | +€4,59 | 41,5% | 779 | 91 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3317 | 3383 | +€4,25 | 42,0% | 604 | 220 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3317 | 3383 | +€3,87 | 36,1% | 199 | 627 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3317 | 3383 | +€2,39 | 40,3% | 520 | 380 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3317 | 3383 | €-0,19 | 31,9% | 369 | 702 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3317 | 3383 | €-0,86 | 29,2% | 312 | 840 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3317 | 3383 | €-0,89 | 40,0% | 402 | 740 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3317 | 3383 | €-1,28 | 45,8% | 673 | 502 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3317 | 3383 | €-3,57 | 33,3% | 557 | 718 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3317 | 3383 | €-4,31 | 32,2% | 189 | 1009 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3317 | 3383 | €-5,13 | 27,7% | 261 | 918 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3317 | 3383 | €-8,39 | 23,1% | 261 | 1051 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
