# Public Fullnode instruction

Hey all, thank you for interested in running a fullnode on AIT3! Please follow the instructions to:

1. Setup you fullnode following the [same instruction](https://aptos.dev/nodes/full-node/fullnode-for-devnet) as running fullnode on devnet, use the `testnet` branch and `testnet` docker image tag instead of the devnet one. 
2. Replace the genesis.blob and waypoint from the above instruction to the files hosted in this repo.
3. Make sure you start your fullnode with static identity. See instruction [here](https://aptos.dev/nodes/full-node/network-identity-fullnode)

For bootstrapping your fullnode node:
- The docker image tag to use is `testnet_b2228f286b5fe7631dee62690ae5d1087017e20d`
- Sha256 for the docker image is `050b644b13cf74a02edfeed3b2416baf269b65f068198a4e10cfa4e58c1b9b0a`
- Sha 256 for genesis blob is `307f6846179c257badc4e50fbf1d7d4d332b82046e6ff297bff087c5a8efe68f`
- Waypoint is `0:96d6b0c072ae759ee3d071d1b41a87b3bc983eb852a805e7054482235eace373`
- CLI version `0.3.2` https://github.com/aptos-labs/aptos-core/releases/tag/aptos-cli-v0.3.2


# Validator instruction

Hey all, congratulation on getting selected as validator node for AIT3! Please follow the instructions to:

1. Initialize your staking pool https://aptos.dev/nodes/ait/steps-in-ait3#initialize-staking-pool
2. Join the AIT3 network. https://aptos.dev/nodes/ait/connect-to-testnet

For bootstrapping your validator node:
- The docker image tag to use is `testnet_b2228f286b5fe7631dee62690ae5d1087017e20d`
- Sha256 for the docker image is `050b644b13cf74a02edfeed3b2416baf269b65f068198a4e10cfa4e58c1b9b0a`
- Sha 256 for genesis blob is `307f6846179c257badc4e50fbf1d7d4d332b82046e6ff297bff087c5a8efe68f`
- Waypoint is `0:96d6b0c072ae759ee3d071d1b41a87b3bc983eb852a805e7054482235eace373`
- Aptos node peer ID is `f326fd30` if you want to check your connection.
- CLI `0.3.2` for ait3 https://github.com/aptos-labs/aptos-core/releases/tag/aptos-cli-v0.3.2

Let us know if you have any questions, and looking forward to see your node coming online!
