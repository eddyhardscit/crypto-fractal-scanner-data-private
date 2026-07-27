# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T15:23:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **165.03 R**
- Profitto virtuale mancato: **259.49 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 188 | 2 | 16329.88 |
| DOWN_20 | 188 | 3 | 32599.76 |
| DOWN_30 | 188 | 18 | 48987.93 |
| DOWN_40 | 188 | 55 | 62720.25 |
| UP_10 | 135 | 0 | 22723.29 |
| UP_20 | 135 | 0 | 45446.57 |
| UP_30 | 135 | 0 | 68169.86 |
| UP_40 | 135 | 68 | 82014.67 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
