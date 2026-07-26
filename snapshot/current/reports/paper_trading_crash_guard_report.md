# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T09:38:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **71**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **25.61 R**
- Profitto virtuale mancato: **150.37 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 286 | 0 | 25222.47 |
| DOWN_20 | 286 | 0 | 50444.93 |
| DOWN_30 | 286 | 25 | 76528.93 |
| DOWN_40 | 286 | 129 | 94238.85 |
| UP_10 | 81 | 0 | 12676.66 |
| UP_20 | 81 | 0 | 25353.31 |
| UP_30 | 81 | 3 | 38081.38 |
| UP_40 | 81 | 41 | 45170.35 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
