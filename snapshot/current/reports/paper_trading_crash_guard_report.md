# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T22:53:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **14**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **221.05 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 75 | 0 | 12009.93 |
| DOWN_20 | 75 | 0 | 24019.86 |
| DOWN_30 | 75 | 0 | 36029.79 |
| DOWN_40 | 75 | 40 | 42574.50 |
| UP_10 | 151 | 2 | 14961.55 |
| UP_20 | 151 | 3 | 29863.10 |
| UP_30 | 151 | 3 | 44532.94 |
| UP_40 | 151 | 59 | 55420.87 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
