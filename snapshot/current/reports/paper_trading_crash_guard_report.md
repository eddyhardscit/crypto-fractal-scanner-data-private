# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T10:38:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **3**
- Simulazioni bloccate attive: **29**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **137.20 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 85 | 0 | 8888.12 |
| DOWN_20 | 85 | 0 | 17776.25 |
| DOWN_30 | 85 | 0 | 26664.37 |
| DOWN_40 | 85 | 19 | 34032.14 |
| UP_10 | 267 | 0 | 32967.16 |
| UP_20 | 267 | 0 | 65934.33 |
| UP_30 | 267 | 5 | 98972.95 |
| UP_40 | 267 | 140 | 117795.15 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
