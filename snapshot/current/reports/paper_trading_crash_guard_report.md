# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T04:10:31+00:00

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
| DOWN_10 | 139 | 0 | 24055.68 |
| DOWN_20 | 139 | 0 | 48111.36 |
| DOWN_30 | 139 | 0 | 72167.04 |
| DOWN_40 | 139 | 44 | 90686.42 |
| UP_10 | 85 | 0 | 20889.67 |
| UP_20 | 85 | 0 | 41779.34 |
| UP_30 | 85 | 0 | 62669.01 |
| UP_40 | 85 | 29 | 79404.73 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
