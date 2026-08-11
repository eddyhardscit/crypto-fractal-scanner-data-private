# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T09:09:39+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **23**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **160.85 R**
- Profitto virtuale mancato: **372.78 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 154 | 0 | 26568.25 |
| DOWN_20 | 154 | 0 | 53136.50 |
| DOWN_30 | 154 | 0 | 79704.75 |
| DOWN_40 | 154 | 52 | 100036.27 |
| UP_10 | 93 | 0 | 21946.23 |
| UP_20 | 93 | 0 | 43892.46 |
| UP_30 | 93 | 0 | 65838.70 |
| UP_40 | 93 | 21 | 82985.55 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
