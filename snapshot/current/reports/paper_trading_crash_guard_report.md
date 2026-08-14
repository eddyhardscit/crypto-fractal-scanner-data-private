# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T07:06:45+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **19**
- Simulazioni bloccate attive: **78**
- Simulazioni completate nel ciclo: **42**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **545.69 R**
- Profitto virtuale mancato: **522.27 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 202 | 0 | 20671.73 |
| DOWN_20 | 202 | 0 | 41343.47 |
| DOWN_30 | 202 | 1 | 62028.39 |
| DOWN_40 | 202 | 60 | 79962.10 |
| UP_10 | 164 | 0 | 32540.89 |
| UP_20 | 164 | 1 | 65085.14 |
| UP_30 | 164 | 9 | 97709.94 |
| UP_40 | 164 | 71 | 119032.44 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
