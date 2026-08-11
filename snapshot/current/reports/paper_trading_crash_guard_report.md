# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T22:24:31+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **114**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **271.65 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 134 | 0 | 24308.44 |
| DOWN_20 | 134 | 0 | 48616.87 |
| DOWN_30 | 134 | 3 | 72965.41 |
| DOWN_40 | 134 | 32 | 93006.26 |
| UP_10 | 142 | 0 | 30334.25 |
| UP_20 | 142 | 0 | 60668.49 |
| UP_30 | 142 | 0 | 91002.74 |
| UP_40 | 142 | 73 | 109854.84 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
