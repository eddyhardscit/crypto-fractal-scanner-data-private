# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T14:31:05+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **17**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-86.30 R**
- Profitto virtuale mancato: **142.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 188 | 0 | 17278.24 |
| DOWN_20 | 188 | 0 | 34556.49 |
| DOWN_30 | 188 | 0 | 51834.73 |
| DOWN_40 | 188 | 48 | 66227.34 |
| UP_10 | 108 | 0 | 29302.42 |
| UP_20 | 108 | 0 | 58604.84 |
| UP_30 | 108 | 0 | 87907.26 |
| UP_40 | 108 | 58 | 105249.77 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
