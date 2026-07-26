# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T06:38:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **71**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **23.59 R**
- Profitto virtuale mancato: **150.37 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 317 | 0 | 25833.40 |
| DOWN_20 | 317 | 0 | 51666.79 |
| DOWN_30 | 317 | 0 | 77500.19 |
| DOWN_40 | 317 | 132 | 95819.96 |
| UP_10 | 76 | 0 | 12637.90 |
| UP_20 | 76 | 0 | 25275.79 |
| UP_30 | 76 | 0 | 37913.69 |
| UP_40 | 76 | 30 | 45235.96 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
