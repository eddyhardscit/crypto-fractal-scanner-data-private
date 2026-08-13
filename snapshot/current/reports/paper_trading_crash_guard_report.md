# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-13T09:08:49+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **67**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **435.83 R**
- Profitto virtuale mancato: **504.86 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 168 | 0 | 28806.21 |
| DOWN_20 | 168 | 0 | 57612.43 |
| DOWN_30 | 168 | 0 | 86418.64 |
| DOWN_40 | 168 | 54 | 111016.92 |
| UP_10 | 139 | 0 | 31691.35 |
| UP_20 | 139 | 0 | 63382.71 |
| UP_30 | 139 | 1 | 95087.65 |
| UP_40 | 139 | 55 | 115737.27 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
