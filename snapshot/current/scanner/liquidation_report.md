# Report semplice futures / liquidazioni BTC / SOL / DOGE

Generato: **2026-08-14 07:37:55 CEST**  
UTC: **2026-08-14 05:37:55 UTC**

Fonte dati: **OKX Futures pubblici**.  
Questo report non è la vera heatmap CoinGlass. Serve a capire se il mercato futures è carico di long, short o leva.

## Traduzione in parole semplici

| Asset | Lettura | Forza | Cosa significa in pratica |
| --- | --- | --- | --- |
| BTC | Misto | 1/5 | Qui pesa di più il report frattale. |
| SOL | Rischio sotto | 3/5 | Per un long a leva: prudenza alta. Guarda bene liquidazione e drawdown del report frattale. |
| DOGE | Misto | 1/5 | Qui pesa di più il report frattale. |

## Numeri principali

| Asset | Prezzo | Prezzo 24h | Funding | Open Interest | OI 24h | Long/Short |
| --- | --- | --- | --- | --- | --- | --- |
| BTC | 63.250 $ | -0.88% | +0.0079% | $2.07B | -2.77% | 1.24 |
| SOL | 75,80 $ | -0.56% | +0.0100% | $222.20M | +2.66% | 2.34 |
| DOGE | 0.06994 $ | -0.48% | +0.0071% | $81.81M | -14.90% | 3.23 |

## Spiegazione rapida dei termini

- **Funding positivo**: i long pagano gli short. Se è troppo positivo, tanti stanno scommettendo al rialzo.
- **Funding negativo**: gli short pagano i long. Se è troppo negativo, tanti stanno scommettendo al ribasso.
- **Open Interest / OI**: quanta leva è aperta sul mercato. Se sale, entra più leva. Se scende, la leva sta uscendo.
- **Long/Short sopra 1**: più mercato orientato long.
- **Long/Short sotto 1**: più mercato orientato short.
- **Flush sotto**: discesa rapida per pulire i long.
- **Short squeeze sopra**: salita rapida per liquidare gli short.

---

## Bitcoin — BTC

### Lettura semplice

**NEUTRALE / POCO CHIARO**  
**Forza segnale: 1/5**

BTC: i futures non danno una lettura chiara. Non si vede uno sbilanciamento forte né long né short.

**Tradotto operativamente:** Qui pesa di più il report frattale.

### Perché

- funding positivo: i long pagano gli short
- open interest in calo: leva in uscita
- long/short ratio abbastanza equilibrato

### Numeri controllati

| Dato | Valore | Traduzione |
| --- | --- | --- |
| Prezzo | $63,331 | prezzo futures/mark usato come riferimento |
| Prezzo 24h | -0.88% | movimento dell'ultimo giorno |
| Funding | +0.0079% | positivo = long pagano; negativo = short pagano |
| Prossimo funding | 2026-08-14 10:00 | prossimo aggiornamento funding |
| Open Interest stimato | $2.07B | leva aperta stimata in dollari |
| Open Interest 24h | -2.77% | leva entrata o uscita nelle ultime 24h |
| Long/Short ratio | 1.24 | sopra 1 = più long; sotto 1 = più short |

### Livelli teorici di liquidazione

Questi NON sono la vera heatmap. Sono solo una stima semplice: se una posizione fosse aperta vicino al prezzo attuale, più o meno dove rischierebbe la liquidazione.

| Leva | Long liquidato circa sotto | Short liquidato circa sopra |
| --- | --- | --- |
| 5x | $50,664 | $75,997 |
| 10x | $56,998 | $69,664 |
| 20x | $60,164 | $66,497 |
| 50x | $62,064 | $64,597 |

---

## Solana — SOL

### Lettura semplice

**RISCHIO DISCESA / FLUSH SOTTO**  
**Forza segnale: 3/5**

SOL: i futures sembrano più vulnerabili verso una discesa improvvisa. Non significa che deve scendere, ma se rompe sotto può accelerare.

**Tradotto operativamente:** Per un long a leva: prudenza alta. Guarda bene liquidazione e drawdown del report frattale.

### Perché

- funding positivo: i long pagano gli short
- open interest in aumento: più leva nel sistema
- long/short ratio alto: mercato più long

### Numeri controllati

| Dato | Valore | Traduzione |
| --- | --- | --- |
| Prezzo | $75.90 | prezzo futures/mark usato come riferimento |
| Prezzo 24h | -0.56% | movimento dell'ultimo giorno |
| Funding | +0.0100% | positivo = long pagano; negativo = short pagano |
| Prossimo funding | 2026-08-14 10:00 | prossimo aggiornamento funding |
| Open Interest stimato | $222.20M | leva aperta stimata in dollari |
| Open Interest 24h | +2.66% | leva entrata o uscita nelle ultime 24h |
| Long/Short ratio | 2.34 | sopra 1 = più long; sotto 1 = più short |

### Livelli teorici di liquidazione

Questi NON sono la vera heatmap. Sono solo una stima semplice: se una posizione fosse aperta vicino al prezzo attuale, più o meno dove rischierebbe la liquidazione.

| Leva | Long liquidato circa sotto | Short liquidato circa sopra |
| --- | --- | --- |
| 5x | $60.72 | $91.08 |
| 10x | $68.31 | $83.49 |
| 20x | $72.11 | $79.70 |
| 50x | $74.38 | $77.42 |

### Note tecniche usate dallo score

- funding positivo: mercato leggermente carico di long
- open interest in aumento: leva in crescita
- long/short ratio alto: più mercato sbilanciato long

---

## Dogecoin — DOGE

### Lettura semplice

**NEUTRALE / POCO CHIARO**  
**Forza segnale: 1/5**

DOGE: i futures non danno una lettura chiara. Non si vede uno sbilanciamento forte né long né short.

**Tradotto operativamente:** Qui pesa di più il report frattale.

### Perché

- funding positivo: i long pagano gli short
- open interest in calo: leva in uscita
- long/short ratio alto: mercato più long

### Numeri controllati

| Dato | Valore | Traduzione |
| --- | --- | --- |
| Prezzo | $0.06996 | prezzo futures/mark usato come riferimento |
| Prezzo 24h | -0.48% | movimento dell'ultimo giorno |
| Funding | +0.0071% | positivo = long pagano; negativo = short pagano |
| Prossimo funding | 2026-08-14 10:00 | prossimo aggiornamento funding |
| Open Interest stimato | $81.81M | leva aperta stimata in dollari |
| Open Interest 24h | -14.90% | leva entrata o uscita nelle ultime 24h |
| Long/Short ratio | 3.23 | sopra 1 = più long; sotto 1 = più short |

### Livelli teorici di liquidazione

Questi NON sono la vera heatmap. Sono solo una stima semplice: se una posizione fosse aperta vicino al prezzo attuale, più o meno dove rischierebbe la liquidazione.

| Leva | Long liquidato circa sotto | Short liquidato circa sopra |
| --- | --- | --- |
| 5x | $0.05597 | $0.08395 |
| 10x | $0.06296 | $0.07696 |
| 20x | $0.06646 | $0.07346 |
| 50x | $0.06856 | $0.07136 |

### Note tecniche usate dallo score

- open interest in forte calo: parte della leva è già uscita
- long/short ratio alto: più mercato sbilanciato long

---
