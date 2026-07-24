# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T02:53:35+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **35**
- Simulazioni completate nel ciclo: **3**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-14.35 R**
- Profitto virtuale mancato: **47.73 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 108 | 0 | 13490.14 |
| DOWN_20 | 108 | 0 | 26980.28 |
| DOWN_30 | 108 | 3 | 40514.20 |
| DOWN_40 | 108 | 25 | 51201.79 |
| UP_10 | 68 | 0 | 19327.36 |
| UP_20 | 68 | 0 | 38654.73 |
| UP_30 | 68 | 0 | 57982.09 |
| UP_40 | 68 | 40 | 67961.81 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
