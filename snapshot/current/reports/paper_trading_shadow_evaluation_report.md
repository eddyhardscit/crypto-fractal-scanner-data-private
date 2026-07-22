# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T14:23:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **8708**
- Valutazioni prodotte: **3265**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_12H | 379 | 0,174 | 0,043 | 0,104 | 52,8% | 85,6 | VALIDATING |
| TIME_6H | 389 | 0,045 | 0,054 | -0,035 | 56,3% | 80,8 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 393 | 0,206 | 0,000 | 0,126 | 49,1% | 73,8 | VALIDATING |
| TP_R050 | 393 | 0,134 | 0,000 | 0,052 | 46,8% | 73,8 | VALIDATING |
| GB30_R050 | 393 | 0,167 | 0,000 | 0,088 | 47,6% | 73,8 | VALIDATING |
| GB40_R050 | 393 | 0,130 | 0,000 | 0,053 | 47,3% | 73,7 | VALIDATING |
| GB50_R050 | 393 | 0,090 | 0,000 | 0,012 | 46,6% | 73,5 | VALIDATING |
| TP_R200 | 346 | 0,112 | 0,000 | 0,043 | 36,1% | 72,8 | VALIDATING |
| GB20_R100 | 380 | 0,067 | 0,000 | 0,009 | 36,8% | 69,4 | VALIDATING |
| GB40_R100 | 380 | 0,042 | 0,000 | -0,013 | 36,3% | 66,7 | VALIDATING |
| GB30_R100 | 380 | 0,053 | 0,000 | -0,005 | 36,3% | 65,2 | VALIDATING |
| TP_R100 | 380 | 0,039 | 0,000 | -0,016 | 34,7% | 61,6 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 366 | 0,025 | 0,000 | -0,034 | 28,7% | 57,0 | VALIDATING |
| GB50_R100 | 358 | 0,010 | 0,000 | -0,036 | 32,4% | 52,2 | VALIDATING |
| ATR15_R100 | 377 | -0,035 | 0,000 | -0,084 | 27,9% | 33,8 | VALIDATING |
| TIME_24H | 335 | -0,110 | 0,000 | -0,201 | 29,0% | 33,6 | UNDERPERFORMING |
| BE_R050 | 356 | -0,064 | 0,000 | -0,144 | 32,3% | 32,1 | VALIDATING |
| BE_R100 | 313 | -0,193 | 0,000 | -0,273 | 23,0% | 30,3 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
