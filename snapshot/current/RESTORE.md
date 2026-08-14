# Restore contract

Paper state and the permanent append-only trade/signal ledgers are restored from
the `paper-trading-v1` Release by `paper_trading_storage.py restore`. The exchange
working state is restored from its two redundant Release assets; completed UTC
months remain immutable Release archives. Published scanner artifacts are restored
from the exact publisher repository commit recorded in `RELEASE_REFERENCE.json`.

`snapshot/legacy-last-full` preserves the final pre-migration full Git snapshot.
Every earlier full snapshot remains available from existing Git history.
