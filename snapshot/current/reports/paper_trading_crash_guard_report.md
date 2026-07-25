# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T16:23:40+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **21**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-41.14 R**
- Profitto virtuale mancato: **144.40 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 157 | 0 | 16450.62 |
| DOWN_20 | 157 | 0 | 32901.23 |
| DOWN_30 | 157 | 0 | 49351.85 |
| DOWN_40 | 157 | 41 | 63320.16 |
| UP_10 | 119 | 0 | 26036.51 |
| UP_20 | 119 | 0 | 52073.01 |
| UP_30 | 119 | 1 | 78161.96 |
| UP_40 | 119 | 62 | 92985.96 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
