# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-23T01:23:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **7**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **14.14 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 118 | 0 | 18646.02 |
| DOWN_20 | 118 | 0 | 37292.03 |
| DOWN_30 | 118 | 1 | 55955.23 |
| DOWN_40 | 118 | 28 | 70041.99 |
| UP_10 | 35 | 0 | 5779.07 |
| UP_20 | 35 | 0 | 11558.14 |
| UP_30 | 35 | 0 | 17337.21 |
| UP_40 | 35 | 9 | 22227.64 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
