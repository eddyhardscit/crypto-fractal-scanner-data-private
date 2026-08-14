# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T08:06:10+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **35**
- Simulazioni bloccate attive: **113**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **545.69 R**
- Profitto virtuale mancato: **522.27 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 201 | 0 | 18853.40 |
| DOWN_20 | 201 | 0 | 37706.80 |
| DOWN_30 | 201 | 0 | 56560.20 |
| DOWN_40 | 201 | 63 | 72609.53 |
| UP_10 | 150 | 0 | 32068.39 |
| UP_20 | 150 | 0 | 64136.78 |
| UP_30 | 150 | 0 | 96205.17 |
| UP_40 | 150 | 60 | 117235.87 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
