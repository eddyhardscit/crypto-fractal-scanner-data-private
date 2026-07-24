# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T11:02:58+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **16**
- Simulazioni completate nel ciclo: **6**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-39.46 R**
- Profitto virtuale mancato: **77.89 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 102 | 0 | 13169.25 |
| DOWN_20 | 102 | 0 | 26338.50 |
| DOWN_30 | 102 | 10 | 39645.53 |
| DOWN_40 | 102 | 26 | 49908.22 |
| UP_10 | 64 | 0 | 18403.79 |
| UP_20 | 64 | 0 | 36807.58 |
| UP_30 | 64 | 0 | 55211.37 |
| UP_40 | 64 | 36 | 65562.11 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
