**Title:** Add Homer fees and Homer Swap volume (Elysium)

Adds two adapters for Homer (https://homer.finance), the liquidity layer of Elysium. The TVL adapter is in DefiLlama-Adapters PR <link it here>.

- `fees/homer`: fees from Homer's own contracts' events:
  - LP fees collected from positions opened through Homer (FeesCollected splits each collection into the LP's part and Homer's part);
  - Homer Swap's 0.25% fee on routed trades (Swapped.fee, in HYPE);
  - the Homer pool hook's cut of every swap in pools created on Homer (HomerFee).
  Homer's part goes to the fee router, which streams `stakerBps` (read on chain, 60% now) to $HOMER stakers and sends the rest to the team.
- `aggregators/homer-swap`: the HYPE side of every trade routed through Homer Swap (Swapped.hypeAmount). Homer Swap quotes every pool on Elysium and routes each trade through the best one.

Tested locally (`pnpm test fees homer`, `pnpm test aggregators homer-swap`) on the latest master: ~$971/day fees, ~$131/day revenue, ~$5.15K/day volume (Nov 9). All contracts are verified on https://elysium.kinetiq.xyz.
