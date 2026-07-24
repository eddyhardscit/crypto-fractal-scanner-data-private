# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T22:08:36+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **37**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-21.28 R**
- Profitto virtuale mancato: **77.89 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 127 | 0 | 12206.99 |
| DOWN_20 | 127 | 0 | 24413.99 |
| DOWN_30 | 127 | 0 | 36620.98 |
| DOWN_40 | 127 | 46 | 46449.79 |
| UP_10 | 68 | 0 | 19013.57 |
| UP_20 | 68 | 0 | 38027.14 |
| UP_30 | 68 | 0 | 57040.71 |
| UP_40 | 68 | 42 | 66914.19 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
