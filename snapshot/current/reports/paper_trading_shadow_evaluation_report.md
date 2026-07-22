# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T01:53:40+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **6195**
- Valutazioni prodotte: **3114**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 278 | 0,221 | 0,036 | 0,130 | 50,4% | 84,2 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 226 | 0,142 | 0,000 | 0,057 | 38,5% | 72,5 | VALIDATING |
| GB30_R050 | 278 | 0,181 | 0,000 | 0,088 | 48,2% | 70,0 | VALIDATING |
| TP_R050 | 278 | 0,133 | 0,000 | 0,034 | 47,1% | 70,0 | VALIDATING |
| GB40_R050 | 278 | 0,140 | 0,000 | 0,048 | 47,8% | 70,0 | VALIDATING |
| GB50_R050 | 278 | 0,096 | 0,000 | 0,007 | 46,8% | 69,7 | VALIDATING |
| GB20_R100 | 265 | 0,090 | 0,000 | 0,018 | 40,8% | 69,3 | VALIDATING |
| GB30_R100 | 265 | 0,057 | 0,000 | -0,010 | 37,7% | 68,1 | VALIDATING |
| TIME_12H | 246 | 0,050 | 0,000 | -0,018 | 38,2% | 66,2 | VALIDATING |
| TP_R100 | 265 | 0,057 | 0,000 | -0,018 | 37,7% | 63,1 | VALIDATING |
| TP_R150 | 242 | 0,050 | 0,000 | -0,024 | 31,8% | 61,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R100 | 259 | 0,021 | 0,000 | -0,044 | 35,1% | 50,9 | VALIDATING |
| GB40_R100 | 265 | 0,022 | 0,000 | -0,049 | 38,5% | 50,3 | VALIDATING |
| BE_R050 | 236 | -0,031 | 0,000 | -0,139 | 33,5% | 39,2 | VALIDATING |
| TIME_6H | 272 | -0,029 | 0,000 | -0,115 | 48,2% | 35,5 | VALIDATING |
| ATR30_R100 | 216 | -0,203 | 0,000 | -0,295 | 25,5% | 33,8 | UNDERPERFORMING |
| BE_R100 | 205 | -0,151 | 0,000 | -0,250 | 26,8% | 33,7 | UNDERPERFORMING |
| ATR15_R100 | 262 | -0,075 | 0,000 | -0,125 | 27,5% | 31,6 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
