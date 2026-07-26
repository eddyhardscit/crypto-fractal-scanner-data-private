# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T14:53:37+00:00

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
| DOWN_10 | 233 | 0 | 19654.25 |
| DOWN_20 | 233 | 0 | 39308.50 |
| DOWN_30 | 233 | 13 | 59177.45 |
| DOWN_40 | 233 | 93 | 74678.83 |
| UP_10 | 93 | 0 | 13212.87 |
| UP_20 | 93 | 0 | 26425.74 |
| UP_30 | 93 | 0 | 39638.60 |
| UP_40 | 93 | 50 | 47041.36 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
