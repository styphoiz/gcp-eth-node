
# Staking as a Service

Staking as a Service ("SaaS") provides an option for staking where third-party node operators handle the operation of your validator client. This can be a great option for individuals who possess 32 ETH but aren't comfortable dealing with the technical complexities of running a node themselves. With SaaS, you can reduce trust while maintaining custody of your withdrawal keys.

## What is Staking as a Service?

Staking as a Service involves depositing your own 32 ETH to become a validator, while delegating the operation of the node to a third-party operator. The process typically includes guiding you through initial setup, such as key generation and deposit, followed by uploading your signing keys to the operator. The service then operates your validator on your behalf, usually in exchange for a monthly fee.

## Why Stake with a Service?

Staking as a Service has emerged to fulfill the demand for delegation of stake, as the Ethereum protocol does not natively support this feature. If you have 32 ETH to stake but are uncomfortable with hardware-related tasks, SaaS services allow you to delegate the operational aspects while you earn native block rewards.

### Your Own Validator

Deposit your own 32 ETH to activate your set of signing keys, participating in Ethereum consensus. Monitor your progress and watch your ETH rewards accumulate using provided dashboards.

### Easy to Start

Forget about hardware specifications, setup, node maintenance, and upgrades. SaaS providers allow you to outsource these tasks by uploading your signing credentials, enabling them to run a validator on your behalf for a small cost.

### Limit Your Risk

In many cases, you may retain access to the keys for withdrawing or transferring staked funds. These keys are separate from the signing keys and can be stored independently to limit your risk as a staker.

## Comparison with Other Options

### Solo Staking

Like solo staking, using SaaS gives you control over your own validator keys without pooling funds. However, with SaaS, you must trust a third-party operator, which introduces potential risks like malicious behavior or becoming a target of attack or regulation. If concerns about trust and centralization are significant, solo staking is the gold standard for self-sovereign staking.

### Pooled Staking

Both SaaS and pooled staking involve relying on someone else to operate the validator client. However, unlike SaaS, pooled staking allows you to participate with smaller amounts of ETH. If you have less than 32 ETH to stake, consider exploring pooled staking options.

## What to Consider

There is a growing number of SaaS providers available to help you stake your ETH, each with its own benefits and risks. All SaaS options require more trust compared to home staking. Some SaaS options may also include additional code wrapping the Ethereum clients that is not open or auditable. Moreover, SaaS has an impact on network decentralization. Depending on the setup, you might not have full control over your validator, as the operator could potentially act dishonestly using your ETH.

#### Attribute Indicators

Attribute indicators are used to signal notable strengths or weaknesses of a listed SaaS provider. Use these indicators as a reference while selecting a service for your staking journey:

- **Open Source**: Essential code is 100% open source and publicly available.
- **Audited**: Essential code has undergone formal auditing, with results published publicly.
- **Bug Bounty**: A public bug bounty program rewards users for reporting and fixing vulnerabilities.
- **Battle Tested**: The service has been publicly available and used for a specific period.
- **Execution Diversity**: The service maintains diversity in the execution clients used by their validators.
- **Consensus Diversity**: The service maintains diversity in the consensus clients used by their validators.
- **Self Custody**: Users retain custody of validator credentials, including signing and withdrawal keys.

## Frequently Asked Questions

#### Who Holds My Keys?

Arrangements can vary, but typically, you'll set up signing keys (one per 32 ETH) and upload them to your provider for validator operation. Signing keys alone do not enable fund withdrawals, transfers, or spending. They allow you to cast votes towards consensus, which, if done incorrectly, can result in penalties or slashing.

#### So There Are Two Sets of Keys?

Yes, each account has both BLS signing keys and BLS withdrawal keys. Signing keys are used for attesting to the state of the chain, participating in sync committees, and proposing blocks. Withdrawal keys are used to sign a one-time message for staking rewards and exited funds. Once this message is broadcast, withdrawal keys are no longer needed. Control over withdrawn funds is permanently delegated to the withdrawal address you provided, minimizing risk even if someone else controls your validator signing keys.

Updating withdrawal credentials is a required step to enable withdrawals. Make sure to safely back up your seed phrase.

#### When Can I Withdraw?

Staking withdrawals were implemented in the Shanghai/Capella upgrade in April 2023. You'll need to provide a withdrawal address (if not provided initially), and reward payments will be automatically distributed periodically. You can also fully exit as a validator to unlock your remaining ETH balance for withdrawal.

#### What Happens If I Get Slashed?

When using an SaaS provider, you entrust node operation to a third party. If your validator is slashed, your balance will be penalized and removed from the validator pool. After the slashing/exiting process, funds will be transferred to the withdrawal address. This requires providing a withdrawal address to enable. Contact your SaaS provider for more details on guarantees, insurance options, and instructions for providing a withdrawal address.
