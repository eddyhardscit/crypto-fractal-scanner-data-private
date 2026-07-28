# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T11:38:39+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **29**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **137.20 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 86 | 0 | 8578.39 |
| DOWN_20 | 86 | 0 | 17156.79 |
| DOWN_30 | 86 | 0 | 25735.18 |
| DOWN_40 | 86 | 21 | 32735.59 |
| UP_10 | 272 | 0 | 32885.79 |
| UP_20 | 272 | 0 | 65771.57 |
| UP_30 | 272 | 5 | 98728.81 |
| UP_40 | 272 | 140 | 117558.48 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
