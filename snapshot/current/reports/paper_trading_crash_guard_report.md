# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-31T15:39:21+00:00

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
| DOWN_10 | 27 | 0 | 1714.10 |
| DOWN_20 | 27 | 0 | 3428.21 |
| DOWN_30 | 27 | 0 | 5142.31 |
| DOWN_40 | 27 | 20 | 6257.24 |
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
