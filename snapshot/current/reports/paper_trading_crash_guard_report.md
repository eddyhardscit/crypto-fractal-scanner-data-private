# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T15:53:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **103**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **25.61 R**
- Profitto virtuale mancato: **150.37 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 244 | 0 | 24003.86 |
| DOWN_20 | 244 | 0 | 48007.71 |
| DOWN_30 | 244 | 0 | 72011.57 |
| DOWN_40 | 244 | 109 | 88734.07 |
| UP_10 | 97 | 0 | 12754.33 |
| UP_20 | 97 | 0 | 25508.66 |
| UP_30 | 97 | 0 | 38262.99 |
| UP_40 | 97 | 50 | 45552.85 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
