# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-21T07:38:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **5.05 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 126 | 0 | 36254.80 |
| DOWN_20 | 126 | 0 | 72509.60 |
| DOWN_30 | 126 | 0 | 108764.39 |
| DOWN_40 | 126 | 54 | 132392.97 |
| UP_10 | 30 | 0 | 2323.16 |
| UP_20 | 30 | 0 | 4646.32 |
| UP_30 | 30 | 0 | 6969.48 |
| UP_40 | 30 | 12 | 8739.51 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
