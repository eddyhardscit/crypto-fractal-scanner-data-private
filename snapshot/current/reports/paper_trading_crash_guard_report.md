# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T06:07:20+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **22**
- Simulazioni bloccate attive: **101**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **503.27 R**
- Profitto virtuale mancato: **522.27 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 200 | 0 | 19621.59 |
| DOWN_20 | 200 | 0 | 39243.18 |
| DOWN_30 | 200 | 9 | 58988.11 |
| DOWN_40 | 200 | 54 | 76541.29 |
| UP_10 | 164 | 0 | 32540.89 |
| UP_20 | 164 | 0 | 65081.77 |
| UP_30 | 164 | 1 | 97623.50 |
| UP_40 | 164 | 69 | 118951.29 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
