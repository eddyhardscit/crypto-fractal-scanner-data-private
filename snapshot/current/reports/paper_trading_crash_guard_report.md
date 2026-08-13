# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-13T02:54:23+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **126**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **366.14 R**
- Profitto virtuale mancato: **504.86 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 139 | 2 | 22129.89 |
| DOWN_20 | 139 | 2 | 44199.77 |
| DOWN_30 | 139 | 3 | 66164.07 |
| DOWN_40 | 139 | 51 | 85300.04 |
| UP_10 | 149 | 0 | 36757.69 |
| UP_20 | 149 | 0 | 73515.38 |
| UP_30 | 149 | 0 | 110273.06 |
| UP_40 | 149 | 65 | 132699.71 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
