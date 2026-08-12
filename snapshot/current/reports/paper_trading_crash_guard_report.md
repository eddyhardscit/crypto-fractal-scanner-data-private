# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T04:24:00+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **94**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **303.97 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 129 | 0 | 19625.70 |
| DOWN_20 | 129 | 0 | 39251.39 |
| DOWN_30 | 129 | 14 | 59072.19 |
| DOWN_40 | 129 | 43 | 73492.48 |
| UP_10 | 156 | 0 | 26980.03 |
| UP_20 | 156 | 0 | 53960.06 |
| UP_30 | 156 | 10 | 81081.77 |
| UP_40 | 156 | 70 | 96983.37 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
