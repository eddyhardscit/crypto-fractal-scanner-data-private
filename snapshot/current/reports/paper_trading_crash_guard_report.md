# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T09:06:05+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **113**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **545.69 R**
- Profitto virtuale mancato: **522.27 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 206 | 0 | 19056.55 |
| DOWN_20 | 206 | 0 | 38113.11 |
| DOWN_30 | 206 | 0 | 57169.66 |
| DOWN_40 | 206 | 63 | 73422.14 |
| UP_10 | 152 | 0 | 32076.93 |
| UP_20 | 152 | 0 | 64153.85 |
| UP_30 | 152 | 0 | 96230.78 |
| UP_40 | 152 | 62 | 117264.32 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
