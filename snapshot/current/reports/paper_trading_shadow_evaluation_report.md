# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T16:53:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **4715**
- Valutazioni prodotte: **2917**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 202 | 0,233 | 0,000 | 0,120 | 47,0% | 73,9 | VALIDATING |
| TP_R050 | 202 | 0,175 | 0,000 | 0,068 | 47,0% | 73,8 | VALIDATING |
| TIME_6H | 202 | 0,049 | 0,036 | -0,055 | 56,4% | 73,8 | VALIDATING |
| GB50_R100 | 183 | 0,121 | 0,000 | 0,052 | 42,6% | 73,3 | VALIDATING |
| GB20_R100 | 199 | 0,151 | 0,000 | 0,061 | 40,7% | 73,2 | VALIDATING |
| TP_R200 | 164 | 0,118 | 0,000 | 0,035 | 34,8% | 73,1 | VALIDATING |
| TP_R100 | 199 | 0,137 | 0,000 | 0,052 | 40,7% | 73,1 | VALIDATING |
| TIME_12H | 173 | 0,111 | 0,000 | 0,035 | 41,0% | 72,4 | VALIDATING |
| GB30_R050 | 202 | 0,203 | 0,000 | 0,081 | 47,0% | 70,2 | VALIDATING |
| GB40_R050 | 202 | 0,160 | 0,000 | 0,040 | 46,5% | 70,1 | VALIDATING |
| GB30_R100 | 198 | 0,120 | 0,000 | 0,042 | 39,4% | 69,8 | VALIDATING |
| GB50_R050 | 202 | 0,119 | 0,000 | 0,011 | 46,5% | 69,7 | VALIDATING |
| TP_R150 | 183 | 0,086 | 0,000 | 0,001 | 32,2% | 68,6 | VALIDATING |
| GB40_R100 | 198 | 0,086 | 0,000 | 0,008 | 41,9% | 65,6 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| ATR15_R100 | 174 | -0,017 | 0,000 | -0,074 | 31,6% | 38,7 | VALIDATING |
| ATR20_R100 | 174 | -0,062 | 0,000 | -0,139 | 29,3% | 35,6 | VALIDATING |
| BE_R050 | 182 | -0,044 | 0,000 | -0,171 | 35,7% | 35,2 | VALIDATING |
| TIME_24H | 156 | -0,034 | 0,000 | -0,169 | 32,1% | 34,8 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
