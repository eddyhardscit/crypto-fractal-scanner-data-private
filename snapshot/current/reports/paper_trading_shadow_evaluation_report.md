# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-19T22:08:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **124**
- Valutazioni prodotte: **273**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R150 | 1 | 0,000 | 0,000 | 0,000 | 0,0% | 35,2 | INSUFFICIENT_DATA |
| ATR15_R100 | 0 | 0,000 | 0,000 | 0,000 | 0,0% | 25,0 | INSUFFICIENT_DATA |
| ATR20_R100 | 0 | 0,000 | 0,000 | 0,000 | 0,0% | 25,0 | INSUFFICIENT_DATA |
| ATR30_R100 | 0 | 0,000 | 0,000 | 0,000 | 0,0% | 25,0 | INSUFFICIENT_DATA |
| BE_R100 | 0 | 0,000 | 0,000 | 0,000 | 0,0% | 25,0 | INSUFFICIENT_DATA |
| TIME_12H | 0 | 0,000 | 0,000 | 0,000 | 0,0% | 25,0 | INSUFFICIENT_DATA |
| TIME_24H | 0 | 0,000 | 0,000 | 0,000 | 0,0% | 25,0 | INSUFFICIENT_DATA |
| TIME_6H | 0 | 0,000 | 0,000 | 0,000 | 0,0% | 25,0 | INSUFFICIENT_DATA |
| TP_R200 | 0 | 0,000 | 0,000 | 0,000 | 0,0% | 25,0 | INSUFFICIENT_DATA |
| GB20_R100 | 1 | -0,408 | -0,408 | -0,408 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| TP_R100 | 1 | -0,500 | -0,500 | -0,500 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| GB30_R100 | 1 | -0,545 | -0,545 | -0,545 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| GB40_R100 | 1 | -0,681 | -0,681 | -0,681 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| GB50_R100 | 1 | -0,779 | -0,779 | -0,779 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| TP_R050 | 1 | -0,999 | -0,999 | -0,999 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| GB20_R050 | 1 | -1,097 | -1,097 | -1,097 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| GB30_R050 | 1 | -1,147 | -1,147 | -1,147 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| GB40_R050 | 1 | -1,197 | -1,197 | -1,197 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| GB50_R050 | 1 | -1,248 | -1,248 | -1,248 | 0,0% | 10,2 | INSUFFICIENT_DATA |
| BE_R050 | 1 | -1,499 | -1,499 | -1,499 | 0,0% | 10,2 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
