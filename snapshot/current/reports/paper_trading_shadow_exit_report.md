# Block 3 — Shadow Exit Engine

Generato: 2026-08-12T06:25:25+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **364**
- Scenari virtuali ancora attivi: **9708**
- Gruppi in attesa dell'uscita originale: **231**
- Gruppi con originale chiuso ma Shadow ancora attive: **133**
- Confronti completati: **155703**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3955 | 4021 | +€8,01 | 50,0% | 1061 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3955 | 4021 | +€7,01 | 49,0% | 1047 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3955 | 4021 | +€6,43 | 42,6% | 832 | 96 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3955 | 4021 | +€5,68 | 47,3% | 1057 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3955 | 4021 | +€4,81 | 42,0% | 788 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3955 | 4021 | +€4,52 | 40,9% | 906 | 92 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3955 | 4021 | +€4,25 | 47,3% | 1175 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3955 | 4021 | €-0,32 | 46,4% | 790 | 575 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3954 | 4020 | +€4,36 | 47,5% | 995 | 164 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3954 | 4020 | +€3,99 | 41,3% | 694 | 258 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3938 | 4004 | +€1,11 | 33,0% | 414 | 761 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3934 | 4000 | +€2,44 | 40,2% | 593 | 410 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3932 | 3998 | €-0,25 | 30,1% | 325 | 953 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3931 | 3997 | +€5,39 | 33,0% | 476 | 419 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3927 | 3993 | €-5,00 | 27,0% | 274 | 1098 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3921 | 3987 | €-0,53 | 40,1% | 451 | 823 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3911 | 3977 | +€4,58 | 35,9% | 227 | 672 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3892 | 3958 | €-5,35 | 31,3% | 200 | 1153 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3871 | 3937 | €-3,40 | 32,4% | 600 | 831 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3861 | 3927 | €-8,01 | 22,9% | 274 | 1188 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
