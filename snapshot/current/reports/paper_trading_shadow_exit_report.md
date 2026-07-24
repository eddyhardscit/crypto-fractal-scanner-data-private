# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T03:53:40+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **341**
- Scenari virtuali ancora attivi: **2861**
- Gruppi in attesa dell'uscita originale: **158**
- Gruppi con originale chiuso ma Shadow ancora attive: **183**
- Confronti completati: **15006**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 718 | 781 | +€6,17 | 49,4% | 200 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 718 | 781 | +€4,06 | 48,1% | 205 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 718 | 781 | +€1,80 | 46,7% | 211 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 718 | 781 | +€0,85 | 46,9% | 223 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 715 | 778 | +€0,51 | 45,1% | 205 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 714 | 777 | €-0,65 | 50,5% | 165 | 105 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 705 | 768 | +€5,04 | 42,3% | 169 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 705 | 768 | +€3,10 | 42,2% | 158 | 34 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 705 | 768 | +€2,92 | 40,4% | 184 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 705 | 768 | +€1,94 | 41,8% | 135 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 702 | 765 | +€1,62 | 38,4% | 99 | 115 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 701 | 764 | €-1,50 | 33,2% | 61 | 171 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 682 | 745 | +€0,80 | 44,2% | 84 | 159 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 676 | 739 | +€1,61 | 30,7% | 78 | 84 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 676 | 739 | €-4,34 | 29,5% | 44 | 196 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 654 | 717 | €-10,55 | 27,6% | 125 | 128 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 651 | 714 | €-9,29 | 25,4% | 40 | 198 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 644 | 707 | +€0,44 | 35,9% | 36 | 125 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 636 | 699 | €-5,47 | 32,6% | 46 | 194 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 603 | 666 | €-16,68 | 19,8% | 39 | 196 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
