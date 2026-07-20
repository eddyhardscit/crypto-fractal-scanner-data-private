# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-20T07:08:29+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **3.03 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 32 | 0 | 4575.37 |
| DOWN_20 | 32 | 0 | 9150.74 |
| DOWN_30 | 32 | 1 | 13755.50 |
| DOWN_40 | 32 | 10 | 17289.98 |
| UP_10 | 38 | 0 | 8151.24 |
| UP_20 | 38 | 0 | 16302.49 |
| UP_30 | 38 | 0 | 24453.73 |
| UP_40 | 38 | 20 | 29467.66 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
