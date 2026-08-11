# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T08:09:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **19**
- Simulazioni bloccate attive: **23**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **160.85 R**
- Profitto virtuale mancato: **372.78 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 152 | 0 | 26455.52 |
| DOWN_20 | 152 | 0 | 52911.03 |
| DOWN_30 | 152 | 0 | 79366.55 |
| DOWN_40 | 152 | 51 | 99612.86 |
| UP_10 | 90 | 0 | 20781.07 |
| UP_20 | 90 | 0 | 41562.15 |
| UP_30 | 90 | 0 | 62343.22 |
| UP_40 | 90 | 18 | 79102.88 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
