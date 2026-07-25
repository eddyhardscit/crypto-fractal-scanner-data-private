# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T11:23:42+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **17**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-86.30 R**
- Profitto virtuale mancato: **142.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 177 | 0 | 15111.70 |
| DOWN_20 | 177 | 0 | 30223.39 |
| DOWN_30 | 177 | 0 | 45335.09 |
| DOWN_40 | 177 | 55 | 57608.19 |
| UP_10 | 102 | 0 | 28968.98 |
| UP_20 | 102 | 0 | 57937.95 |
| UP_30 | 102 | 0 | 86906.93 |
| UP_40 | 102 | 51 | 103972.35 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
