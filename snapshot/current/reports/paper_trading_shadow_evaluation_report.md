# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T21:39:03+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **25312**
- Valutazioni prodotte: **8664**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R075 | 38 | 0,676 | 1,035 | 0,498 | 81,6% | 86,8 | EARLY_SIGNAL |
| GB20_R075 | 38 | 0,818 | 1,262 | 0,586 | 81,6% | 86,7 | EARLY_SIGNAL |
| GB30_R075 | 38 | 0,732 | 1,140 | 0,525 | 78,9% | 86,7 | EARLY_SIGNAL |
| GB20_R040 | 38 | 0,459 | 0,689 | 0,303 | 81,6% | 83,0 | EARLY_SIGNAL |
| GB20_R050 | 38 | 0,459 | 0,689 | 0,305 | 81,6% | 83,0 | EARLY_SIGNAL |
| GB30_R040 | 38 | 0,434 | 0,639 | 0,282 | 78,9% | 83,0 | EARLY_SIGNAL |
| GB30_R050 | 38 | 0,434 | 0,639 | 0,277 | 78,9% | 83,0 | EARLY_SIGNAL |
| GB20_R100 | 38 | 0,836 | 1,262 | 0,591 | 78,9% | 83,0 | EARLY_SIGNAL |
| TP_R100 | 38 | 0,808 | 1,284 | 0,565 | 78,9% | 83,0 | EARLY_SIGNAL |
| GB30_R100 | 38 | 0,753 | 1,140 | 0,525 | 78,9% | 83,0 | EARLY_SIGNAL |
| TP_R060 | 38 | 0,566 | 0,885 | 0,392 | 81,6% | 83,0 | EARLY_SIGNAL |
| GB40_R040 | 38 | 0,462 | 0,711 | 0,300 | 78,9% | 83,0 | EARLY_SIGNAL |
| GB40_R050 | 38 | 0,462 | 0,711 | 0,291 | 78,9% | 83,0 | EARLY_SIGNAL |
| GB40_R100 | 38 | 0,660 | 1,018 | 0,461 | 78,9% | 83,0 | EARLY_SIGNAL |
| TP_R050 | 38 | 0,492 | 0,785 | 0,341 | 78,9% | 83,0 | EARLY_SIGNAL |
| GB50_R050 | 38 | 0,406 | 0,640 | 0,247 | 78,9% | 83,0 | EARLY_SIGNAL |
| ATR10_R050 | 38 | 0,208 | 0,359 | 0,101 | 81,6% | 83,0 | EARLY_SIGNAL |
| GB50_R100 | 38 | 0,566 | 0,896 | 0,354 | 78,9% | 83,0 | EARLY_SIGNAL |
| TP_R040 | 38 | 0,419 | 0,685 | 0,248 | 78,9% | 83,0 | EARLY_SIGNAL |
| TP_R035 | 38 | 0,382 | 0,635 | 0,234 | 78,9% | 83,0 | EARLY_SIGNAL |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
