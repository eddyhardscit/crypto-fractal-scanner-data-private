# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-13T19:39:48+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **67**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **435.83 R**
- Profitto virtuale mancato: **504.86 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 184 | 0 | 29903.94 |
| DOWN_20 | 184 | 0 | 59807.88 |
| DOWN_30 | 184 | 0 | 89711.82 |
| DOWN_40 | 184 | 60 | 114794.33 |
| UP_10 | 152 | 0 | 32814.23 |
| UP_20 | 152 | 0 | 65628.47 |
| UP_30 | 152 | 0 | 98442.70 |
| UP_40 | 152 | 55 | 119710.37 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
