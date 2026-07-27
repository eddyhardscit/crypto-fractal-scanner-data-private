# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T18:23:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **2**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **165.03 R**
- Profitto virtuale mancato: **259.49 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 182 | 0 | 15713.11 |
| DOWN_20 | 182 | 0 | 31426.21 |
| DOWN_30 | 182 | 1 | 47140.21 |
| DOWN_40 | 182 | 52 | 60596.93 |
| UP_10 | 168 | 0 | 26825.09 |
| UP_20 | 168 | 0 | 53650.17 |
| UP_30 | 168 | 0 | 80475.26 |
| UP_40 | 168 | 90 | 96276.75 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
