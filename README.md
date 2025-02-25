# stake.link

## About the Project

stake.link is a first-of-its-kind liquid delegated staking platform delivering DeFi composability for Chainlink Staking. Built by premier Chainlink ecosystem developer LinkPool, powered by Chainlink node operators, and governed by the stake.link DAO, stake.link's extensible architecture is purpose-built to support Chainlink Staking and to extend participation in the Chainlink Network.

![Protocol Diagram](https://res.cloudinary.com/droqoz7lg/image/upload/v1727800681/link-staking-diagram_h9yjdz.png)

- [Website](https://stake.link/)
- [Twitter](https://x.com/stakedotlink)
- [GitHub](https://github.com/stakedotlink/contracts)
- [Docs](https://docs.stake.link/)

## Actors

- **Staker**: Stakers hold stLINK which is the liquid staking token minted by the StakingPool when LINK is deposited.

- **Queued Staker**: Queued stakers have deposited LINK into the Priority Pool that is queued to be staked into the
  Staking Pool once space becomes available.

- **Queued Withdrawer**: Queued withdrawers have deposited stLINK into the Withdrawal Pool that is queued for withdrawal once LINK becomes available.

- **Operator**: An operator has authorization to raise an alert in the Chainlink staking contract through their
  respective Operator Vault.

- **Operator Rewards Receiver**: The rewards receiver in an Operator Vault has authorization to withdraw operator rewards for that vault as well as transfer the role to another address.

- **Owner**: The owner is a 5/7 multisig controlled by the stake.link council and has authorization to upgrade
  contracts and manage parameters that affect how the protocol functions.

## Scope (contracts)

The following contracts are in scope:

## Compatibilities

Blockchains:
- Ethereum

Tokens:
- [ERC20](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/) 
- [ERC677](https://github.com/ethereum/EIPs/issues/677)

[//]: # (scope-close)

[//]: # (getting-started-open)

## Setup

Build:

```bash
yarn install

yarn compile
```

Tests:

```bash
yarn test
```

[//]: # (getting-started-close)

[//]: # (known-issues-open)
