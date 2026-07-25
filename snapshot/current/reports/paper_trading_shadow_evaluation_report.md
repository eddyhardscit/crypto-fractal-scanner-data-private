# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T07:08:54+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **19842**
- Valutazioni prodotte: **5534**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R100 | 318 | 0,195 | 0,217 | 0,111 | 62,6% | 96,3 | ELIGIBLE_FOR_MUTATION |
| GB40_R100 | 282 | 0,124 | 0,256 | 0,032 | 64,2% | 94,0 | VALIDATING |
| GB30_R100 | 294 | 0,157 | 0,263 | 0,056 | 63,3% | 93,2 | VALIDATING |
| GB50_R100 | 277 | 0,072 | 0,253 | -0,022 | 64,6% | 91,1 | VALIDATING |
| TP_R200 | 259 | 0,173 | 0,243 | 0,045 | 61,0% | 90,7 | ELIGIBLE_FOR_MUTATION |
| TP_R100 | 318 | 0,151 | 0,217 | 0,059 | 58,5% | 88,5 | VALIDATING |
| GB20_R050 | 320 | 0,062 | 0,168 | -0,033 | 58,4% | 79,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R150 | 285 | 0,148 | 0,000 | 0,046 | 46,3% | 73,3 | VALIDATING |
| GB20_R050 | 659 | 0,091 | 0,000 | 0,030 | 46,0% | 70,0 | VALIDATING |
| TP_R150 | 633 | 0,063 | 0,000 | 0,012 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 644 | 0,064 | 0,000 | 0,013 | 37,3% | 69,8 | VALIDATING |
| GB30_R050 | 659 | 0,051 | 0,000 | -0,014 | 44,5% | 67,9 | VALIDATING |
| TP_R200 | 623 | 0,050 | 0,000 | -0,013 | 35,2% | 64,0 | VALIDATING |
| GB30_R050 | 319 | 0,020 | 0,147 | -0,076 | 57,7% | 63,6 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 644 | 0,032 | 0,000 | -0,023 | 35,1% | 58,0 | VALIDATING |
| GB30_R100 | 644 | 0,025 | 0,000 | -0,031 | 37,0% | 54,5 | VALIDATING |
| GB50_R050 | 307 | -0,029 | 0,140 | -0,114 | 58,3% | 53,7 | VALIDATING |
| GB40_R050 | 309 | -0,015 | 0,149 | -0,111 | 57,6% | 53,2 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
