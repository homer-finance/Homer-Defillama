**Title:** Add Homer (Elysium)

##### Name (to be shown on DefiLlama):
Homer

##### Twitter Link:
https://x.com/homer_fi

##### List of audit links if any:
None yet. All contracts are verified on Kinetiq's explorer (https://elysium.kinetiq.xyz).

##### Website Link:
https://homer.finance

##### Logo (High resolution, will be shown with rounded borders):
(attach homer-logo-1000.png)

##### Current TVL:
~$22K (plus ~$5.4K staking)

##### Treasury Addresses (if the protocol has treasury)
0x5def359cf05a374c6c29718d83216bbe88f663e4 (team share from the fee router)

##### Chain:
Elysium

##### Coingecko ID (so your TVL can appear on Coingecko, leave empty if not listed):

##### Coinmarketcap ID (so your TVL can appear on Coinmarketcap, leave empty if not listed):

##### Short Description (to be shown on DefiLlama):
Homer is the liquidity layer of Elysium: every pool on the chain in one place, best-rate swaps across all of Elysium's DEXes, and managed liquidity positions (add with one token, one-click rebalance, fee tracking) on Uniswap v3 and v4-style pools.

##### Token address and ticker if any:
HOMER, 0x365be4728d0ee2140e8b75a05c5dcf6b7d76399a

##### Category (full list at https://defillama.com/categories) *Please choose only one:
Liquidity manager

##### Oracle Provider(s): Specify the oracle(s) used (e.g., Chainlink, Band, API3, TWAP, etc.):
None

##### Implementation Details: Briefly describe how the oracle is integrated into your project:
No oracle is used.

##### Documentation/Proof: Provide links to documentation or any other resources that verify the oracle's usage:
https://homer.finance/docs

##### forkedFrom (Does your project originate from another project):
None

##### methodology (what is being counted as tvl, how is tvl being calculated):
TVL is the liquidity in positions users opened through Homer: Uniswap v3-style position NFTs held by the HomerLiquidityManager contracts and Uniswap v4 positions held by the HomerV4Manager contracts, valued from each position's liquidity and range at the pool's current price. These positions sit in other DEXes' pools, so the TVL is marked as double counted. Staking is the $HOMER staked in HomerStaking, valued at the HOMER/WHYPE pool price on KleosSwap.

##### Github org/user (Optional, if your code is open source, we can track activity):

##### Does this project have a referral program?
Yes: referrers earn 20% of the fees Homer takes from the wallets they bring (Homer Swap fees and Homer's share of LP fees), paid by the team from its share in HYPE. Referred users pay nothing extra.
