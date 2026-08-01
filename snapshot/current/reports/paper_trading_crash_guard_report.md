# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-01T12:08:47+00:00

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
| DOWN_10 | 10 | 0 | 659.23 |
| DOWN_20 | 10 | 0 | 1318.45 |
| DOWN_30 | 10 | 0 | 1977.68 |
| DOWN_40 | 10 | 4 | 2553.81 |
| UP_10 | 31 | 0 | 1266.84 |
| UP_20 | 31 | 0 | 2533.68 |
| UP_30 | 31 | 0 | 3800.51 |
| UP_40 | 31 | 6 | 4615.78 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
