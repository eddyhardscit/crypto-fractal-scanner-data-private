# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T13:53:36+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **103**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **25.61 R**
- Profitto virtuale mancato: **150.37 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 268 | 0 | 22416.25 |
| DOWN_20 | 268 | 0 | 44832.50 |
| DOWN_30 | 268 | 0 | 67248.75 |
| DOWN_40 | 268 | 113 | 84697.89 |
| UP_10 | 85 | 0 | 12885.65 |
| UP_20 | 85 | 0 | 25771.31 |
| UP_30 | 85 | 0 | 38656.96 |
| UP_40 | 85 | 48 | 45787.21 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
