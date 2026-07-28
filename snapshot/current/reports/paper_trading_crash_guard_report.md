# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T16:38:39+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **70**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **143.26 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 63 | 0 | 12264.24 |
| DOWN_20 | 63 | 0 | 24528.48 |
| DOWN_30 | 63 | 0 | 36792.72 |
| DOWN_40 | 63 | 23 | 43884.61 |
| UP_10 | 138 | 0 | 14264.19 |
| UP_20 | 138 | 0 | 28528.39 |
| UP_30 | 138 | 0 | 42792.58 |
| UP_40 | 138 | 48 | 54121.29 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
