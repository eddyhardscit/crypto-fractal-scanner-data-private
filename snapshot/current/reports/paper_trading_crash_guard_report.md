# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T19:24:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **195**
- Simulazioni completate nel ciclo: **24**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **156.51 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 105 | 4 | 11788.03 |
| DOWN_20 | 105 | 6 | 23456.05 |
| DOWN_30 | 105 | 6 | 34895.58 |
| DOWN_40 | 105 | 26 | 44251.79 |
| UP_10 | 171 | 0 | 44489.50 |
| UP_20 | 171 | 0 | 88979.01 |
| UP_30 | 171 | 4 | 133525.29 |
| UP_40 | 171 | 92 | 159529.45 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
