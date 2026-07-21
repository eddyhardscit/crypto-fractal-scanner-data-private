# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T09:38:40+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **3160**
- Valutazioni prodotte: **2387**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 117 | 0,065 | 0,049 | -0,044 | 56,4% | 79,3 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TIME_12H | 114 | 0,142 | 0,000 | 0,029 | 45,6% | 72,5 | VALIDATING |
| GB20_R050 | 118 | 0,234 | 0,000 | 0,089 | 47,5% | 70,1 | VALIDATING |
| GB30_R050 | 118 | 0,199 | 0,000 | 0,050 | 46,6% | 70,0 | VALIDATING |
| GB40_R050 | 118 | 0,159 | 0,000 | 0,017 | 46,6% | 70,0 | VALIDATING |
| GB20_R100 | 118 | 0,137 | 0,000 | 0,021 | 44,9% | 69,4 | VALIDATING |
| TP_R050 | 118 | 0,153 | 0,000 | -0,007 | 47,5% | 69,0 | VALIDATING |
| GB50_R100 | 107 | 0,089 | 0,000 | -0,002 | 43,9% | 68,6 | VALIDATING |
| TP_R100 | 118 | 0,102 | 0,000 | -0,008 | 43,2% | 68,1 | VALIDATING |
| TP_R200 | 114 | 0,104 | 0,000 | -0,011 | 38,6% | 67,2 | VALIDATING |
| GB50_R050 | 118 | 0,151 | 0,000 | 0,012 | 46,6% | 66,2 | VALIDATING |
| GB30_R100 | 115 | 0,087 | 0,000 | -0,021 | 42,6% | 66,0 | VALIDATING |
| GB40_R100 | 115 | 0,056 | 0,000 | -0,052 | 43,5% | 61,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 115 | 0,003 | 0,000 | -0,097 | 33,9% | 41,1 | VALIDATING |
| ATR20_R100 | 105 | -0,080 | 0,000 | -0,193 | 39,0% | 38,5 | VALIDATING |
| ATR15_R100 | 105 | -0,039 | 0,000 | -0,122 | 40,0% | 38,0 | VALIDATING |
| BE_R050 | 116 | -0,142 | 0,000 | -0,335 | 37,9% | 34,9 | VALIDATING |
| ATR30_R100 | 104 | -0,223 | 0,000 | -0,377 | 36,5% | 32,9 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
