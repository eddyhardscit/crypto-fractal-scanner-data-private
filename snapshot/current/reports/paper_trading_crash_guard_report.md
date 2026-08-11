# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T00:09:07+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **23**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **221.54 R**
- Profitto virtuale mancato: **312.09 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 95 | 0 | 17921.44 |
| DOWN_20 | 95 | 0 | 35842.88 |
| DOWN_30 | 95 | 0 | 53764.32 |
| DOWN_40 | 95 | 28 | 66867.95 |
| UP_10 | 43 | 0 | 13753.00 |
| UP_20 | 43 | 0 | 27506.01 |
| UP_30 | 43 | 0 | 41259.01 |
| UP_40 | 43 | 11 | 52755.83 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
