# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T02:08:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **63**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **44.54 R**
- Profitto virtuale mancato: **163.76 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 289 | 0 | 28791.34 |
| DOWN_20 | 289 | 0 | 57582.67 |
| DOWN_30 | 289 | 7 | 86505.21 |
| DOWN_40 | 289 | 117 | 106983.68 |
| UP_10 | 104 | 2 | 13982.01 |
| UP_20 | 104 | 3 | 27904.02 |
| UP_30 | 104 | 7 | 41714.38 |
| UP_40 | 104 | 54 | 50075.00 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
