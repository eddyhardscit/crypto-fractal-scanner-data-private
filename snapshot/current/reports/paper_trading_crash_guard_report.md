# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T00:08:36+00:00

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
| DOWN_10 | 291 | 0 | 24723.28 |
| DOWN_20 | 291 | 0 | 49446.56 |
| DOWN_30 | 291 | 12 | 74312.61 |
| DOWN_40 | 291 | 148 | 90762.50 |
| UP_10 | 105 | 2 | 13984.75 |
| UP_20 | 105 | 3 | 27909.50 |
| UP_30 | 105 | 3 | 41665.63 |
| UP_40 | 105 | 49 | 50084.13 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
