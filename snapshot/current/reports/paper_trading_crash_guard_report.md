# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-21T00:38:31+00:00

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
| DOWN_10 | 75 | 0 | 16444.93 |
| DOWN_20 | 75 | 0 | 32889.86 |
| DOWN_30 | 75 | 3 | 49376.91 |
| DOWN_40 | 75 | 23 | 61833.19 |
| UP_10 | 30 | 0 | 4486.28 |
| UP_20 | 30 | 0 | 8972.56 |
| UP_30 | 30 | 0 | 13458.83 |
| UP_40 | 30 | 10 | 17225.30 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
