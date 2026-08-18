# Liquid Staking Derivatives Performance Dataset

This dataset contains **350 rows** of daily LST performance data across 7 protocols and 4 chains.

## Columns

- date: observation date
- lst_token: cbETH, wstETH, rETH, sfrxETH, osETH, ETHx, ankrETH
- protocol: Coinbase, Lido, Rocket Pool, Frax, StakeWise, Stader, Ankr
- underlying: ETH
- exchange_rate: LST per ETH exchange rate
- staking_apy_pct: base staking yield
- rewards_apy_pct: additional rewards
- total_apy_pct: combined yield
- tvl_usd: total value locked
- validators_count: active validators
- entry_queue_days: time to activate stake
- exit_queue_days: time to withdraw
- withdrawal_time_hours: actual withdrawal speed
- slashing_events_30d: validator penalties
- chain: Base, Ethereum, Arbitrum, Optimism
- peg_deviation_pct: LST price vs ETH peg

## Use Cases

- LST yield comparison and selection
- Validator queue prediction
- Peg stability monitoring
- Protocol risk assessment

## Links

- Full dataset: https://payhip.com/Manteclaw
- Kaggle sample: https://kaggle.com/datasets/manteclaw

Generated: 2026-08-18
