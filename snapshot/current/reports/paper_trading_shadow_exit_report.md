# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T16:39:43+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **370**
- Scenari virtuali ancora attivi: **8302**
- Gruppi in attesa dell'uscita originale: **227**
- Gruppi con originale chiuso ma Shadow ancora attive: **143**
- Confronti completati: **169101**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 4211 | 4277 | +€9,04 | 50,7% | 1074 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 4211 | 4277 | +€8,13 | 49,7% | 1066 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 4211 | 4277 | +€6,81 | 42,3% | 841 | 102 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 4211 | 4277 | +€6,79 | 48,0% | 1077 | 114 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 4211 | 4277 | +€5,50 | 48,2% | 1189 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 4211 | 4277 | +€5,47 | 48,2% | 1014 | 166 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 4211 | 4277 | +€5,23 | 41,8% | 797 | 169 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 4211 | 4277 | +€5,04 | 40,7% | 916 | 98 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 4211 | 4277 | +€4,38 | 41,1% | 704 | 264 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 4203 | 4269 | +€2,75 | 39,8% | 602 | 433 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 4203 | 4269 | +€1,16 | 33,1% | 414 | 791 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 4199 | 4265 | €-0,24 | 30,3% | 327 | 985 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 4193 | 4259 | €-4,78 | 27,2% | 276 | 1132 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 4192 | 4258 | +€0,29 | 46,0% | 809 | 575 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 4176 | 4242 | €-3,18 | 33,2% | 609 | 896 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 4174 | 4240 | €-8,30 | 23,0% | 276 | 1274 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 4173 | 4239 | +€4,85 | 32,2% | 486 | 446 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 4165 | 4231 | €-0,45 | 39,3% | 462 | 863 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 4145 | 4211 | €-5,53 | 30,4% | 209 | 1204 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 4143 | 4209 | +€3,91 | 34,9% | 236 | 704 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
