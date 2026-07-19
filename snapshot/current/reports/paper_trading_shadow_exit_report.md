# Block 3 — Shadow Exit Engine

Generato: 2026-07-19T20:08:34+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **70**
- Scenari virtuali ancora attivi: **1164**
- Gruppi in attesa dell'uscita originale: **68**
- Gruppi con originale chiuso ma Shadow ancora attive: **2**
- Confronti completati: **57**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 0 | 3 | +€13,27 | 66,7% | 0 | 0 | WAITING_FULL_SAMPLE |
| ATR15_R100 | 0 | 2 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| ATR20_R100 | 0 | 2 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| ATR30_R100 | 0 | 2 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| BE_R100 | 0 | 2 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| GB40_R100 | 0 | 2 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| GB50_R100 | 0 | 2 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| TIME_12H | 0 | 2 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| TIME_24H | 0 | 2 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| TP_R150 | 0 | 3 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| TP_R200 | 0 | 2 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| GB20_R050 | 0 | 4 | €-2,92 | 25,0% | 1 | 0 | WAITING_FULL_SAMPLE |
| GB20_R100 | 0 | 3 | €-3,88 | 0,0% | 1 | 0 | WAITING_FULL_SAMPLE |
| GB30_R050 | 0 | 4 | €-4,92 | 25,0% | 1 | 0 | WAITING_FULL_SAMPLE |
| TP_R050 | 0 | 4 | €-6,41 | 25,0% | 1 | 0 | WAITING_FULL_SAMPLE |
| GB30_R100 | 0 | 3 | €-6,51 | 0,0% | 1 | 0 | WAITING_FULL_SAMPLE |
| GB40_R050 | 0 | 4 | €-6,92 | 25,0% | 1 | 0 | WAITING_FULL_SAMPLE |
| TP_R100 | 0 | 3 | €-8,30 | 0,0% | 1 | 0 | WAITING_FULL_SAMPLE |
| GB50_R050 | 0 | 4 | €-8,92 | 25,0% | 1 | 0 | WAITING_FULL_SAMPLE |
| BE_R050 | 0 | 4 | €-18,93 | 0,0% | 2 | 0 | WAITING_FULL_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
