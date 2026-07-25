# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T20:38:43+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **69**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-41.14 R**
- Profitto virtuale mancato: **144.40 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 256 | 0 | 21903.93 |
| DOWN_20 | 256 | 0 | 43807.86 |
| DOWN_30 | 256 | 1 | 65713.03 |
| DOWN_40 | 256 | 94 | 82359.52 |
| UP_10 | 98 | 4 | 18985.24 |
| UP_20 | 98 | 6 | 37850.48 |
| UP_30 | 98 | 17 | 56460.71 |
| UP_40 | 98 | 57 | 67391.87 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
