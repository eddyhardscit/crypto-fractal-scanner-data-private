# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T12:38:43+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **23**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **143.26 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 98 | 0 | 9073.11 |
| DOWN_20 | 98 | 0 | 18146.21 |
| DOWN_30 | 98 | 14 | 27401.03 |
| DOWN_40 | 98 | 22 | 34687.08 |
| UP_10 | 285 | 0 | 35437.21 |
| UP_20 | 285 | 0 | 70874.42 |
| UP_30 | 285 | 0 | 106311.63 |
| UP_40 | 285 | 147 | 126148.49 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
