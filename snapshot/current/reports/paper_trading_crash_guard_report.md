# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T06:09:59+00:00

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
| DOWN_10 | 147 | 0 | 26224.01 |
| DOWN_20 | 147 | 0 | 52448.03 |
| DOWN_30 | 147 | 0 | 78672.04 |
| DOWN_40 | 147 | 47 | 98839.45 |
| UP_10 | 87 | 0 | 20859.41 |
| UP_20 | 87 | 0 | 41718.83 |
| UP_30 | 87 | 0 | 62578.24 |
| UP_40 | 87 | 29 | 79356.80 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
