# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T14:53:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **3900**
- Valutazioni prodotte: **2860**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 154 | 0,069 | 0,054 | -0,037 | 61,0% | 89,0 | VALIDATING |
| GB20_R050 | 157 | 0,307 | 0,060 | 0,165 | 52,2% | 86,0 | VALIDATING |
| TP_R050 | 157 | 0,237 | 0,060 | 0,101 | 52,2% | 85,9 | VALIDATING |
| GB30_R050 | 157 | 0,278 | 0,060 | 0,148 | 51,6% | 85,4 | VALIDATING |
| GB40_R050 | 157 | 0,235 | 0,060 | 0,101 | 51,6% | 85,3 | VALIDATING |
| GB50_R050 | 157 | 0,192 | 0,044 | 0,064 | 51,6% | 84,8 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R100 | 155 | 0,173 | 0,000 | 0,063 | 45,2% | 73,3 | VALIDATING |
| GB30_R100 | 154 | 0,148 | 0,000 | 0,046 | 44,2% | 73,3 | VALIDATING |
| TP_R100 | 155 | 0,155 | 0,000 | 0,052 | 43,9% | 73,2 | VALIDATING |
| TP_R200 | 141 | 0,130 | 0,000 | 0,031 | 39,0% | 73,1 | VALIDATING |
| GB40_R100 | 154 | 0,108 | 0,000 | 0,012 | 44,8% | 69,4 | VALIDATING |
| GB50_R100 | 139 | 0,146 | 0,000 | 0,067 | 46,0% | 69,2 | VALIDATING |
| TIME_12H | 143 | 0,109 | 0,000 | 0,013 | 44,1% | 68,4 | VALIDATING |
| TP_R150 | 146 | 0,076 | 0,000 | -0,026 | 35,6% | 64,8 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| ATR15_R100 | 136 | 0,019 | 0,000 | -0,048 | 39,0% | 49,6 | VALIDATING |
| ATR20_R100 | 135 | -0,014 | 0,000 | -0,108 | 37,8% | 35,6 | VALIDATING |
| BE_R050 | 153 | -0,071 | 0,000 | -0,219 | 39,9% | 34,9 | VALIDATING |
| TIME_24H | 126 | -0,074 | 0,000 | -0,255 | 34,9% | 34,2 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
