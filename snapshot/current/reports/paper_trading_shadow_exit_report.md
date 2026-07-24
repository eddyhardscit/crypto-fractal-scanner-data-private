# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T12:53:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **344**
- Scenari virtuali ancora attivi: **2610**
- Gruppi in attesa dell'uscita originale: **182**
- Gruppi con originale chiuso ma Shadow ancora attive: **162**
- Confronti completati: **15838**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 757 | 820 | +€0,53 | 50,5% | 167 | 112 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 754 | 817 | +€7,13 | 50,1% | 201 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 754 | 817 | +€4,99 | 48,8% | 206 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 754 | 817 | +€2,71 | 47,5% | 212 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 754 | 817 | +€1,59 | 47,6% | 224 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 751 | 814 | +€1,37 | 45,8% | 207 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 742 | 805 | +€4,01 | 41,5% | 185 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 741 | 804 | +€6,08 | 43,3% | 170 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 741 | 804 | +€4,11 | 43,2% | 159 | 34 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 741 | 804 | +€2,88 | 42,8% | 136 | 58 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 739 | 802 | €-0,44 | 43,0% | 85 | 187 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 738 | 801 | +€2,44 | 39,6% | 100 | 115 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 737 | 800 | €-1,44 | 34,2% | 61 | 175 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 733 | 796 | €-5,12 | 29,9% | 44 | 221 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 721 | 784 | +€3,31 | 32,7% | 78 | 88 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 706 | 769 | €-9,74 | 26,5% | 40 | 218 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 697 | 760 | €-10,48 | 28,8% | 125 | 138 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 689 | 752 | €-3,49 | 33,9% | 46 | 208 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 675 | 738 | +€0,08 | 36,2% | 36 | 131 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 654 | 717 | €-17,00 | 21,1% | 39 | 216 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
