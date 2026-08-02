# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-02T00:08:46+00:00

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
| DOWN_10 | 9 | 0 | 843.88 |
| DOWN_20 | 9 | 3 | 1687.76 |
| DOWN_30 | 9 | 3 | 1961.42 |
| DOWN_40 | 9 | 7 | 2152.00 |
| UP_10 | 22 | 0 | 1156.35 |
| UP_20 | 22 | 0 | 2312.71 |
| UP_30 | 22 | 0 | 3469.06 |
| UP_40 | 22 | 5 | 4177.75 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
