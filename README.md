# Solana (SolanaCypher)
SolanaWallet

Proposal for an interconnected crypto wallet running on proxy re-encryption network.

The problem: Currently, there exists a vast variety of different wallets with different keys and different addresses. Crypto users will typically use a different wallet/address for each different crypto asset like BTC, ETH, XLM, etc. This can force investors to maintain an unnecessarily high number of different wallets and addresses for each project they have invested in.

The solution: Building a decentralized crypto wallet that allows users to store all the major crypto assets in a single crypto wallet by sending the coins/tokens to a single address (stage I). In the second stage, users will be able to store and trade/swap all the major crypto assets from within this wallet. The third stage will feature token privacy protection by means of applying Ring Signatures.

Solana will be used as the native proxy re-encryption network of the ecosystem to support privaxy. It will be further used to be the centerpiece of the cross-chain wallet that enables the trustless mechanism for cross chain swaps/trading. Inter- as well as intra-chain transactions consume specified amounts of Solana, which is used as security deposit for cross-chain transactions.

Technical implementation: Cross-chain transactions will be accomplished by means of joint anchoring schemes and multi-party computing. Crypto assets are transferred to the NubutuCypherWallet and will be identified accordingly by the wallets validator node. After successfully identifying the asset, a new asset (i.e. a new smart contract) will be created on Solana so that the crypto asset (for instance, BTC or ETH) can be used inside the NubutuCypherWallet wallet.

Once a transaction is successfully sent to the NubutuCypherWallet wallet, the validator node locks the original crypto asset (for instance, BTC or ETH) that has been sent to the wallet while simultaneously creating a new smart contract for the sent crypto asset on Solana.
