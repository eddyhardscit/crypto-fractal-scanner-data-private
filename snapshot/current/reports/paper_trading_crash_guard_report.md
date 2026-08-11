# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T23:24:07+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **114**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **271.65 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 131 | 0 | 23181.00 |
| DOWN_20 | 131 | 0 | 46361.99 |
| DOWN_30 | 131 | 3 | 69583.09 |
| DOWN_40 | 131 | 28 | 89275.03 |
| UP_10 | 145 | 0 | 27858.48 |
| UP_20 | 145 | 0 | 55716.97 |
| UP_30 | 145 | 0 | 83575.45 |
| UP_40 | 145 | 79 | 100681.01 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
