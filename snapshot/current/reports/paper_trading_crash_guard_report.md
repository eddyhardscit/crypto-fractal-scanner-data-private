# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-13T03:54:07+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **71**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **421.69 R**
- Profitto virtuale mancato: **504.86 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 137 | 0 | 22069.89 |
| DOWN_20 | 137 | 0 | 44139.77 |
| DOWN_30 | 137 | 1 | 66104.07 |
| DOWN_40 | 137 | 47 | 85240.04 |
| UP_10 | 141 | 0 | 33373.18 |
| UP_20 | 141 | 0 | 66746.35 |
| UP_30 | 141 | 0 | 100119.53 |
| UP_40 | 141 | 59 | 121370.33 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
