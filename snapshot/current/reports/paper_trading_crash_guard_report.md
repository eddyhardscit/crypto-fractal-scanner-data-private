# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-20T13:23:30+00:00

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
| DOWN_10 | 36 | 0 | 5788.22 |
| DOWN_20 | 36 | 0 | 11576.44 |
| DOWN_30 | 36 | 3 | 17406.78 |
| DOWN_40 | 36 | 15 | 20920.23 |
| UP_10 | 27 | 0 | 3127.98 |
| UP_20 | 27 | 0 | 6255.95 |
| UP_30 | 27 | 1 | 9415.26 |
| UP_40 | 27 | 9 | 11664.35 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
