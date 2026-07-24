# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T03:53:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **33**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-17.33 R**
- Profitto virtuale mancato: **50.71 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 103 | 0 | 13291.08 |
| DOWN_20 | 103 | 0 | 26582.16 |
| DOWN_30 | 103 | 3 | 39925.32 |
| DOWN_40 | 103 | 24 | 50424.91 |
| UP_10 | 60 | 0 | 16846.53 |
| UP_20 | 60 | 0 | 33693.07 |
| UP_30 | 60 | 0 | 50539.60 |
| UP_40 | 60 | 35 | 59565.75 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
