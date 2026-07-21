# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T21:53:40+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **5386**
- Valutazioni prodotte: **2996**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 248 | 0,202 | 0,059 | 0,100 | 50,8% | 84,5 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 190 | 0,201 | 0,000 | 0,115 | 41,1% | 72,8 | VALIDATING |
| TIME_12H | 212 | 0,092 | 0,000 | 0,024 | 39,6% | 72,4 | VALIDATING |
| GB30_R050 | 248 | 0,162 | 0,000 | 0,059 | 48,4% | 70,1 | VALIDATING |
| TP_R050 | 248 | 0,116 | 0,000 | 0,021 | 47,2% | 70,0 | VALIDATING |
| GB40_R050 | 248 | 0,121 | 0,000 | 0,022 | 48,0% | 70,0 | VALIDATING |
| GB20_R100 | 226 | 0,140 | 0,000 | 0,058 | 43,4% | 69,6 | VALIDATING |
| GB30_R100 | 226 | 0,104 | 0,000 | 0,028 | 39,8% | 69,5 | VALIDATING |
| TP_R150 | 206 | 0,095 | 0,000 | 0,017 | 34,0% | 69,0 | VALIDATING |
| GB50_R050 | 248 | 0,075 | 0,000 | -0,012 | 46,8% | 67,8 | VALIDATING |
| TP_R100 | 226 | 0,104 | 0,000 | 0,023 | 39,8% | 65,7 | VALIDATING |
| GB50_R100 | 221 | 0,066 | 0,000 | 0,002 | 37,6% | 65,5 | VALIDATING |
| GB40_R100 | 226 | 0,066 | 0,000 | -0,007 | 42,0% | 64,6 | VALIDATING |
| TIME_6H | 220 | 0,010 | 0,036 | -0,082 | 54,1% | 59,6 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| BE_R050 | 209 | -0,051 | 0,000 | -0,167 | 31,6% | 39,1 | VALIDATING |
| TIME_24H | 172 | -0,035 | 0,000 | -0,162 | 34,3% | 38,8 | VALIDATING |
| ATR15_R100 | 226 | -0,043 | 0,000 | -0,100 | 28,8% | 35,2 | VALIDATING |
| ATR20_R100 | 196 | -0,108 | 0,000 | -0,181 | 26,0% | 31,8 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
