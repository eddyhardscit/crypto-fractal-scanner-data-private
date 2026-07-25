# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T17:23:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **543**
- Scenari virtuali ancora attivi: **6363**
- Gruppi in attesa dell'uscita originale: **301**
- Gruppi con originale chiuso ma Shadow ancora attive: **242**
- Confronti completati: **22741**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1113 | 1178 | +€0,69 | 47,0% | 386 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1113 | 1178 | €-1,21 | 46,0% | 392 | 10 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1113 | 1178 | €-3,61 | 44,9% | 414 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1112 | 1177 | €-3,39 | 44,9% | 386 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1108 | 1173 | €-4,77 | 43,8% | 378 | 44 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1108 | 1173 | €-6,16 | 45,4% | 341 | 141 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1101 | 1166 | €-3,45 | 42,3% | 187 | 253 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1091 | 1156 | +€2,59 | 42,6% | 321 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1091 | 1156 | +€0,90 | 42,6% | 307 | 41 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1091 | 1156 | +€0,38 | 39,4% | 360 | 25 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1089 | 1154 | €-0,69 | 42,0% | 265 | 82 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1082 | 1147 | €-1,50 | 38,5% | 229 | 156 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1079 | 1144 | +€2,17 | 31,8% | 174 | 111 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1068 | 1133 | +€3,28 | 40,7% | 96 | 179 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1051 | 1116 | €-4,58 | 34,6% | 145 | 229 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1030 | 1095 | €-18,19 | 26,8% | 242 | 219 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1011 | 1076 | €-9,35 | 28,3% | 126 | 281 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 996 | 1061 | €-3,74 | 36,4% | 84 | 286 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 994 | 1059 | €-15,42 | 24,4% | 90 | 323 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 935 | 1000 | €-22,19 | 19,8% | 89 | 321 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
