# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-23T13:38:34+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **16**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **14.15 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 131 | 0 | 15954.40 |
| DOWN_20 | 131 | 0 | 31908.81 |
| DOWN_30 | 131 | 0 | 47863.21 |
| DOWN_40 | 131 | 42 | 59964.03 |
| UP_10 | 51 | 0 | 12058.41 |
| UP_20 | 51 | 0 | 24116.82 |
| UP_30 | 51 | 0 | 36175.24 |
| UP_40 | 51 | 22 | 43677.32 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
