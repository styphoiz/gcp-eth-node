# More on Solo Staking

## Why Solo Staking?

- Receive maximum rewards directly from the protocol for keeping your validator properly functioning and online
- Run home hardware and personally add to the security and decentralization of the Ethereum network
- Remove trust, and never give up control of the keys to your funds

## What is Solo Staking?

Solo staking involves running an Ethereum node connected to the internet and depositing 32 ETH to become a validator. This allows you to directly participate in the Ethereum network's consensus mechanism.

Solo staking enhances Ethereum's decentralization, making it more resilient against censorship and attacks. Unlike other staking methods, solo staking plays a pivotal role in securing the Ethereum network and is considered the optimal choice for staking.

An Ethereum node consists of an execution layer (EL) client and a consensus layer (CL) client. These software components, combined with a valid set of signing keys, validate transactions, attest to the correct chain head, aggregate attestations, and propose blocks.

As a solo staker, you are responsible for maintaining the hardware required to run these clients. Using a dedicated machine at home is recommended to ensure the network's health.

## Benefits of Solo Staking

- 💸 Earn Fresh ETH: Receive ETH rewards directly from the protocol when your validator is online, without intermediaries.
- 🎛️ Full Control: Retain ownership of your keys and choose the combination of clients and hardware that minimizes risk and contributes to network health.
- 🔐 Network Security: Solo staking significantly enhances network robustness, decentralization, and security by running a validator on your hardware at home.

## Considerations Before Solo Staking

While solo staking offers significant advantages, it comes with added responsibility. Before choosing solo staking for your ETH, consider the following:

- **Required Reading**: Familiarize yourself with the essential concepts of solo staking.
- **Comfortable with Computers**: Ensure you have a reasonable understanding of computer operations.
- **Secure Key Management**: Safeguard your keys to prevent unauthorized access.
- **Maintenance**: Be prepared to maintain your hardware and keep your node online.
- **Reliable Uptime**: Ensure consistent uptime for your validator to maximize rewards.
- **Slashing Risk**: Understand the penalties and risks associated with validator misbehavior.

## How it Works

Here's a step-by-step guide on how solo staking works:

1. **Get Some Hardware**: You need to run an Ethereum node to stake.
2. **Sync an Execution Layer Client**: Set up and synchronize the execution layer client software.
3. **Sync a Consensus Layer Client**: Set up and synchronize the consensus layer client software.
4. **Generate Your Keys**: Create a valid set of signing keys and load them into your validator client.
5. **Monitor and Maintain Your Node**: Ensure your node is active and properly functioning.

While your validator is active, you will earn ETH rewards, which will be periodically deposited into your withdrawal address.

If desired, you can exit as a validator, which eliminates the requirement to be online and stops further rewards. Your remaining balance will then be withdrawn to the designated withdrawal address you specified during setup.

## Frequently Asked Questions

### What is a Validator?

A validator is a virtual entity that participates in the consensus of the Ethereum protocol. Validators are represented by a balance, public key, and other properties. A validator client is the software that acts on behalf of the validator by holding and using its private key. A single validator client can control many validators.

### Can I Deposit More Than 32 ETH?

Each key-pair associated with a validator requires exactly 32 ETH to be activated. More ETH deposited to a single set of keys does not increase rewards potential, as each validator is limited to an effective balance of 32 ETH. This means that staking is done in 32 ETH increments, each with its own set of keys and balance. Do not deposit more than 32 ETH for a single validator. Excess funds over 32 ETH will be automatically withdrawn to the withdrawal address during the next validator sweep.

### Will I Be Slashed if I Go Offline?

Going offline when the network is finalizing properly will NOT result in slashing. Small inactivity penalties are incurred if your validator is not available to attest for a given epoch, but this is different from slashing. Penalties for inactivity are proportional to how many validators are offline at the same time. In cases where a large portion of the network is all offline at once, the penalties for each of these validators will be greater than when a single validator is unavailable.

### How Do I Ensure I Don't Get Slashed?

Act in good faith, run a minority client, and keep your signing keys on one machine at a time to minimize the risk of getting slashed. Only a few specific ways can result in a validator getting slashed, such as redundant hardware setups where signing keys are stored on two separate machines at once.

### Which Client is Best?

All production clients perform the same core functions to sync and interact with the blockchain. Choose a minority client, meaning any client that is NOT currently being used by a majority of validators on the network, to reduce the risk of slashing in the event of a bug.

### Can I Just Use a VPS (Virtual Private Server)?

While a VPS can be used, the physical access and location of your validator client matter. Centralized cloud solutions centralize the network and increase the risk of penalties in case of outages.

### How Do I Unlock My Rewards or Get My ETH Back?

Withdrawals from the Beacon Chain require withdrawal credentials to be set. Reward payments will be periodically distributed to the withdrawal address automatically. To receive your entire balance back, you must complete the process of exiting your validator.
