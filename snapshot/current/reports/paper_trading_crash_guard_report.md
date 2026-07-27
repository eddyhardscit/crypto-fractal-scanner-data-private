# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T19:23:38+00:00

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
| DOWN_10 | 170 | 0 | 14608.64 |
| DOWN_20 | 170 | 0 | 29217.29 |
| DOWN_30 | 170 | 15 | 44026.11 |
| DOWN_40 | 170 | 49 | 56432.95 |
| UP_10 | 180 | 0 | 27501.67 |
| UP_20 | 180 | 0 | 55003.33 |
| UP_30 | 180 | 0 | 82505.00 |
| UP_40 | 180 | 93 | 98898.31 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
