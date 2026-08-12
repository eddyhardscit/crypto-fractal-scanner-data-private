# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T21:39:48+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **12**
- Simulazioni bloccate attive: **74**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **388.81 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 123 | 0 | 16806.28 |
| DOWN_20 | 123 | 0 | 33612.57 |
| DOWN_30 | 123 | 0 | 50418.85 |
| DOWN_40 | 123 | 41 | 64894.70 |
| UP_10 | 81 | 0 | 23429.93 |
| UP_20 | 81 | 1 | 46918.17 |
| UP_30 | 81 | 3 | 70333.10 |
| UP_40 | 81 | 42 | 84825.12 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
