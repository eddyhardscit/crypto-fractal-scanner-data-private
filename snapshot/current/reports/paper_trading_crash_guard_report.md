# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T08:38:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **36**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **154.60 R**
- Profitto virtuale mancato: **269.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 65 | 0 | 8105.65 |
| DOWN_20 | 65 | 0 | 16211.29 |
| DOWN_30 | 65 | 4 | 24372.21 |
| DOWN_40 | 65 | 13 | 31041.40 |
| UP_10 | 266 | 0 | 33249.41 |
| UP_20 | 266 | 0 | 66498.82 |
| UP_30 | 266 | 0 | 99748.23 |
| UP_40 | 266 | 139 | 118925.98 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
