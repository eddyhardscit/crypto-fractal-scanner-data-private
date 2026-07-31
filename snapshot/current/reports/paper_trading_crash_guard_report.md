# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-31T14:38:47+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **196.28 R**
- Profitto virtuale mancato: **312.09 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 31 | 0 | 2538.75 |
| DOWN_20 | 31 | 0 | 5077.51 |
| DOWN_30 | 31 | 0 | 7616.26 |
| DOWN_40 | 31 | 20 | 9555.85 |
| UP_10 | 42 | 0 | 1902.55 |
| UP_20 | 42 | 0 | 3805.10 |
| UP_30 | 42 | 0 | 5707.65 |
| UP_40 | 42 | 9 | 7130.04 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
