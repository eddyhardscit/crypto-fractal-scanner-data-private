# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T11:23:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **536**
- Scenari virtuali ancora attivi: **5245**
- Gruppi in attesa dell'uscita originale: **279**
- Gruppi con originale chiuso ma Shadow ancora attive: **257**
- Confronti completati: **20214**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 1002 | 1066 | €-4,00 | 47,6% | 291 | 127 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 1000 | 1064 | +€2,82 | 49,2% | 323 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1000 | 1064 | +€0,92 | 47,9% | 330 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1000 | 1064 | €-1,27 | 46,6% | 326 | 24 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1000 | 1064 | €-1,85 | 47,3% | 346 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 990 | 1054 | €-2,55 | 45,9% | 313 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 987 | 1051 | €-1,22 | 44,4% | 154 | 218 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 982 | 1046 | +€4,23 | 44,6% | 270 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 982 | 1046 | +€2,45 | 45,0% | 252 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 982 | 1046 | +€2,10 | 42,2% | 298 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 979 | 1043 | +€1,09 | 44,5% | 212 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 966 | 1030 | €-0,10 | 41,2% | 169 | 148 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 937 | 1001 | +€3,51 | 33,4% | 130 | 92 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 909 | 973 | €-3,05 | 37,0% | 81 | 258 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 906 | 970 | +€4,23 | 41,9% | 72 | 146 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 891 | 955 | €-3,16 | 35,6% | 91 | 199 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 887 | 951 | €-13,62 | 28,7% | 208 | 149 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 878 | 942 | €-6,88 | 30,6% | 76 | 244 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 857 | 921 | €-10,54 | 27,5% | 70 | 243 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 798 | 862 | €-17,05 | 22,5% | 69 | 240 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
