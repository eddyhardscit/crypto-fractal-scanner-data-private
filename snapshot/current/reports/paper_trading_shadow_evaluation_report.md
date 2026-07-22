# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T15:23:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **8730**
- Valutazioni prodotte: **3266**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 382 | 0,157 | 0,039 | 0,086 | 52,4% | 85,2 | VALIDATING |
| TIME_6H | 389 | 0,045 | 0,054 | -0,035 | 56,3% | 80,8 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 394 | 0,206 | 0,000 | 0,128 | 49,2% | 73,8 | VALIDATING |
| TP_R050 | 394 | 0,135 | 0,000 | 0,051 | 47,0% | 73,8 | VALIDATING |
| GB30_R050 | 394 | 0,168 | 0,000 | 0,090 | 47,7% | 73,8 | VALIDATING |
| GB40_R050 | 394 | 0,130 | 0,000 | 0,052 | 47,5% | 73,7 | VALIDATING |
| GB50_R050 | 394 | 0,090 | 0,000 | 0,013 | 46,7% | 73,5 | VALIDATING |
| TP_R200 | 349 | 0,094 | 0,000 | 0,021 | 35,8% | 72,8 | VALIDATING |
| GB20_R100 | 380 | 0,067 | 0,000 | 0,009 | 36,8% | 69,4 | VALIDATING |
| GB40_R100 | 380 | 0,042 | 0,000 | -0,013 | 36,3% | 66,7 | VALIDATING |
| GB30_R100 | 380 | 0,053 | 0,000 | -0,005 | 36,3% | 65,2 | VALIDATING |
| TP_R100 | 380 | 0,039 | 0,000 | -0,016 | 34,7% | 61,6 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 366 | 0,025 | 0,000 | -0,034 | 28,7% | 57,0 | VALIDATING |
| GB50_R100 | 358 | 0,010 | 0,000 | -0,036 | 32,4% | 52,2 | VALIDATING |
| ATR15_R100 | 378 | -0,034 | 0,000 | -0,082 | 28,0% | 34,0 | VALIDATING |
| TIME_24H | 340 | -0,120 | 0,000 | -0,216 | 29,1% | 33,5 | UNDERPERFORMING |
| BE_R050 | 358 | -0,064 | 0,000 | -0,145 | 32,1% | 32,1 | VALIDATING |
| ATR20_R100 | 347 | -0,131 | 0,000 | -0,184 | 22,2% | 31,5 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
