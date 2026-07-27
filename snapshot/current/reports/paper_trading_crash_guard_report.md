# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T14:23:39+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **165.03 R**
- Profitto virtuale mancato: **259.49 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 245 | 0 | 28666.21 |
| DOWN_20 | 245 | 0 | 57332.43 |
| DOWN_30 | 245 | 13 | 86170.32 |
| DOWN_40 | 245 | 86 | 107012.49 |
| UP_10 | 92 | 0 | 11445.80 |
| UP_20 | 92 | 0 | 22891.61 |
| UP_30 | 92 | 0 | 34337.41 |
| UP_40 | 92 | 49 | 41060.81 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
