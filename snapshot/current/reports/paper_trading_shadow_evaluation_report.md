# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T10:38:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **3300**
- Valutazioni prodotte: **2547**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 124 | 0,088 | 0,057 | -0,021 | 58,9% | 85,3 | VALIDATING |
| TP_R050 | 125 | 0,207 | 0,060 | 0,048 | 50,4% | 80,2 | VALIDATING |
| GB20_R050 | 125 | 0,281 | 0,029 | 0,140 | 50,4% | 80,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB30_R050 | 125 | 0,247 | 0,000 | 0,097 | 49,6% | 69,9 | VALIDATING |
| GB40_R050 | 125 | 0,209 | 0,000 | 0,061 | 49,6% | 69,8 | VALIDATING |
| GB20_R100 | 125 | 0,156 | 0,000 | 0,056 | 48,0% | 69,6 | VALIDATING |
| TP_R100 | 125 | 0,123 | 0,000 | 0,015 | 46,4% | 69,5 | VALIDATING |
| GB30_R100 | 122 | 0,109 | 0,000 | 0,011 | 45,9% | 69,4 | VALIDATING |
| GB50_R100 | 114 | 0,112 | 0,000 | 0,026 | 47,4% | 69,2 | VALIDATING |
| GB50_R050 | 125 | 0,169 | 0,000 | 0,037 | 49,6% | 69,1 | VALIDATING |
| TP_R200 | 121 | 0,126 | 0,000 | 0,013 | 42,1% | 69,1 | VALIDATING |
| TIME_12H | 121 | 0,161 | 0,000 | 0,058 | 48,8% | 69,0 | VALIDATING |
| GB40_R100 | 122 | 0,080 | 0,000 | -0,019 | 46,7% | 66,5 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 122 | 0,030 | 0,000 | -0,065 | 37,7% | 54,5 | VALIDATING |
| ATR15_R100 | 112 | -0,007 | 0,000 | -0,091 | 43,8% | 40,2 | VALIDATING |
| ATR20_R100 | 112 | -0,045 | 0,000 | -0,159 | 42,9% | 39,2 | VALIDATING |
| BE_R050 | 123 | -0,107 | 0,000 | -0,291 | 41,5% | 38,2 | VALIDATING |
| TIME_24H | 111 | -0,089 | 0,000 | -0,282 | 38,7% | 34,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
