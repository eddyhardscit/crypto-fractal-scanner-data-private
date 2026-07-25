# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T09:23:46+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **486**
- Scenari virtuali ancora attivi: **4447**
- Gruppi in attesa dell'uscita originale: **229**
- Gruppi con originale chiuso ma Shadow ancora attive: **257**
- Confronti completati: **20090**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1000 | 1064 | +€2,82 | 49,2% | 323 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1000 | 1064 | €-1,85 | 47,3% | 346 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 999 | 1063 | +€0,93 | 48,0% | 330 | 8 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 998 | 1062 | €-4,02 | 47,6% | 291 | 125 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 997 | 1061 | €-1,22 | 46,7% | 326 | 21 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 982 | 1046 | +€4,23 | 44,6% | 270 | 25 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 982 | 1046 | +€2,10 | 42,2% | 298 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 979 | 1043 | +€2,47 | 45,0% | 252 | 38 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 976 | 1040 | €-2,20 | 46,3% | 313 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 962 | 1026 | €-1,80 | 43,7% | 154 | 212 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 952 | 1016 | +€0,87 | 43,9% | 212 | 69 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 937 | 1001 | +€3,51 | 33,4% | 130 | 92 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 928 | 992 | +€0,31 | 42,1% | 169 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 906 | 970 | +€4,23 | 41,9% | 72 | 146 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 900 | 964 | €-3,48 | 36,5% | 81 | 257 | READY_FOR_BLOCK4_EVALUATION |
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
