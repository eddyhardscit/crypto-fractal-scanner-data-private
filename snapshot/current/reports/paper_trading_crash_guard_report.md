# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T23:23:41+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **14**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **163.54 R**
- Profitto virtuale mancato: **260.98 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 132 | 0 | 13578.35 |
| DOWN_20 | 132 | 0 | 27156.71 |
| DOWN_30 | 132 | 5 | 40806.11 |
| DOWN_40 | 132 | 24 | 52758.37 |
| UP_10 | 224 | 0 | 34220.04 |
| UP_20 | 224 | 0 | 68440.08 |
| UP_30 | 224 | 0 | 102660.12 |
| UP_40 | 224 | 122 | 121032.44 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
