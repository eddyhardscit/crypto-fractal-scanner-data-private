# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T13:23:45+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **569**
- Scenari virtuali ancora attivi: **5661**
- Gruppi in attesa dell'uscita originale: **299**
- Gruppi con originale chiuso ma Shadow ancora attive: **270**
- Confronti completati: **20461**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 1018 | 1082 | €-4,24 | 47,0% | 302 | 127 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 1017 | 1081 | +€2,31 | 48,6% | 334 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1017 | 1081 | +€0,40 | 47,4% | 341 | 9 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1017 | 1081 | €-1,79 | 46,1% | 337 | 24 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1017 | 1081 | €-2,26 | 46,7% | 357 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1007 | 1071 | €-3,07 | 45,4% | 324 | 39 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 998 | 1062 | +€3,90 | 44,2% | 280 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 998 | 1062 | +€2,12 | 44,5% | 262 | 39 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 998 | 1062 | +€1,88 | 41,7% | 308 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 998 | 1062 | €-1,22 | 44,4% | 154 | 221 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 995 | 1059 | +€0,75 | 43,9% | 223 | 78 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 981 | 1045 | €-0,50 | 40,6% | 180 | 148 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 951 | 1015 | +€3,46 | 32,9% | 130 | 92 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 915 | 979 | €-3,01 | 36,9% | 81 | 258 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 910 | 974 | +€4,21 | 41,7% | 72 | 146 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 897 | 961 | €-13,90 | 28,4% | 213 | 150 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 895 | 959 | €-3,14 | 35,5% | 91 | 199 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 882 | 946 | €-6,85 | 30,4% | 76 | 244 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 866 | 930 | €-10,79 | 27,2% | 70 | 248 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 803 | 867 | €-17,00 | 22,4% | 69 | 241 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
