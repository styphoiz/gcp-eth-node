# Pooled Staking

Pooled staking is a collaborative approach that allows individuals to stake and earn rewards with any amount of ETH by joining forces with others. This option simplifies validator operation by entrusting it to a third-party, while allowing stakers to hold staking tokens in their own wallet.

## What Are Staking Pools?

Staking pools enable users with smaller amounts of ETH to obtain the required 32 ETH for activating a set of validator keys. Since pooling is not natively supported by the protocol, solutions were developed separately to address this need.

Some pools operate through smart contracts, where funds are deposited to a contract that manages and tracks stake. In return, stakers receive a token representing their stake. Other pools may operate off-chain.

## Why Stake with a Pool?

- **Low Barrier to Entry**: Staking pools allow stakers with any amount of ETH to participate, unlike solo staking which requires 32 ETH.
- **Stake Today**: Staking with a pool is as easy as a token swap. No need to worry about hardware setup and node maintenance. Rewards are distributed to contributors minus a fee for node operations.
- **Staking Tokens**: Many staking pools issue tokens representing staked ETH and rewards. These tokens can be used as collateral in DeFi applications.

### Comparison with Other Options

#### Solo Staking

Pooled staking has a significantly lower barrier to entry compared to solo staking. However, pooled staking involves delegating node operations to a third-party and paying a fee. Solo staking provides full control over the staking setup and rewards without middlemen.

#### Staking as a Service (SaaS)

Staking with a service also involves not running the validator software yourself. However, SaaS requires a full 32 ETH deposit to activate a validator. Using SaaS comes with a fee and provides your own validator keys. If you have at least 32 ETH and prefer retaining your own keys, SaaS might be a suitable option.

## What to Consider

Pooled staking is not natively supported by the Ethereum protocol, but a range of solutions have been developed to cater to users who want to stake less than 32 ETH.

Different pools and tools, including smart contracts, have been developed by various teams, each with its own benefits and risks. Pools allow users to swap ETH for tokens representing staked ETH. These tokens can be traded for yield-bearing tokens generating returns from staking rewards, even though the actual ETH remains staked. However, these tokens can lead to centralization, potentially facilitating censorship or value extraction. For the highest level of security, individuals running validators on their own hardware remains the gold standard for staking.

#### Attribute Indicators

Attribute indicators are used to signal notable strengths or weaknesses of a staking pool. Refer to these indicators while choosing a pool to join:

- **Open Source**: Essential code is 100% open source and available for public use.
- **Audited**: Essential code has undergone formal auditing, with publicly available results.
- **Bug Bounty**: A public bug bounty program rewards users for reporting and fixing vulnerabilities.
- **Battle Tested**: The service has been publicly available and used for a specific period.
- **Trustless**: The service does not require trusting humans for key custody or reward distribution.
- **Permissionless Nodes**: The service allows anyone to join as a node operator without permission.
- **Execution Diversity**: The service maintains diversity in execution clients used by validators.
- **Consensus Diversity**: The service maintains diversity in consensus clients used by validators.
- **Liquidity Token**: Offers a tradable liquidity token representing your staked ETH, held in your own wallet.

## Frequently Asked Questions

#### How Do I Earn Rewards?

Stakers typically receive ERC-20 staking tokens representing their staked ETH and rewards. Different pools may distribute rewards slightly differently, but the underlying concept remains the same.

#### When Can I Withdraw My Stake?

With the Shanghai/Capella network upgrade in April 2023, staking withdrawals were introduced. Validator accounts backing staking pools now have the ability to exit and withdraw ETH to their designated withdrawal address. Some pools with ERC-20 staking tokens allow users to trade these tokens on the open market, effectively "withdrawing" without removing ETH from the staking contract.

#### Is This Different from Staking with My Exchange?

Pooled staking options share similarities with centralized exchanges in terms of enabling staking with small amounts of ETH. However, pooled staking often utilizes smart contracts and/or staking tokens, which provide more sovereignty and security compared to centralized exchanges. The tokens can be held in your own wallet and traded, offering control over your tokens. Nonetheless, pooled staking doesn't grant direct control over the validator client attesting on your behalf in the background. Some pools are more decentralized than others regarding the backing nodes.

