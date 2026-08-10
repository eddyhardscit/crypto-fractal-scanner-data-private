# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-10T23:09:42+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **23**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **221.54 R**
- Profitto virtuale mancato: **312.09 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 94 | 0 | 17530.98 |
| DOWN_20 | 94 | 0 | 35061.96 |
| DOWN_30 | 94 | 0 | 52592.94 |
| DOWN_40 | 94 | 28 | 65306.11 |
| UP_10 | 30 | 0 | 9076.86 |
| UP_20 | 30 | 0 | 18153.72 |
| UP_30 | 30 | 0 | 27230.58 |
| UP_40 | 30 | 8 | 34936.14 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
