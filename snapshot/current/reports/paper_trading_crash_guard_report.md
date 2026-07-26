# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T08:38:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **73**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **23.59 R**
- Profitto virtuale mancato: **150.37 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 280 | 0 | 25039.74 |
| DOWN_20 | 280 | 0 | 50079.49 |
| DOWN_30 | 280 | 8 | 75217.83 |
| DOWN_40 | 280 | 128 | 93569.76 |
| UP_10 | 79 | 0 | 12581.67 |
| UP_20 | 79 | 0 | 25163.34 |
| UP_30 | 79 | 0 | 37745.01 |
| UP_40 | 79 | 39 | 44853.73 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
