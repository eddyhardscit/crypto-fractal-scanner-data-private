# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T06:08:39+00:00

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
| DOWN_10 | 335 | 2 | 37223.84 |
| DOWN_20 | 335 | 3 | 74387.68 |
| DOWN_30 | 335 | 3 | 111529.95 |
| DOWN_40 | 335 | 159 | 135943.89 |
| UP_10 | 97 | 0 | 13249.40 |
| UP_20 | 97 | 0 | 26498.80 |
| UP_30 | 97 | 0 | 39748.20 |
| UP_40 | 97 | 46 | 47718.99 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
