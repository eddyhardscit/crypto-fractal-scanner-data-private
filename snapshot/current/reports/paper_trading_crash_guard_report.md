# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-21T11:38:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **6.06 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 132 | 0 | 37440.98 |
| DOWN_20 | 132 | 0 | 74881.96 |
| DOWN_30 | 132 | 0 | 112322.94 |
| DOWN_40 | 132 | 53 | 137212.23 |
| UP_10 | 38 | 2 | 3069.22 |
| UP_20 | 38 | 3 | 6078.44 |
| UP_30 | 38 | 3 | 8838.11 |
| UP_40 | 38 | 19 | 10860.90 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
