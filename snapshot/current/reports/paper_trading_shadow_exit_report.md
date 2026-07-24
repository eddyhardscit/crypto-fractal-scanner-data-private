# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T00:53:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **326**
- Scenari virtuali ancora attivi: **2812**
- Gruppi in attesa dell'uscita originale: **186**
- Gruppi con originale chiuso ma Shadow ancora attive: **140**
- Confronti completati: **13368**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 631 | 694 | +€6,07 | 46,8% | 174 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 631 | 694 | +€4,04 | 45,8% | 176 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 631 | 694 | +€1,82 | 44,7% | 179 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 631 | 694 | +€0,50 | 43,9% | 197 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 628 | 691 | +€0,62 | 43,1% | 171 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 624 | 687 | +€1,45 | 36,1% | 167 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 623 | 686 | +€3,98 | 38,6% | 150 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 623 | 686 | +€2,28 | 38,5% | 139 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 623 | 686 | +€1,32 | 38,0% | 116 | 55 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 622 | 685 | +€1,03 | 50,8% | 130 | 92 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 619 | 682 | +€1,20 | 35,0% | 83 | 103 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 612 | 675 | €-0,61 | 31,6% | 36 | 154 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 610 | 673 | +€1,20 | 27,6% | 73 | 74 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 602 | 665 | €-3,09 | 28,3% | 42 | 162 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 595 | 658 | +€0,24 | 33,3% | 34 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 591 | 654 | +€4,16 | 45,4% | 58 | 126 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 578 | 641 | €-8,22 | 23,9% | 38 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 568 | 631 | €-2,80 | 31,5% | 33 | 168 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 549 | 612 | €-7,50 | 27,8% | 97 | 93 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 517 | 580 | €-14,53 | 18,1% | 37 | 147 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
