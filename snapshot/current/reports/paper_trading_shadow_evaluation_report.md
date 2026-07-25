# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T22:38:52+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **25462**
- Valutazioni prodotte: **8865**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R100 | 44 | 0,749 | 1,084 | 0,536 | 81,8% | 88,0 | EARLY_SIGNAL |
| GB20_R100 | 44 | 0,771 | 1,262 | 0,555 | 81,8% | 88,0 | EARLY_SIGNAL |
| GB30_R100 | 44 | 0,683 | 1,140 | 0,485 | 81,8% | 88,0 | EARLY_SIGNAL |
| TP_R075 | 44 | 0,601 | 0,834 | 0,434 | 84,1% | 88,0 | EARLY_SIGNAL |
| GB20_R040 | 44 | 0,398 | 0,659 | 0,244 | 75,0% | 88,0 | EARLY_SIGNAL |
| GB20_R050 | 44 | 0,398 | 0,659 | 0,267 | 75,0% | 88,0 | EARLY_SIGNAL |
| GB40_R100 | 44 | 0,585 | 0,996 | 0,416 | 81,8% | 88,0 | EARLY_SIGNAL |
| GB30_R040 | 44 | 0,366 | 0,639 | 0,223 | 68,2% | 88,0 | EARLY_SIGNAL |
| GB30_R050 | 44 | 0,366 | 0,639 | 0,228 | 68,2% | 88,0 | EARLY_SIGNAL |
| TP_R060 | 44 | 0,485 | 0,684 | 0,319 | 75,0% | 88,0 | EARLY_SIGNAL |
| GB40_R040 | 44 | 0,379 | 0,654 | 0,228 | 68,2% | 88,0 | EARLY_SIGNAL |
| GB40_R050 | 44 | 0,379 | 0,654 | 0,223 | 68,2% | 88,0 | EARLY_SIGNAL |
| TP_R050 | 44 | 0,408 | 0,585 | 0,265 | 68,2% | 88,0 | EARLY_SIGNAL |
| GB20_R075 | 44 | 0,708 | 0,843 | 0,505 | 75,0% | 87,9 | EARLY_SIGNAL |
| GB30_R075 | 44 | 0,623 | 0,748 | 0,428 | 68,2% | 87,9 | EARLY_SIGNAL |
| GB40_R075 | 44 | 0,537 | 0,654 | 0,346 | 68,2% | 87,9 | EARLY_SIGNAL |
| GB50_R100 | 44 | 0,488 | 0,844 | 0,291 | 72,7% | 84,2 | EARLY_SIGNAL |
| GB50_R050 | 44 | 0,349 | 0,559 | 0,210 | 72,7% | 84,2 | EARLY_SIGNAL |
| ATR10_R050 | 44 | 0,167 | 0,265 | 0,070 | 70,5% | 84,2 | EARLY_SIGNAL |
| TP_R040 | 44 | 0,331 | 0,485 | 0,190 | 68,2% | 84,2 | EARLY_SIGNAL |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
