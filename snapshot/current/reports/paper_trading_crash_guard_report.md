# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T13:09:49+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **12**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **141.06 R**
- Profitto virtuale mancato: **392.57 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 162 | 0 | 27415.82 |
| DOWN_20 | 162 | 0 | 54831.63 |
| DOWN_30 | 162 | 0 | 82247.45 |
| DOWN_40 | 162 | 53 | 103148.28 |
| UP_10 | 94 | 0 | 18677.83 |
| UP_20 | 94 | 0 | 37355.66 |
| UP_30 | 94 | 0 | 56033.49 |
| UP_40 | 94 | 16 | 71332.04 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
