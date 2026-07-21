# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T15:53:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **4466**
- Valutazioni prodotte: **2885**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 189 | 0,110 | 0,049 | 0,017 | 58,2% | 87,4 | ELIGIBLE_FOR_MUTATION |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 189 | 0,260 | 0,000 | 0,142 | 48,1% | 73,8 | VALIDATING |
| GB30_R050 | 189 | 0,233 | 0,000 | 0,116 | 48,1% | 73,8 | VALIDATING |
| GB40_R050 | 189 | 0,192 | 0,000 | 0,071 | 47,6% | 73,8 | VALIDATING |
| TP_R050 | 189 | 0,203 | 0,000 | 0,093 | 48,1% | 73,8 | VALIDATING |
| GB30_R100 | 185 | 0,156 | 0,000 | 0,072 | 42,2% | 73,5 | VALIDATING |
| GB50_R050 | 189 | 0,153 | 0,000 | 0,049 | 47,6% | 73,3 | VALIDATING |
| GB50_R100 | 173 | 0,150 | 0,000 | 0,083 | 45,1% | 73,3 | VALIDATING |
| GB20_R100 | 186 | 0,184 | 0,000 | 0,093 | 43,5% | 73,2 | VALIDATING |
| TP_R100 | 186 | 0,170 | 0,000 | 0,078 | 43,5% | 73,1 | VALIDATING |
| GB40_R100 | 185 | 0,124 | 0,000 | 0,044 | 44,9% | 69,3 | VALIDATING |
| TP_R200 | 158 | 0,116 | 0,000 | 0,034 | 34,8% | 69,3 | VALIDATING |
| TIME_12H | 169 | 0,114 | 0,000 | 0,036 | 42,0% | 68,7 | VALIDATING |
| TP_R150 | 170 | 0,093 | 0,000 | 0,002 | 34,7% | 65,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| ATR15_R100 | 162 | 0,013 | 0,000 | -0,042 | 34,0% | 47,7 | VALIDATING |
| ATR20_R100 | 162 | -0,021 | 0,000 | -0,102 | 31,5% | 35,6 | VALIDATING |
| BE_R050 | 178 | -0,068 | 0,000 | -0,197 | 34,3% | 35,1 | VALIDATING |
| TIME_24H | 146 | -0,062 | 0,000 | -0,194 | 31,5% | 34,2 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
