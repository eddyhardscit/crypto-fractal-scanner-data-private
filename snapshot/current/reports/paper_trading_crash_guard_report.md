# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-23T18:38:36+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **25**
- Simulazioni completate nel ciclo: **5**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **9.33 R**
- Profitto virtuale mancato: **11.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 120 | 0 | 15267.06 |
| DOWN_20 | 120 | 0 | 30534.11 |
| DOWN_30 | 120 | 3 | 45863.96 |
| DOWN_40 | 120 | 35 | 57554.88 |
| UP_10 | 63 | 0 | 16534.70 |
| UP_20 | 63 | 0 | 33069.40 |
| UP_30 | 63 | 0 | 49604.10 |
| UP_40 | 63 | 35 | 58593.53 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
