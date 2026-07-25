# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T23:38:57+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **25888**
- Valutazioni prodotte: **9344**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R100 | 48 | 0,770 | 1,084 | 0,561 | 79,2% | 88,6 | EARLY_SIGNAL |
| GB20_R075 | 48 | 0,728 | 0,843 | 0,530 | 72,9% | 88,6 | EARLY_SIGNAL |
| GB20_R100 | 48 | 0,795 | 1,262 | 0,575 | 79,2% | 88,5 | EARLY_SIGNAL |
| GB30_R075 | 48 | 0,644 | 0,748 | 0,456 | 66,7% | 88,5 | EARLY_SIGNAL |
| GB30_R100 | 48 | 0,709 | 1,140 | 0,502 | 79,2% | 88,5 | EARLY_SIGNAL |
| TP_R075 | 48 | 0,624 | 0,834 | 0,461 | 81,2% | 88,5 | EARLY_SIGNAL |
| GB40_R075 | 48 | 0,561 | 0,654 | 0,372 | 66,7% | 88,5 | EARLY_SIGNAL |
| GB40_R100 | 48 | 0,613 | 0,996 | 0,438 | 79,2% | 88,4 | EARLY_SIGNAL |
| GB50_R075 | 48 | 0,505 | 0,559 | 0,325 | 70,8% | 88,4 | EARLY_SIGNAL |
| TP_R060 | 48 | 0,511 | 0,684 | 0,354 | 72,9% | 88,4 | EARLY_SIGNAL |
| GB50_R100 | 48 | 0,518 | 0,844 | 0,329 | 70,8% | 88,4 | EARLY_SIGNAL |
| TP_R050 | 48 | 0,437 | 0,585 | 0,293 | 66,7% | 88,3 | EARLY_SIGNAL |
| GB40_R040 | 48 | 0,410 | 0,654 | 0,252 | 66,7% | 88,3 | EARLY_SIGNAL |
| GB40_R050 | 48 | 0,410 | 0,654 | 0,254 | 66,7% | 88,3 | EARLY_SIGNAL |
| GB20_R040 | 48 | 0,427 | 0,659 | 0,294 | 72,9% | 88,2 | EARLY_SIGNAL |
| GB20_R050 | 48 | 0,427 | 0,659 | 0,274 | 72,9% | 88,2 | EARLY_SIGNAL |
| TP_R040 | 48 | 0,362 | 0,485 | 0,213 | 66,7% | 88,2 | EARLY_SIGNAL |
| GB50_R050 | 48 | 0,379 | 0,559 | 0,236 | 70,8% | 88,2 | EARLY_SIGNAL |
| GB30_R040 | 48 | 0,398 | 0,639 | 0,244 | 66,7% | 88,2 | EARLY_SIGNAL |
| GB30_R050 | 48 | 0,398 | 0,639 | 0,250 | 66,7% | 88,2 | EARLY_SIGNAL |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
