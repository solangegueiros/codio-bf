|||guidance
### Layer 2s

|||

In the Ethereum context, a [Layer-2](https://chain.link/education-hub/what-is-layer-2) (L2) solution is another framework or protocol built on top of the Ethereum blockchain (Layer-1) to improve its scalability, efficiency, and speed. It is not a separate blockchain in the traditional sense.

Layer-2 solutions handle transactions outside the main Ethereum chain (Layer-1) but still rely on Ethereum's security and decentralization. They are designed to work directly with the Ethereum blockchain and are not independent blockchains with their own consensus mechanisms.

Examples include State Channels and Rollups.

### State Channels

State channels allow users to perform multiple offchain transactions while only recording the final state on the Ethereum blockchain. This approach reduces the need for numerous onchain transactions.

State Channels examples:[Celer Network](https://celer.network/), [Raiden Network](https://raiden.network/)

### Layer-2 Rollups

Layer-2 rollups are of two types: 

* Optimistic rollups  
* ZK-Rollups 

Both are “true layer-2 solutions," meaning they can execute a large volume of transactions at high speeds and low costs while verifying this bundle of transactions on layer-1. 

With Optimistic rollups, we “optimistically assume” that transactions executed on the rollup are authentic and accurate. Unless challenged as fraudulent, these transactions get “rolled up” and submitted to layer-1. These rollups are “optimistic” because these bundles of transactions are considered “innocent until proven guilty.” Fraudulent transactions must be established by fraud proofs that challenge the validity of the transactions. Such a challenge must be submitted within seven days of the transaction. 

Optimistic Rollups examples: [Arbitrum](https://arbitrum.io/), [Base](https://www.base.org/), [Celo](https://celo.org/), [Optimism](https://www.optimism.io/)

ZK-Rollups uses [zero-knowledge proofs](https://chain.link/education/zero-knowledge-proof-zkp) to bundle transactions and submit a proof of validity to Ethereum, ensuring scalability and security.

ZK-Rollups examples: [Loopring](https://loopring.org/), [zkSync](https://zksync.io/)