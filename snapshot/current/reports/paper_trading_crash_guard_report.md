# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T21:24:08+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **10**
- Simulazioni bloccate attive: **160**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **225.19 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 119 | 0 | 19692.75 |
| DOWN_20 | 119 | 0 | 39385.50 |
| DOWN_30 | 119 | 0 | 59078.25 |
| DOWN_40 | 119 | 25 | 76056.19 |
| UP_10 | 148 | 0 | 39031.09 |
| UP_20 | 148 | 0 | 78062.18 |
| UP_30 | 148 | 0 | 117093.27 |
| UP_40 | 148 | 70 | 141396.43 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
