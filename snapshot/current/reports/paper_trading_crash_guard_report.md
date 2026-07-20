# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-20T20:23:32+00:00

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
| DOWN_10 | 48 | 0 | 10287.38 |
| DOWN_20 | 48 | 0 | 20574.77 |
| DOWN_30 | 48 | 0 | 30862.15 |
| DOWN_40 | 48 | 22 | 37202.99 |
| UP_10 | 23 | 0 | 1884.23 |
| UP_20 | 23 | 0 | 3768.45 |
| UP_30 | 23 | 0 | 5652.68 |
| UP_40 | 23 | 10 | 6963.05 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
