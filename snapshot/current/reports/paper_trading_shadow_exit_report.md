# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T03:08:34+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **82**
- Scenari virtuali ancora attivi: **1156**
- Gruppi in attesa dell'uscita originale: **69**
- Gruppi con originale chiuso ma Shadow ancora attive: **13**
- Confronti completati: **583**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 12 | 33 | +€15,16 | 48,5% | 8 | 0 | PRELIMINARY_SAMPLE |
| GB30_R050 | 12 | 33 | +€12,07 | 48,5% | 8 | 0 | PRELIMINARY_SAMPLE |
| TP_R150 | 12 | 30 | +€10,88 | 43,3% | 4 | 1 | PRELIMINARY_SAMPLE |
| GB40_R050 | 12 | 33 | +€9,37 | 48,5% | 8 | 0 | PRELIMINARY_SAMPLE |
| GB20_R100 | 12 | 32 | +€8,99 | 46,9% | 7 | 1 | PRELIMINARY_SAMPLE |
| TP_R050 | 12 | 33 | +€7,85 | 48,5% | 8 | 0 | PRELIMINARY_SAMPLE |
| GB50_R050 | 12 | 33 | +€6,58 | 48,5% | 8 | 0 | PRELIMINARY_SAMPLE |
| GB30_R100 | 12 | 32 | +€5,69 | 46,9% | 7 | 1 | PRELIMINARY_SAMPLE |
| TP_R100 | 12 | 32 | +€2,70 | 46,9% | 7 | 1 | PRELIMINARY_SAMPLE |
| GB40_R100 | 12 | 32 | +€2,26 | 46,9% | 6 | 2 | PRELIMINARY_SAMPLE |
| GB50_R100 | 12 | 32 | €-0,65 | 43,8% | 6 | 3 | PRELIMINARY_SAMPLE |
| TIME_6H | 12 | 33 | €-2,79 | 54,5% | 10 | 3 | PRELIMINARY_SAMPLE |
| TP_R200 | 11 | 26 | +€14,94 | 46,2% | 1 | 1 | PRELIMINARY_SAMPLE |
| BE_R050 | 10 | 28 | €-2,02 | 35,7% | 7 | 0 | PRELIMINARY_SAMPLE |
| ATR15_R100 | 9 | 26 | €-0,46 | 53,8% | 1 | 2 | COLLECTING |
| TIME_12H | 8 | 26 | +€11,65 | 65,4% | 5 | 1 | COLLECTING |
| TIME_24H | 8 | 21 | +€3,54 | 66,7% | 2 | 2 | COLLECTING |
| ATR20_R100 | 8 | 23 | +€2,48 | 52,2% | 0 | 1 | COLLECTING |
| BE_R100 | 8 | 22 | +€2,01 | 45,5% | 0 | 1 | COLLECTING |
| ATR30_R100 | 8 | 23 | +€1,62 | 43,5% | 1 | 1 | COLLECTING |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
