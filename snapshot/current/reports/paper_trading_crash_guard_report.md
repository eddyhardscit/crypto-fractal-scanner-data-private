# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T17:53:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **94**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **12.22 R**
- Profitto virtuale mancato: **163.76 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 241 | 0 | 20815.56 |
| DOWN_20 | 241 | 0 | 41631.13 |
| DOWN_30 | 241 | 0 | 62446.69 |
| DOWN_40 | 241 | 93 | 78326.23 |
| UP_10 | 94 | 0 | 12280.52 |
| UP_20 | 94 | 0 | 24561.04 |
| UP_30 | 94 | 0 | 36841.56 |
| UP_40 | 94 | 44 | 43945.91 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
