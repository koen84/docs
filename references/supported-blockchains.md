# ✅ Supported Blockchains

## Integrating New RelayChains

Pocket works out-of-the-box with any network/blockchain \(RelayChain\) that uses the RPC standard. The effort required is not in integrating the RelayChain but in our community of node runners deploying the RelayChain's nodes.

When asking yourself how easy it would be to integrate a RelayChain with Pocket, ask yourself how easy it is for someone to deploy, sync, and maintain a node. How helpful is the documentation? How long does it take to sync a node from scratch? How stable are the nodes? These will be the factors determining how quickly Pocket's community of node runners can support the RelayChain.

## RelayChains Generating Revenue Soon

Due to Pocket Network's permissionless nature, any RelayChainID can be claimed by adding it to the list below and apps/nodes staking on it will be matched together in [sessions](../main-concepts/protocol/servicing.md#sessions). However, the nodes will not earn POKT for their work.

To incentivize node runners to support a new RelayChain at scale, the RelayChainID must be added to the [`SupportedBlockchains`](protocol-parameters.md#supportedblockchains) parameter, meaning that nodes will earn[`RelaysToTokensMultiplier`](protocol-parameters.md#relaystotokensmultiplier) POKT for every request that they relay for the RelayChain. The Generates Revenue column below highlights whether or not the RelayChain has been added to the SupportedBlockchains parameter.

Following '[PIP-6.2: Settlers of New Chains](https://forum.pokt.network/t/pip-6-2-settlers-of-new-chains/1027)', the Pocket Network Foundation controls the SupportedBlockchains parameter on behalf of the DAO. Before adding new RelayChainIDs to the SupportedBlockchains parameter, the Foundation aims to give the community of node runners enough notice to deploy their nodes, to ensure a level playing field. In this interest, below is a list of all upcoming revenue activation events.

July 5th:

* Avalanche \(0003\)
* BSC \(0004\)
* BSC Archival \(0010\)
* Fuse \(0005\)
* xDAI \(0027\)
* Ethereum Archival \(0022\)
* Ethereum Archival Trace \(0028\)
* Ethereum Ropsten \(0023\)
* Ethereum Rinkeby \(0025\)
* Ethereum Goerli \(0026\)
* Ethereum Kovan \(0024\)

## Mainnet RelayChains

| Name | Portal API Prefix | RelayChainID | Generates Revenue |
| :--- | :--- | :--- | :--- |
| Avalanche | avax-mainnet | 0003 | July 5th |
| Binance Smart Chain | bsc-mainnet | 0004 | July 5th |
| Binance Smart Chain Archival | bsc-archival | 0010 | July 5th |
| Binance Smart Chain Testnet | bsc-testnet | 0011 | - |
| Bitcoin | btc-mainnet | 0002 | - |
| Ethereum | eth-mainnet | 0021 | Y |
| Ethereum Archival | eth-archival | 0022 | July 5th |
| Ethereum Archival Trace | eth-archival-trace | 0028 | July 5th |
| Ethereum Goerli | poa-goerli | 0026 | July 5th |
| Ethereum Kovan | poa-kovan | 0024 | July 5th |
| Ethereum Rinkeby | poa-rinkeby | 0025 | July 5th |
| Ethereum Ropsten | eth-ropsten | 0023 | July 5th |
| FUSE | fuse-mainnet | 0005 | July 5th |
| FUSE Archival | fuse-archival | 000A | - |
| Pocket Network | mainnet | 0001 | Y |
| Polygon | matic-mainnet | 0009 | - |
| Solana | sol-mainnet | 0006 | - |
| xDAI | poa-xdai | 0027 | July 5th |

## Testnet RelayChains

| Name | RelayChainID |
| :--- | :--- |
| Ethereum Goerli | 0020 |
| Ethereum Rinkeby | 0022 |
| Ethereum Ropsten | 0023 |
| Pocket Network Testnet | 0002 |

