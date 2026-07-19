# Block 3 — Shadow Exit Engine

Generato: 2026-07-19T22:08:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **74**
- Scenari virtuali ancora attivi: **1226**
- Gruppi in attesa dell'uscita originale: **70**
- Gruppi con originale chiuso ma Shadow ancora attive: **4**
- Confronti completati: **124**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R150 | 1 | 7 | €-3,63 | 0,0% | 1 | 0 | COLLECTING |
| GB50_R100 | 1 | 6 | €-11,75 | 0,0% | 1 | 1 | COLLECTING |
| GB20_R100 | 1 | 7 | €-12,73 | 0,0% | 3 | 0 | COLLECTING |
| TP_R100 | 1 | 7 | €-14,23 | 0,0% | 3 | 0 | COLLECTING |
| GB30_R100 | 1 | 7 | €-15,56 | 0,0% | 3 | 0 | COLLECTING |
| GB20_R050 | 1 | 8 | €-16,15 | 12,5% | 3 | 0 | COLLECTING |
| GB30_R050 | 1 | 8 | €-18,02 | 12,5% | 3 | 0 | COLLECTING |
| GB40_R100 | 1 | 7 | €-18,06 | 0,0% | 2 | 1 | COLLECTING |
| TP_R050 | 1 | 8 | €-18,70 | 12,5% | 3 | 0 | COLLECTING |
| GB40_R050 | 1 | 8 | €-19,89 | 12,5% | 3 | 0 | COLLECTING |
| GB50_R050 | 1 | 8 | €-21,76 | 12,5% | 3 | 0 | COLLECTING |
| BE_R050 | 1 | 8 | €-31,12 | 0,0% | 4 | 0 | COLLECTING |
| TIME_6H | 0 | 5 | +€15,38 | 80,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| TIME_12H | 0 | 5 | +€9,41 | 60,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| TIME_24H | 0 | 4 | +€9,27 | 50,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| TP_R200 | 0 | 5 | +€0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| ATR15_R100 | 0 | 4 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| ATR20_R100 | 0 | 4 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| ATR30_R100 | 0 | 4 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| BE_R100 | 0 | 4 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
