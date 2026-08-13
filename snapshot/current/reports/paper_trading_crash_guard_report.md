# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-13T00:54:17+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **77**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **373.00 R**
- Profitto virtuale mancato: **460.60 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 179 | 2 | 22179.89 |
| DOWN_20 | 179 | 9 | 44735.90 |
| DOWN_30 | 179 | 10 | 66423.12 |
| DOWN_40 | 179 | 88 | 86571.60 |
| UP_10 | 139 | 0 | 35584.20 |
| UP_20 | 139 | 0 | 71168.41 |
| UP_30 | 139 | 0 | 106752.61 |
| UP_40 | 139 | 63 | 128420.73 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
