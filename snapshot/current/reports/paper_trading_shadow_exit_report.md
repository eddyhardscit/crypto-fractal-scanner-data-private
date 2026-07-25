# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T02:08:44+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **416**
- Scenari virtuali ancora attivi: **3931**
- Gruppi in attesa dell'uscita originale: **223**
- Gruppi con originale chiuso ma Shadow ancora attive: **193**
- Confronti completati: **18727**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 908 | 971 | €-1,99 | 48,7% | 238 | 123 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 907 | 970 | +€5,19 | 50,5% | 262 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 907 | 970 | +€3,01 | 49,2% | 270 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 907 | 970 | +€0,71 | 47,8% | 277 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 907 | 970 | +€0,03 | 48,5% | 285 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 901 | 964 | €-0,58 | 46,7% | 269 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 891 | 954 | +€4,72 | 44,8% | 223 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 891 | 954 | +€3,03 | 43,3% | 237 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 891 | 954 | +€2,86 | 44,8% | 211 | 35 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 891 | 954 | €-2,08 | 42,5% | 138 | 206 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 888 | 951 | +€1,54 | 44,4% | 186 | 59 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 879 | 942 | +€0,72 | 41,7% | 147 | 116 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 866 | 929 | €-3,45 | 35,3% | 90 | 196 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 855 | 918 | +€3,32 | 34,0% | 117 | 92 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 855 | 918 | €-7,33 | 30,1% | 75 | 243 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 849 | 912 | €-4,78 | 35,6% | 80 | 240 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 837 | 900 | +€2,41 | 39,1% | 69 | 146 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 834 | 897 | €-12,60 | 28,3% | 184 | 147 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 827 | 890 | €-11,56 | 26,4% | 70 | 240 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 775 | 838 | €-17,88 | 21,7% | 69 | 238 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
