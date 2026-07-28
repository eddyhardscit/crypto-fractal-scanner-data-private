# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T06:39:04+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **41**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **163.54 R**
- Profitto virtuale mancato: **260.98 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 103 | 0 | 9674.88 |
| DOWN_20 | 103 | 0 | 19349.75 |
| DOWN_30 | 103 | 0 | 29024.63 |
| DOWN_40 | 103 | 15 | 37179.33 |
| UP_10 | 248 | 0 | 33002.69 |
| UP_20 | 248 | 0 | 66005.39 |
| UP_30 | 248 | 0 | 99008.08 |
| UP_40 | 248 | 133 | 117111.30 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
