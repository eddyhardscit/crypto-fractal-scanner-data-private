# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T18:53:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **30**
- Simulazioni completate nel ciclo: **1**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **191.76 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 103 | 0 | 13023.22 |
| DOWN_20 | 103 | 0 | 26046.44 |
| DOWN_30 | 103 | 23 | 39380.02 |
| DOWN_40 | 103 | 45 | 46553.39 |
| UP_10 | 136 | 0 | 13557.18 |
| UP_20 | 136 | 0 | 27114.36 |
| UP_30 | 136 | 0 | 40671.53 |
| UP_40 | 136 | 48 | 51178.29 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
