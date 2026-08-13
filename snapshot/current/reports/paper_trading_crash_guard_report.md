# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-13T20:06:51+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **42**
- Simulazioni bloccate attive: **109**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **435.83 R**
- Profitto virtuale mancato: **504.86 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 192 | 0 | 30364.99 |
| DOWN_20 | 192 | 0 | 60729.97 |
| DOWN_30 | 192 | 0 | 91094.96 |
| DOWN_40 | 192 | 60 | 116481.92 |
| UP_10 | 156 | 0 | 32762.09 |
| UP_20 | 156 | 0 | 65524.19 |
| UP_30 | 156 | 0 | 98286.28 |
| UP_40 | 156 | 66 | 119548.22 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
