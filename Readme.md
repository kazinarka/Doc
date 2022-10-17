# Dexs research
## Serum
Serum provides a fully on-chain orderbook, allowing applications such as trading interfaces to 'plug into' Serum's composable ecosystem.
### Common functionality
 - Serum Core

Asset Agnostic order book for matching any Solana based trading product from options, futures, borrow lending positions, or any financial and non-financial instrument that can take advantage of Serum’s backend matching engine.

- True Composability

Serum makes it possible for a diverse range of applications and participants to share middleware in one place. The design of the AOB makes Serum’s architecture more suited to modularity. Programs that use Serum will have more flexibility, all while maintaining some standard design principles and composability.

- Developer Ecosystem and Services

Decentralized on chain order matching service that provides infrastructure for trading applications, giving developers full control and flexibility.
Permissioned markets allow for even greater flexibility and compliance.
Serum DEX, built on top of the Asset Agnostic Order book provides the ecosystem with a greater source of pooled liquidity and shared resource to power based trading features.
### Advantages
- Serum Token (SRM)

SRM is the utility and governance token of the Serum ecosystem
SRM will be fully integrated into Serum and benefit from buy/burn of fees

- Solana Speeds and Costs

Solana allows for sub-second trading and settlement on top of ultra-low transaction costs of $0.00001 per transaction
### Useful links
Rust docs
>https://docs.rs/serum/0.4.7/serum_dex/

Rust serum-dex folder
>https://github.com/project-serum/serum-dex

serum-dex Crates.io
>https://crates.io/crates/serum_dex

Clients' library (TS)
>https://github.com/project-serum/serum-ts/blob/master/README.md

Clients' library (Python)
>https://github.com/serum-community/pyserum

Clients' library (.Net)
>https://github.com/bmresearch/Solnet.Serum
## Orca
Orca is an easy place to trade cryptocurrency on the Solana blockchain. On Orca, you can trade tokens cheaply, quickly, and confidently (thanks to the Fair Price Indicator). Additionally, you can provide liquidity to a liquidity pools, including concentrated liquidity pools (Whirlpools) to earn trading fees and token emissions.
### Common functionality
- Obtain pool and farm addresses
- Obtain price quotes
- Trade
- Deposit to and withdraw from a liquidity pool
- Stake and unstake from a farm
- Harvest stake rewards
- Make use of miscellaneous helper functions
### Advantages
- Use the WhirlpoolClient or construct your own transactions with the raw instructions to:
    - Manage your positions (open position, increase, decrease liquidity, close position)
    - Collect fees and rewards
    - As a WhirlpoolsConfig owner, manage a set of Whirlpools
- Quotes - helper functions to help developers perform quote estimations on tasks such as:
    - Estimating the tokens required to deposit or withdrawn from positions
    - Estimating available fees and rewards to collect
    - Get a quote on a swap
- Utility classes
    - AccountFetcher - simple to use class to fetch, parse & cache Whirlpools accounts
    - Easily calculate conversion math between price, sqrt-price and ticks
    - Other helper functions to help interact with Whirlpools components
### Useful links
Program and TS SDK
>https://github.com/orca-so/whirlpools

Instruction documentation

>https://github.com/orca-so/whirlpools/blob/main/programs/whirlpool/src/lib.rs

Api docs
>https://orca-so.gitbook.io/orca-developer-portal/whirlpools/interacting-with-the-protocol

TS SDK
>https://github.com/orca-so/typescript-sdk
## Raydium
Raydium is an automated market maker (AMM) built on the Solana blockchain which leverages the central order book of the Serum decentralized exchange (DEX) to enable lightning-fast trades, shared liquidity and new features for earning yield.
### Common functionality
- Trade and swap

Raydium's swap feature allows two tokens to be exchanged quickly through Serum, while the DEX UI also allows for more advanced trading features such as limit orders. These make for a better trading experience for users.  
- Earn RAY

There are a number of ways to earn RAY tokens while farming liquidity pools and staking. More features are on the way!
### Advantages
Other AMM DEXs and DeFi protocols are only able to access liquidity within their own pools and have no access to a central order book. Additionally, with the majority of platforms running on Ethereum, transactions are slow and gas fees are high.

Raydium offers a few key advantages:

- Faster and cheaper: 

    - Raydium leverages the efficiency of the Solana blockchain to achieve transactions magnitudes faster than Ethereum and gas fees which are a fraction of the cost.


- A central order book for ecosystem-wide liquidity: 
  - Raydium provides on-chain liquidity to the central limit order book of the Serum DEX, meaning that Raydium allows access to the order flow and liquidity of the entire Serum ecosystem.


- Trading interface: 
  - For traders who want to be able to view TradingView charts, set limit orders and have more control over their trading.
### Useful links
SDK
>https://sdk.raydium.io/