# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T13:39:06+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **91**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **349.42 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 179 | 0 | 35391.91 |
| DOWN_20 | 179 | 0 | 70783.82 |
| DOWN_30 | 179 | 9 | 106299.52 |
| DOWN_40 | 179 | 57 | 134721.53 |
| UP_10 | 77 | 4 | 21309.27 |
| UP_20 | 77 | 6 | 42498.54 |
| UP_30 | 77 | 6 | 63402.35 |
| UP_40 | 77 | 36 | 76758.03 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
