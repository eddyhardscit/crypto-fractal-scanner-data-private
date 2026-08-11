# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T03:10:02+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **12**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **180.95 R**
- Profitto virtuale mancato: **352.68 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 108 | 0 | 18906.22 |
| DOWN_20 | 108 | 0 | 37812.44 |
| DOWN_30 | 108 | 0 | 56718.66 |
| DOWN_40 | 108 | 39 | 70428.31 |
| UP_10 | 78 | 0 | 20266.16 |
| UP_20 | 78 | 0 | 40532.31 |
| UP_30 | 78 | 0 | 60798.47 |
| UP_40 | 78 | 19 | 77405.69 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
