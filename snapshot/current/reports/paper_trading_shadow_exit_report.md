# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T05:53:42+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **367**
- Scenari virtuali ancora attivi: **3303**
- Gruppi in attesa dell'uscita originale: **182**
- Gruppi con originale chiuso ma Shadow ancora attive: **185**
- Confronti completati: **15126**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 724 | 787 | +€6,26 | 49,6% | 200 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 724 | 787 | +€4,15 | 48,3% | 205 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 724 | 787 | +€1,89 | 46,9% | 211 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 724 | 787 | +€0,96 | 47,0% | 223 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 721 | 784 | +€0,61 | 45,2% | 206 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 719 | 782 | €-0,66 | 50,4% | 166 | 105 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 710 | 773 | +€5,05 | 42,4% | 169 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 710 | 773 | +€3,12 | 42,3% | 158 | 34 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 710 | 773 | +€2,96 | 40,5% | 184 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 710 | 773 | +€1,96 | 41,9% | 135 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 707 | 770 | +€1,64 | 38,6% | 99 | 115 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 706 | 769 | €-1,48 | 33,4% | 61 | 171 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 702 | 765 | +€0,34 | 44,1% | 85 | 168 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 684 | 747 | €-4,74 | 29,5% | 44 | 200 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 680 | 743 | +€1,60 | 30,8% | 78 | 84 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 658 | 721 | €-10,42 | 27,7% | 125 | 128 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 655 | 718 | €-9,23 | 25,5% | 40 | 198 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 650 | 713 | +€0,50 | 36,2% | 36 | 125 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 641 | 704 | €-5,40 | 32,8% | 46 | 194 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 607 | 670 | €-16,58 | 20,0% | 39 | 196 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
