# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T23:50:12+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **77**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **373.00 R**
- Profitto virtuale mancato: **460.60 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 133 | 2 | 18227.00 |
| DOWN_20 | 133 | 3 | 36394.00 |
| DOWN_30 | 133 | 3 | 54455.41 |
| DOWN_40 | 133 | 36 | 69911.19 |
| UP_10 | 102 | 0 | 29343.41 |
| UP_20 | 102 | 0 | 58686.81 |
| UP_30 | 102 | 0 | 88030.22 |
| UP_40 | 102 | 58 | 104766.52 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
