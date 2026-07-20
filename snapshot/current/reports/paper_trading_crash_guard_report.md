# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-20T17:23:31+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **3.03 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 47 | 0 | 10038.60 |
| DOWN_20 | 47 | 0 | 20077.20 |
| DOWN_30 | 47 | 0 | 30115.80 |
| DOWN_40 | 47 | 21 | 36401.52 |
| UP_10 | 24 | 0 | 1926.09 |
| UP_20 | 24 | 0 | 3852.19 |
| UP_30 | 24 | 0 | 5778.28 |
| UP_40 | 24 | 10 | 7130.52 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
