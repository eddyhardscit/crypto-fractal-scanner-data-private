# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T12:23:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **1657**
- Valutazioni prodotte: **1991**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB50_R100 | 43 | 0,134 | 0,000 | 0,013 | 44,2% | 61,6 | EARLY_SIGNAL |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R050 | 47 | 0,198 | 0,000 | -0,031 | 44,7% | 54,2 | EARLY_SIGNAL |
| TP_R200 | 49 | 0,122 | 0,000 | -0,045 | 32,7% | 48,7 | EARLY_SIGNAL |
| GB20_R050 | 53 | 0,151 | 0,000 | -0,075 | 41,5% | 45,2 | VALIDATING |
| GB20_R100 | 53 | 0,058 | 0,000 | -0,113 | 37,7% | 41,6 | VALIDATING |
| GB30_R050 | 53 | 0,113 | 0,000 | -0,121 | 39,6% | 41,5 | VALIDATING |
| GB40_R050 | 52 | 0,082 | 0,000 | -0,157 | 40,4% | 41,2 | VALIDATING |
| TP_R050 | 53 | 0,044 | 0,000 | -0,205 | 41,5% | 41,1 | VALIDATING |
| TIME_12H | 38 | 0,089 | 0,000 | -0,123 | 31,6% | 33,4 | EARLY_SIGNAL |
| BE_R050 | 46 | 0,029 | 0,000 | -0,165 | 30,4% | 31,5 | EARLY_SIGNAL |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| GB30_R100 | 53 | 0,006 | 0,000 | -0,153 | 37,7% | 28,5 | VALIDATING |
| TP_R100 | 53 | -0,003 | 0,000 | -0,175 | 37,7% | 26,3 | VALIDATING |
| GB40_R100 | 52 | -0,038 | 0,000 | -0,193 | 38,5% | 26,1 | VALIDATING |
| TP_R150 | 52 | -0,006 | 0,000 | -0,152 | 28,8% | 26,0 | VALIDATING |
| TIME_24H | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 25,2 | INSUFFICIENT_DATA |
| TIME_6H | 45 | -0,021 | 0,000 | -0,174 | 40,0% | 21,0 | EARLY_SIGNAL |
| ATR15_R100 | 42 | 0,001 | 0,000 | -0,076 | 35,7% | 20,9 | EARLY_SIGNAL |
| ATR20_R100 | 39 | -0,010 | 0,000 | -0,102 | 30,8% | 16,6 | EARLY_SIGNAL |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
