# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T20:53:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **5280**
- Valutazioni prodotte: **2992**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 189 | 0,198 | 0,000 | 0,109 | 40,7% | 72,8 | VALIDATING |
| GB20_R050 | 240 | 0,197 | 0,000 | 0,093 | 49,6% | 70,0 | VALIDATING |
| GB30_R050 | 240 | 0,158 | 0,000 | 0,046 | 47,1% | 70,0 | VALIDATING |
| TP_R050 | 240 | 0,108 | 0,000 | 0,010 | 45,8% | 70,0 | VALIDATING |
| GB40_R050 | 240 | 0,117 | 0,000 | 0,008 | 46,7% | 70,0 | VALIDATING |
| GB20_R100 | 225 | 0,139 | 0,000 | 0,056 | 43,1% | 69,6 | VALIDATING |
| GB30_R100 | 225 | 0,103 | 0,000 | 0,025 | 39,6% | 69,5 | VALIDATING |
| TP_R150 | 205 | 0,094 | 0,000 | 0,015 | 33,7% | 69,0 | VALIDATING |
| TIME_12H | 209 | 0,073 | 0,000 | 0,006 | 38,8% | 68,4 | VALIDATING |
| GB50_R050 | 229 | 0,087 | 0,000 | -0,017 | 47,6% | 67,0 | VALIDATING |
| TP_R100 | 225 | 0,105 | 0,000 | 0,027 | 40,0% | 65,7 | VALIDATING |
| GB50_R100 | 206 | 0,089 | 0,000 | 0,027 | 40,3% | 65,5 | VALIDATING |
| GB40_R100 | 225 | 0,066 | 0,000 | -0,009 | 41,8% | 64,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TIME_6H | 215 | 0,012 | 0,036 | -0,088 | 54,4% | 55,9 | VALIDATING |
| BE_R050 | 202 | -0,052 | 0,000 | -0,165 | 32,7% | 39,1 | VALIDATING |
| ATR15_R100 | 222 | -0,052 | 0,000 | -0,103 | 27,5% | 35,2 | UNDERPERFORMING |
| TIME_24H | 169 | -0,019 | 0,000 | -0,147 | 34,9% | 35,0 | VALIDATING |
| ATR20_R100 | 184 | -0,074 | 0,000 | -0,149 | 27,7% | 31,8 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
