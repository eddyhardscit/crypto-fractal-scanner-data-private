# Market Regime Match Report

Generated: 2026-08-14 05:36 UTC

This report adds market regime context to the raw fractal matches.

Main idea:

- A chart match during a bull market is not the same as a chart match during a bear market.
- This report separates matches by BTC regime and by similar-asset regime.
- The most useful group is SAME_BTC_AND_ASSET_REGIME, but only if it has enough matches.

## Current regime snapshot

| target   | target_regime_today   |   target_price | target_above_ma200   | target_return_90d   | target_ma200_slope_60d   | btc_regime_today   | btc_return_90d   | btc_ma200_slope_60d   |
|:---------|:----------------------|---------------:|:---------------------|:--------------------|:-------------------------|:-------------------|:-----------------|:----------------------|
| BTC-USD | BEAR | 63.250 $ | False | -19.01% | -10.18% | BEAR | -19.01% | -10.18% |
| DOGE-USD | BEAR | 0.06994 $ | False | -36.07% | -16.70% | BEAR | -19.01% | -10.18% |
| SOL-USD | BEAR | 75,80 $ | False | -12.33% | -16.92% | BEAR | -19.01% | -10.18% |

## Summary by regime filter

| target   | group                     |   matches | positive_30d_rate   | return_30d_p50   | return_30d_p75   | return_30d_p90   | drawdown_30d_p50   | drawdown_30d_p10   | max_gain_30d_p50   | max_gain_30d_p75   | max_gain_30d_p90   | positive_60d_rate   | return_60d_p50   | return_60d_p75   | return_60d_p90   |
|:---------|:--------------------------|----------:|:--------------------|:-----------------|:-----------------|:-----------------|:-------------------|:-------------------|:-------------------|:-------------------|:-------------------|:--------------------|:-----------------|:-----------------|:-----------------|
| BTC-USD | ALL_MATCHES | 40 | 75.00% | 10.41% | 19.43% | 58.72% | -3.13% | -16.60% | 19.23% | 32.97% | 68.81% | 57.50% | 9.56% | 66.14% | 151.06% |
| BTC-USD | SAME_BTC_REGIME | 22 | 81.82% | 10.74% | 17.03% | 57.28% | -2.50% | -7.13% | 19.23% | 36.30% | 65.70% | 45.45% | -5.45% | 71.94% | 145.83% |
| BTC-USD | SAME_ASSET_REGIME | 23 | 82.61% | 11.07% | 18.10% | 44.52% | -2.51% | -14.09% | 18.73% | 26.19% | 62.61% | 52.17% | 5.16% | 70.57% | 104.60% |
| BTC-USD | SAME_BTC_AND_ASSET_REGIME | 19 | 84.21% | 11.07% | 16.71% | 56.82% | -2.49% | -6.50% | 18.73% | 22.83% | 71.10% | 47.37% | -10.17% | 70.57% | 117.47% |
| DOGE-USD | ALL_MATCHES | 40 | 67.50% | 12.05% | 28.91% | 47.55% | -9.86% | -28.12% | 22.24% | 38.39% | 58.83% | 47.50% | -2.61% | 13.99% | 52.69% |
| DOGE-USD | SAME_BTC_REGIME | 20 | 90.00% | 18.34% | 39.59% | 58.34% | -9.86% | -17.54% | 23.94% | 45.90% | 72.75% | 55.00% | 2.33% | 10.21% | 111.39% |
| DOGE-USD | SAME_ASSET_REGIME | 17 | 88.24% | 15.11% | 27.54% | 44.28% | -9.15% | -18.91% | 23.54% | 35.15% | 59.27% | 52.94% | 1.61% | 5.82% | 12.76% |
| DOGE-USD | SAME_BTC_AND_ASSET_REGIME | 16 | 87.50% | 14.57% | 25.54% | 45.83% | -8.48% | -20.60% | 23.48% | 37.32% | 61.28% | 50.00% | -0.19% | 5.65% | 13.79% |
| SOL-USD | ALL_MATCHES | 40 | 72.50% | 7.17% | 26.31% | 85.79% | -4.47% | -14.74% | 18.34% | 49.03% | 110.25% | 57.50% | 12.25% | 61.82% | 188.42% |
| SOL-USD | SAME_BTC_REGIME | 14 | 92.86% | 15.83% | 44.44% | 86.17% | -0.12% | -6.95% | 26.39% | 65.99% | 96.37% | 57.14% | 59.10% | 106.75% | 174.66% |
| SOL-USD | SAME_ASSET_REGIME | 13 | 84.62% | 13.12% | 21.01% | 77.29% | -3.10% | -11.96% | 22.38% | 48.60% | 81.55% | 53.85% | 10.98% | 88.25% | 178.56% |
| SOL-USD | SAME_BTC_AND_ASSET_REGIME | 11 | 90.91% | 15.59% | 25.01% | 89.36% | -3.10% | -7.11% | 23.31% | 49.46% | 89.36% | 54.55% | 56.65% | 117.80% | 186.36% |

## Breakdown by historical BTC regime

| target   | group                       |   matches | positive_30d_rate   | return_30d_p50   | drawdown_30d_p50   | max_gain_30d_p75   | positive_60d_rate   | return_60d_p50   | max_gain_60d_p75   |
|:---------|:----------------------------|----------:|:--------------------|:-----------------|:-------------------|:-------------------|:--------------------|:-----------------|:-------------------|
| BTC-USD | HISTORICAL_BTC_BEAR | 22 | 81.82% | 10.74% | -2.50% | 36.30% | 45.45% | -5.45% | 95.48% |
| BTC-USD | HISTORICAL_BTC_BULL | 10 | 90.00% | 15.66% | -1.69% | 35.42% | 90.00% | 21.72% | 77.40% |
| BTC-USD | HISTORICAL_BTC_RECOVERY | 8 | 37.50% | -3.05% | -5.47% | 21.39% | 50.00% | 20.41% | 70.17% |
| DOGE-USD | HISTORICAL_BTC_BEAR | 20 | 90.00% | 18.34% | -9.86% | 45.90% | 55.00% | 2.33% | 60.69% |
| DOGE-USD | HISTORICAL_BTC_BULL | 17 | 35.29% | -3.46% | -13.49% | 22.39% | 35.29% | -21.46% | 33.11% |
| DOGE-USD | HISTORICAL_BTC_DISTRIBUTION | 1 | 100.00% | 11.10% | 0.00% | 36.94% | 100.00% | 19.41% | 36.94% |
| DOGE-USD | HISTORICAL_BTC_RECOVERY | 2 | 100.00% | 23.81% | -8.62% | 28.42% | 50.00% | -0.95% | 36.12% |
| SOL-USD | HISTORICAL_BTC_BEAR | 14 | 92.86% | 15.83% | -0.12% | 65.99% | 57.14% | 59.10% | 111.53% |
| SOL-USD | HISTORICAL_BTC_BULL | 9 | 77.78% | 10.45% | -1.51% | 75.54% | 44.44% | -1.64% | 142.40% |
| SOL-USD | HISTORICAL_BTC_RECOVERY | 17 | 52.94% | 0.35% | -4.97% | 21.19% | 64.71% | 13.51% | 52.19% |

## Breakdown by historical asset regime

| target   | group                         |   matches | positive_30d_rate   | return_30d_p50   | drawdown_30d_p50   | max_gain_30d_p75   | positive_60d_rate   | return_60d_p50   | max_gain_60d_p75   |
|:---------|:------------------------------|----------:|:--------------------|:-----------------|:-------------------|:-------------------|:--------------------|:-----------------|:-------------------|
| BTC-USD | HISTORICAL_ASSET_BEAR | 23 | 82.61% | 11.07% | -2.51% | 26.19% | 52.17% | 5.16% | 81.04% |
| BTC-USD | HISTORICAL_ASSET_BULL | 4 | 100.00% | 15.66% | -0.07% | 72.26% | 100.00% | 119.30% | 279.89% |
| BTC-USD | HISTORICAL_ASSET_DISTRIBUTION | 3 | 100.00% | 58.23% | 0.00% | 87.46% | 66.67% | 41.56% | 135.68% |
| BTC-USD | HISTORICAL_ASSET_RECOVERY | 10 | 40.00% | -3.05% | -6.36% | 24.23% | 50.00% | 0.09% | 59.33% |
| DOGE-USD | HISTORICAL_ASSET_BEAR | 17 | 88.24% | 15.11% | -9.15% | 35.15% | 52.94% | 1.61% | 45.11% |
| DOGE-USD | HISTORICAL_ASSET_BULL | 10 | 60.00% | 9.70% | -5.90% | 41.28% | 70.00% | 14.18% | 53.36% |
| DOGE-USD | HISTORICAL_ASSET_DISTRIBUTION | 2 | 100.00% | 51.18% | -11.72% | 54.71% | 100.00% | 82.52% | 130.29% |
| DOGE-USD | HISTORICAL_ASSET_RECOVERY | 11 | 36.36% | -2.19% | -13.49% | 14.83% | 9.09% | -25.34% | 17.66% |
| SOL-USD | HISTORICAL_ASSET_BEAR | 13 | 84.62% | 13.12% | -3.10% | 48.60% | 53.85% | 10.98% | 107.36% |
| SOL-USD | HISTORICAL_ASSET_BULL | 5 | 80.00% | 49.59% | -1.51% | 75.54% | 60.00% | 62.63% | 342.74% |
| SOL-USD | HISTORICAL_ASSET_DISTRIBUTION | 4 | 75.00% | 7.08% | -4.99% | 37.01% | 25.00% | -2.15% | 41.51% |
| SOL-USD | HISTORICAL_ASSET_MIXED | 3 | 66.67% | 78.73% | -2.60% | 104.45% | 66.67% | 112.92% | 221.88% |
| SOL-USD | HISTORICAL_ASSET_RECOVERY | 15 | 60.00% | 5.22% | -4.86% | 23.42% | 66.67% | 13.51% | 56.95% |

## Top regime-adjusted matches

The table below shows the top matches separately for each target, so BTC does not hide SOL and DOGE.

| target   | similar_asset   | start_date   | similarity   | btc_regime_at_match   | similar_asset_regime_at_match   | regime_alignment   | outcome_family   | return_30d   | drawdown_30d   | max_gain_30d   | return_60d   | drawdown_60d   | max_gain_60d   |
|:---------|:----------------|:-------------|:-------------|:----------------------|:--------------------------------|:-------------------|:-----------------|:-------------|:---------------|:---------------|:-------------|:---------------|:---------------|
| BTC-USD | XRP-USD | 2026-01-05 | 89.86% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | 8.98% | 0.00% | 8.98% | -15.55% | -19.71% | 8.98% |
| BTC-USD | ETH-USD | 2026-01-05 | 88.18% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | -1.82% | -3.01% | 4.21% | -27.68% | -32.48% | 4.21% |
| BTC-USD | BTC-USD | 2018-10-22 | 88.06% | BEAR | BEAR | SAME_BTC_AND_ASSET | BULLISH_30D | 11.79% | -1.41% | 20.14% | 19.10% | -1.41% | 20.14% |
| BTC-USD | NEO-USD | 2018-10-24 | 87.91% | BEAR | BEAR | SAME_BTC_AND_ASSET | BULLISH_30D | 27.24% | -1.02% | 46.91% | 44.33% | -1.02% | 46.91% |
| BTC-USD | OMG-USD | 2018-10-24 | 87.60% | BEAR | BEAR | SAME_BTC_AND_ASSET | EXPLOSIVE_60D | 17.35% | -6.48% | 23.17% | 67.84% | -6.48% | 81.36% |
| BTC-USD | XTZ-USD | 2018-10-24 | 86.17% | BEAR | BEAR | SAME_BTC_AND_ASSET | EXPLOSIVE_60D | 7.22% | -3.99% | 22.40% | 159.29% | -3.99% | 179.67% |
| BTC-USD | QTUM-USD | 2026-01-05 | 85.68% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | 9.08% | -4.42% | 15.90% | -19.04% | -24.31% | 15.90% |
| BTC-USD | SOL-USD | 2026-01-08 | 85.61% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | -4.16% | -6.58% | 9.54% | -17.40% | -30.02% | 9.54% |
| BTC-USD | ETC-USD | 2018-10-24 | 85.49% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | 8.28% | -4.92% | 22.50% | 22.00% | -4.92% | 23.79% |
| BTC-USD | 1INCH-USD | 2024-07-11 | 85.41% | BEAR | BEAR | SAME_BTC_AND_ASSET | EXPLOSIVE_60D | 11.07% | -15.97% | 17.08% | 73.31% | -15.97% | 124.84% |
| DOGE-USD | OP-USD | 2026-01-06 | 91.75% | BEAR | BEAR | SAME_BTC_AND_ASSET | BULLISH_30D | 14.03% | -0.09% | 43.84% | -9.51% | -24.09% | 43.84% |
| DOGE-USD | THETA-USD | 2022-03-26 | 88.06% | BEAR | BEAR | SAME_BTC_AND_ASSET | BULLISH_30D | 13.01% | -10.28% | 22.09% | -4.02% | -10.28% | 37.23% |
| DOGE-USD | ADA-USD | 2022-03-27 | 88.05% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | 6.67% | -11.01% | 11.91% | -3.21% | -11.01% | 21.44% |
| DOGE-USD | CHZ-USD | 2022-03-26 | 87.91% | BEAR | BEAR | SAME_BTC_AND_ASSET | EXPLOSIVE_60D | 38.08% | -1.30% | 51.20% | 116.30% | -1.30% | 153.33% |
| DOGE-USD | QTUM-USD | 2022-07-30 | 87.56% | BEAR | BEAR | SAME_BTC_AND_ASSET | BEARISH_30D | -22.20% | -30.29% | 1.37% | -32.40% | -35.81% | 1.37% |
| DOGE-USD | NEO-USD | 2022-03-27 | 87.42% | BEAR | BEAR | SAME_BTC_AND_ASSET | BULLISH_30D | 24.88% | -6.07% | 31.81% | 4.99% | -6.07% | 39.85% |
| DOGE-USD | LTC-USD | 2018-04-25 | 86.81% | BEAR | BEAR | SAME_BTC_AND_ASSET | BEARISH_30D | -13.38% | -29.08% | 1.83% | -20.92% | -32.15% | 1.83% |
| DOGE-USD | XTZ-USD | 2026-01-05 | 86.79% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | 9.21% | 0.00% | 15.85% | -31.20% | -34.31% | 15.85% |
| DOGE-USD | DASH-USD | 2022-03-27 | 86.60% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | 9.84% | -9.75% | 18.21% | 3.04% | -9.75% | 28.47% |
| DOGE-USD | FIL-USD | 2022-03-26 | 86.29% | BEAR | BEAR | SAME_BTC_AND_ASSET | HIGH_SPIKE_60D | 53.58% | -4.32% | 85.24% | 8.64% | -4.32% | 85.24% |
| SOL-USD | ENJ-USD | 2018-10-24 | 85.03% | BEAR | BEAR | SAME_BTC_AND_ASSET | EXPLOSIVE_60D | 190.30% | -13.17% | 193.34% | 417.86% | -13.17% | 644.83% |
| SOL-USD | EOS-USD | 2018-11-03 | 81.88% | BEAR | BEAR | SAME_BTC_AND_ASSET | EXPLOSIVE_60D | 29.01% | -3.10% | 50.33% | 88.25% | -3.10% | 105.67% |
| SOL-USD | NEAR-USD | 2026-01-05 | 81.24% | BEAR | BEAR | SAME_BTC_AND_ASSET | EXPLOSIVE_60D | 15.59% | -7.11% | 17.95% | 56.65% | -7.11% | 107.36% |
| SOL-USD | SOL-USD | 2026-01-08 | 79.80% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | -4.16% | -6.58% | 9.54% | -17.40% | -30.02% | 9.54% |
| SOL-USD | RUNE-USD | 2026-01-11 | 79.60% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | 2.83% | 0.00% | 48.60% | -7.07% | -24.29% | 48.60% |
| SOL-USD | QTUM-USD | 2018-10-24 | 79.38% | BEAR | BEAR | SAME_BTC_AND_ASSET | EXPLOSIVE_60D | 13.12% | -5.39% | 29.47% | 61.55% | -5.39% | 61.55% |
| SOL-USD | XTZ-USD | 2018-11-03 | 77.97% | BEAR | BEAR | SAME_BTC_AND_ASSET | EXPLOSIVE_60D | 21.01% | 0.00% | 22.38% | 147.35% | 0.00% | 179.64% |
| SOL-USD | LINK-USD | 2026-01-05 | 77.96% | BEAR | BEAR | SAME_BTC_AND_ASSET | BULLISH_30D | 16.07% | 0.00% | 18.73% | -11.59% | -18.53% | 18.73% |
| SOL-USD | KAVA-USD | 2026-01-10 | 77.54% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | 3.53% | 0.00% | 23.31% | -16.11% | -23.42% | 23.31% |
| SOL-USD | BTC-USD | 2026-01-08 | 77.14% | BEAR | BEAR | SAME_BTC_AND_ASSET | MIXED | 0.39% | -4.24% | 6.50% | -14.94% | -21.08% | 6.50% |

## Interpretation rules

- ALL_MATCHES is the raw view. It can mix bull, bear, recovery and distribution phases.
- SAME_BTC_REGIME is cleaner because BTC had a similar macro background.
- SAME_ASSET_REGIME is cleaner because the matched altcoin had a similar local trend.
- SAME_BTC_AND_ASSET_REGIME is the cleanest filter, but it needs enough matches to matter.
- If SAME_BTC_AND_ASSET_REGIME has fewer than 5 matches, treat it as useful context, not a strong statistic.
- If ALL_MATCHES is bullish but SAME_BTC_AND_ASSET_REGIME is bearish, the bullish read is weaker.
- If ALL_MATCHES is uncertain but SAME_BTC_AND_ASSET_REGIME improves, the setup is more interesting.

## Regime definitions

- BULL: price above MA200, MA200 rising, positive 90d trend.
- BEAR: price below MA200, MA200 falling, weak 90d trend.
- RECOVERY: improving 90d trend, but not yet a clean bull structure.
- DISTRIBUTION: price still structurally high, but 90d momentum is weakening.
- MIXED: unclear regime.
- UNKNOWN: not enough historical data.

