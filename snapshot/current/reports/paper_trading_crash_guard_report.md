# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T10:39:20+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **78**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **349.42 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 154 | 0 | 29050.19 |
| DOWN_20 | 154 | 0 | 58100.38 |
| DOWN_30 | 154 | 0 | 87150.57 |
| DOWN_40 | 154 | 44 | 109198.94 |
| UP_10 | 88 | 0 | 26206.95 |
| UP_20 | 88 | 0 | 52413.90 |
| UP_30 | 88 | 0 | 78620.86 |
| UP_40 | 88 | 33 | 96317.77 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
