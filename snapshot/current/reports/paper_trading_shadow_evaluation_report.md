# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T11:23:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **1481**
- Valutazioni prodotte: **1861**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB50_R100 | 36 | 0,161 | 0,033 | 0,013 | 52,8% | 69,3 | EARLY_SIGNAL |
| GB50_R050 | 39 | 0,236 | 0,044 | -0,012 | 51,3% | 67,5 | EARLY_SIGNAL |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB20_R050 | 44 | 0,194 | 0,000 | -0,052 | 47,7% | 50,5 | EARLY_SIGNAL |
| GB30_R050 | 44 | 0,147 | 0,000 | -0,112 | 45,5% | 44,2 | EARLY_SIGNAL |
| GB40_R050 | 44 | 0,091 | 0,000 | -0,174 | 45,5% | 44,1 | EARLY_SIGNAL |
| GB20_R100 | 44 | 0,088 | 0,000 | -0,121 | 45,5% | 43,6 | EARLY_SIGNAL |
| TP_R200 | 42 | 0,142 | 0,000 | -0,049 | 38,1% | 43,0 | EARLY_SIGNAL |
| BE_R050 | 37 | 0,093 | 0,000 | -0,126 | 35,1% | 42,5 | EARLY_SIGNAL |
| TP_R050 | 44 | 0,067 | 0,000 | -0,210 | 47,7% | 39,4 | EARLY_SIGNAL |
| GB30_R100 | 44 | 0,032 | 0,000 | -0,166 | 45,5% | 39,1 | EARLY_SIGNAL |
| TP_R100 | 44 | 0,021 | 0,000 | -0,197 | 45,5% | 35,2 | EARLY_SIGNAL |
| BE_R100 | 30 | 0,030 | 0,000 | -0,065 | 40,0% | 33,7 | EARLY_SIGNAL |
| ATR30_R100 | 30 | 0,030 | 0,000 | -0,080 | 40,0% | 31,3 | EARLY_SIGNAL |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| GB40_R100 | 44 | -0,035 | 0,000 | -0,232 | 45,5% | 28,3 | EARLY_SIGNAL |
| ATR15_R100 | 34 | 0,011 | 0,000 | -0,082 | 44,1% | 25,7 | EARLY_SIGNAL |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| TIME_6H | 37 | -0,060 | 0,000 | -0,238 | 40,5% | 22,6 | EARLY_SIGNAL |
| TP_R150 | 43 | -0,005 | 0,000 | -0,186 | 34,9% | 20,4 | EARLY_SIGNAL |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
