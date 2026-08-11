# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T07:09:43+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **14**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **180.95 R**
- Profitto virtuale mancato: **352.68 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 152 | 0 | 26455.52 |
| DOWN_20 | 152 | 0 | 52911.03 |
| DOWN_30 | 152 | 0 | 79366.55 |
| DOWN_40 | 152 | 51 | 99612.86 |
| UP_10 | 87 | 0 | 20859.41 |
| UP_20 | 87 | 0 | 41718.83 |
| UP_30 | 87 | 0 | 62578.24 |
| UP_40 | 87 | 17 | 79356.80 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
