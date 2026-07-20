# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-20T03:08:29+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **3**
- Simulazioni bloccate attive: **3**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **0.00 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 33 | 0 | 5715.54 |
| DOWN_20 | 33 | 0 | 11431.09 |
| DOWN_30 | 33 | 0 | 17146.63 |
| DOWN_40 | 33 | 8 | 21564.63 |
| UP_10 | 29 | 0 | 6075.11 |
| UP_20 | 29 | 0 | 12150.23 |
| UP_30 | 29 | 0 | 18225.34 |
| UP_40 | 29 | 13 | 22515.42 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
