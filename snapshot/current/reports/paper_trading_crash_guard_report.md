# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T15:23:44+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **40**
- Simulazioni bloccate attive: **63**
- Simulazioni completate nel ciclo: **1**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-85.29 R**
- Profitto virtuale mancato: **142.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 154 | 0 | 16243.50 |
| DOWN_20 | 154 | 0 | 32486.99 |
| DOWN_30 | 154 | 0 | 48730.49 |
| DOWN_40 | 154 | 39 | 62553.49 |
| UP_10 | 130 | 0 | 29921.87 |
| UP_20 | 130 | 0 | 59843.75 |
| UP_30 | 130 | 0 | 89765.62 |
| UP_40 | 130 | 68 | 107565.06 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
