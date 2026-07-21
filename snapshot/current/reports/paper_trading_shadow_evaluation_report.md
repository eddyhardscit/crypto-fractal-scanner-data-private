# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T22:53:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **5895**
- Valutazioni prodotte: **3085**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 264 | 0,196 | 0,000 | 0,097 | 49,6% | 73,7 | VALIDATING |
| TP_R050 | 264 | 0,115 | 0,000 | 0,011 | 46,2% | 73,7 | VALIDATING |
| TP_R200 | 213 | 0,148 | 0,000 | 0,069 | 38,5% | 72,4 | VALIDATING |
| GB30_R050 | 264 | 0,158 | 0,000 | 0,065 | 47,3% | 69,9 | VALIDATING |
| GB40_R050 | 264 | 0,119 | 0,000 | 0,025 | 47,0% | 69,8 | VALIDATING |
| GB30_R100 | 249 | 0,067 | 0,000 | -0,001 | 37,8% | 69,4 | VALIDATING |
| GB20_R100 | 249 | 0,099 | 0,000 | 0,021 | 41,0% | 69,3 | VALIDATING |
| GB50_R050 | 264 | 0,076 | 0,000 | -0,008 | 45,8% | 68,3 | VALIDATING |
| TIME_12H | 235 | 0,054 | 0,000 | -0,015 | 37,4% | 66,4 | VALIDATING |
| TP_R100 | 249 | 0,067 | 0,000 | -0,010 | 37,8% | 64,3 | VALIDATING |
| TP_R150 | 229 | 0,056 | 0,000 | -0,020 | 32,3% | 61,9 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R100 | 245 | 0,034 | 0,000 | -0,027 | 35,9% | 58,0 | VALIDATING |
| GB40_R100 | 249 | 0,032 | 0,000 | -0,037 | 39,8% | 55,9 | VALIDATING |
| BE_R050 | 226 | -0,045 | 0,000 | -0,153 | 31,4% | 39,2 | VALIDATING |
| TIME_6H | 256 | -0,035 | 0,000 | -0,122 | 48,0% | 39,2 | VALIDATING |
| ATR15_R100 | 249 | -0,066 | 0,000 | -0,120 | 27,7% | 35,2 | UNDERPERFORMING |
| ATR20_R100 | 227 | -0,126 | 0,000 | -0,200 | 25,1% | 35,2 | UNDERPERFORMING |
| TIME_24H | 201 | -0,071 | 0,000 | -0,177 | 31,3% | 34,5 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
