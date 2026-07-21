# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T19:53:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **5124**
- Valutazioni prodotte: **2986**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 186 | 0,196 | 0,000 | 0,103 | 40,9% | 72,7 | VALIDATING |
| GB40_R050 | 226 | 0,113 | 0,000 | 0,006 | 44,2% | 70,1 | VALIDATING |
| GB20_R050 | 226 | 0,191 | 0,000 | 0,087 | 47,3% | 70,0 | VALIDATING |
| GB30_R050 | 226 | 0,153 | 0,000 | 0,046 | 44,7% | 70,0 | VALIDATING |
| GB20_R100 | 221 | 0,138 | 0,000 | 0,053 | 43,0% | 69,5 | VALIDATING |
| GB30_R100 | 221 | 0,103 | 0,000 | 0,029 | 39,4% | 69,5 | VALIDATING |
| GB50_R100 | 190 | 0,116 | 0,000 | 0,049 | 42,6% | 69,2 | VALIDATING |
| TP_R150 | 203 | 0,098 | 0,000 | 0,022 | 34,0% | 69,0 | VALIDATING |
| TIME_12H | 207 | 0,072 | 0,000 | 0,006 | 38,6% | 68,9 | VALIDATING |
| TP_R050 | 226 | 0,096 | 0,000 | -0,008 | 43,4% | 68,9 | VALIDATING |
| GB50_R050 | 216 | 0,079 | 0,000 | -0,022 | 44,9% | 66,5 | VALIDATING |
| TP_R100 | 221 | 0,103 | 0,000 | 0,022 | 39,8% | 65,6 | VALIDATING |
| GB40_R100 | 221 | 0,066 | 0,000 | -0,008 | 41,6% | 64,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TIME_6H | 213 | 0,012 | 0,036 | -0,087 | 54,5% | 55,9 | VALIDATING |
| BE_R050 | 189 | -0,055 | 0,000 | -0,183 | 34,9% | 39,0 | VALIDATING |
| ATR15_R100 | 201 | -0,030 | 0,000 | -0,081 | 29,9% | 37,9 | VALIDATING |
| TIME_24H | 166 | -0,028 | 0,000 | -0,155 | 34,3% | 34,9 | VALIDATING |
| ATR20_R100 | 181 | -0,074 | 0,000 | -0,147 | 28,2% | 31,8 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
