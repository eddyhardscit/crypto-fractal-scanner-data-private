# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-31T13:38:40+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **196.28 R**
- Profitto virtuale mancato: **312.09 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 34 | 0 | 2553.24 |
| DOWN_20 | 34 | 0 | 5106.48 |
| DOWN_30 | 34 | 0 | 7659.72 |
| DOWN_40 | 34 | 20 | 9613.79 |
| UP_10 | 48 | 0 | 2147.58 |
| UP_20 | 48 | 0 | 4295.16 |
| UP_30 | 48 | 0 | 6442.74 |
| UP_40 | 48 | 10 | 8082.68 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
