# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T21:23:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **14**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **163.54 R**
- Profitto virtuale mancato: **260.98 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 169 | 0 | 14292.14 |
| DOWN_20 | 169 | 0 | 28584.27 |
| DOWN_30 | 169 | 0 | 42876.41 |
| DOWN_40 | 169 | 43 | 55166.92 |
| UP_10 | 184 | 0 | 26915.32 |
| UP_20 | 184 | 0 | 53830.64 |
| UP_30 | 184 | 0 | 80745.96 |
| UP_40 | 184 | 94 | 96716.56 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
