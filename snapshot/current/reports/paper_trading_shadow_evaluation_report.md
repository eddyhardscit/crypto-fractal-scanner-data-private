# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T10:23:36+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **1348**
- Valutazioni prodotte: **1743**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB50_R050 | 32 | 0,439 | 0,075 | 0,212 | 62,5% | 82,9 | EARLY_SIGNAL |
| GB20_R050 | 37 | 0,344 | 0,075 | 0,072 | 54,1% | 71,8 | EARLY_SIGNAL |
| GB30_R050 | 37 | 0,294 | 0,075 | 0,030 | 54,1% | 71,8 | EARLY_SIGNAL |
| GB50_R100 | 31 | 0,184 | 0,033 | 0,014 | 58,1% | 69,8 | EARLY_SIGNAL |
| GB40_R050 | 37 | 0,233 | 0,075 | -0,044 | 54,1% | 65,2 | EARLY_SIGNAL |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R050 | 37 | 0,189 | 0,075 | -0,127 | 54,1% | 56,8 | EARLY_SIGNAL |
| GB20_R100 | 37 | 0,149 | 0,033 | -0,068 | 51,4% | 54,5 | EARLY_SIGNAL |
| BE_R050 | 31 | 0,235 | 0,000 | 0,067 | 41,9% | 52,5 | EARLY_SIGNAL |
| GB30_R100 | 37 | 0,097 | 0,033 | -0,118 | 51,4% | 49,6 | EARLY_SIGNAL |
| TP_R100 | 37 | 0,081 | 0,033 | -0,152 | 51,4% | 49,3 | EARLY_SIGNAL |
| GB40_R100 | 37 | 0,033 | 0,033 | -0,175 | 51,4% | 45,4 | EARLY_SIGNAL |
| TP_R200 | 36 | 0,158 | 0,000 | -0,077 | 41,7% | 41,2 | EARLY_SIGNAL |
| BE_R100 | 27 | 0,033 | 0,000 | -0,081 | 44,4% | 31,8 | INSUFFICIENT_DATA |
| ATR30_R100 | 27 | 0,033 | 0,000 | -0,081 | 44,4% | 31,8 | INSUFFICIENT_DATA |
| ATR20_R100 | 27 | 0,033 | 0,000 | -0,101 | 44,4% | 28,9 | INSUFFICIENT_DATA |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| ATR15_R100 | 31 | 0,012 | 0,000 | -0,087 | 48,4% | 24,7 | EARLY_SIGNAL |
| TIME_6H | 31 | -0,015 | 0,000 | -0,177 | 45,2% | 21,2 | EARLY_SIGNAL |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
