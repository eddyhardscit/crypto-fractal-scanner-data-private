# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T12:38:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **3512**
- Valutazioni prodotte: **2669**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 134 | 0,072 | 0,036 | -0,025 | 59,7% | 85,7 | VALIDATING |
| GB20_R050 | 139 | 0,322 | 0,075 | 0,172 | 54,0% | 84,1 | VALIDATING |
| TP_R050 | 139 | 0,239 | 0,075 | 0,103 | 54,0% | 84,0 | VALIDATING |
| GB30_R050 | 139 | 0,294 | 0,075 | 0,158 | 53,2% | 83,3 | VALIDATING |
| GB40_R050 | 139 | 0,250 | 0,075 | 0,109 | 53,2% | 83,3 | VALIDATING |
| GB50_R050 | 139 | 0,205 | 0,060 | 0,087 | 53,2% | 82,7 | VALIDATING |
| GB20_R100 | 137 | 0,226 | 0,033 | 0,109 | 51,1% | 80,6 | VALIDATING |
| GB50_R100 | 126 | 0,161 | 0,033 | 0,066 | 50,8% | 80,0 | VALIDATING |
| GB40_R100 | 137 | 0,152 | 0,033 | 0,054 | 50,4% | 79,8 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 124 | 0,139 | 0,000 | 0,027 | 43,5% | 73,0 | VALIDATING |
| GB30_R100 | 137 | 0,193 | 0,000 | 0,085 | 49,6% | 69,5 | VALIDATING |
| TP_R100 | 137 | 0,205 | 0,000 | 0,091 | 49,6% | 69,5 | VALIDATING |
| TIME_12H | 127 | 0,153 | 0,000 | 0,054 | 49,6% | 68,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 124 | 0,034 | 0,000 | -0,060 | 38,7% | 56,5 | VALIDATING |
| ATR15_R100 | 122 | 0,020 | 0,000 | -0,064 | 42,6% | 51,2 | VALIDATING |
| ATR20_R100 | 122 | -0,015 | 0,000 | -0,122 | 41,8% | 39,3 | VALIDATING |
| TIME_24H | 112 | -0,081 | 0,000 | -0,286 | 39,3% | 34,2 | VALIDATING |
| ATR30_R100 | 121 | -0,138 | 0,000 | -0,289 | 39,7% | 33,6 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
