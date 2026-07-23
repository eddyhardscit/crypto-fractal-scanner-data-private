# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-23T16:38:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **8**
- Simulazioni completate nel ciclo: **8**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **2.23 R**
- Profitto virtuale mancato: **11.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 117 | 2 | 14877.25 |
| DOWN_20 | 117 | 3 | 29694.50 |
| DOWN_30 | 117 | 3 | 44339.27 |
| DOWN_40 | 117 | 32 | 55751.75 |
| UP_10 | 53 | 0 | 13933.67 |
| UP_20 | 53 | 0 | 27867.33 |
| UP_30 | 53 | 0 | 41801.00 |
| UP_40 | 53 | 25 | 49883.61 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
