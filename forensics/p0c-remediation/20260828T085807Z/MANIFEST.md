# P0C missing-cost preservation receipt

- Created UTC: 2026-08-28T08:58:07Z
- Source repository: `/root/crypto-fractal-scanner`
- Source HEAD: `bb2a69033446511e9391b1e57be47fdcda4575a2`
- Runtime source tracked: no
- Regression test tracked: no
- Commit decision: not safe; adding the exact paths would commit two complete pre-existing untracked files rather than only the P0C remediation delta.

## Root cause and contract

`_p0c_backfill_integrity_metadata` supplied provenance but omitted all six cost values. The lower authority layer normalized the omissions to null and correctly rejected the resulting difference from an immutable observed `entry_fee`.

The preserved fix establishes: missing incoming data preserves an existing authoritative value; missing plus missing remains unknown; a concrete incoming value may fill a missing value only through the existing explicit authority gate; equal concrete values are idempotent; different concrete values remain fail-closed.

Fields covered: `entry_fee`, `exit_fee`, `entry_slippage`, `exit_slippage`, `funding_amount`, and `funding_policy`.

Economic parameters changed: no. Strategy logic changed: no. Permanent ledger changes: no.

## File hashes

- `forward_shadow_exit_lab.py` pre-fix: `eca764cad7edc267cff9d68d2b0767c4ee3c46604f06594e7f82cca12291aac5`
- `forward_shadow_exit_lab.py` post-fix: `0dfb042bb9eb98ecb0479ef3f52244f9a0de230110e58c437046548178572555`
- `tests/test_exit_only_cohort_authority_integrity.py` pre-fix: `0433d9cf868414c061c0fd2066a3dc0e3286782deee0c63f49b3cb88ea8ce140`
- `tests/test_exit_only_cohort_authority_integrity.py` post-fix: `6526fff59258e834d343b9a130823c3a21842942e2fae37fee10371fe7467e3b`

The pre-images were reconstructed deterministically by reversing the exact remediation transcript; the original failing source line was independently confirmed in the system journal.

## Scope

The accompanying unified diff contains only the producer/backfill cost-preservation logic and its three regression tests. It contains no strategy constants, thresholds, portfolio logic, execution sizing, or economic parameter changes.
