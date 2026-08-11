# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T10:10:02+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **21**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **156.47 R**
- Profitto virtuale mancato: **377.16 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 157 | 0 | 26714.29 |
| DOWN_20 | 157 | 0 | 53428.58 |
| DOWN_30 | 157 | 0 | 80142.87 |
| DOWN_40 | 157 | 53 | 100581.75 |
| UP_10 | 96 | 0 | 20238.71 |
| UP_20 | 96 | 0 | 40477.41 |
| UP_30 | 96 | 0 | 60716.12 |
| UP_40 | 96 | 18 | 76655.00 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
