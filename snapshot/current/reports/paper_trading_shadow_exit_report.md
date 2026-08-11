# Block 3 — Shadow Exit Engine

Generato: 2026-08-11T21:24:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **395**
- Scenari virtuali ancora attivi: **10455**
- Gruppi in attesa dell'uscita originale: **245**
- Gruppi con originale chiuso ma Shadow ancora attive: **150**
- Confronti completati: **146459**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 3769 | 3835 | +€7,61 | 50,2% | 1040 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 3769 | 3835 | +€6,48 | 49,1% | 1029 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 3769 | 3835 | +€5,17 | 47,2% | 1039 | 113 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 3769 | 3835 | +€4,47 | 41,2% | 887 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 3769 | 3835 | +€3,64 | 47,3% | 1155 | 12 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 3768 | 3834 | +€6,45 | 43,0% | 813 | 95 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 3768 | 3834 | +€4,82 | 42,4% | 770 | 161 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 3768 | 3834 | +€4,01 | 41,7% | 676 | 256 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 3761 | 3827 | +€0,95 | 33,2% | 396 | 756 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 3758 | 3824 | €-0,39 | 30,3% | 325 | 927 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 3755 | 3821 | €-5,34 | 27,0% | 274 | 1074 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 3750 | 3816 | +€5,61 | 33,4% | 472 | 404 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 3750 | 3816 | +€3,82 | 47,4% | 977 | 160 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 3747 | 3813 | €-1,10 | 45,2% | 772 | 559 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 3745 | 3811 | +€4,73 | 36,3% | 227 | 657 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 3742 | 3808 | +€2,23 | 40,1% | 592 | 402 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 3721 | 3787 | €-0,30 | 40,8% | 450 | 782 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 3698 | 3764 | €-4,13 | 32,0% | 597 | 808 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 3691 | 3757 | €-8,47 | 22,8% | 274 | 1164 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 3619 | 3685 | €-4,77 | 31,6% | 200 | 1059 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
