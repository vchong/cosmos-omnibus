# Chihuahua

| | |
|---|---|
|Version|`v9.0.5`|
|Binary|`chihuahuad`|
|Directory|`.chihuahuad`|
|ENV namespace|`CHIHUAHUAD`|
|Repository|`https://github.com/ChihuahuaChain/chihuahua`|
|Image|`ghcr.io/akash-network/cosmos-omnibus:v1.2.23-chihuahua-v9.0.5`|

## Examples

- Run on Akash with the [example deploy.yml](./deploy.yml)
- Run with Docker using the [example docker-compose.yml](./docker-compose.yml)

## Chain information

The [Cosmos Chain Registry](https://github.com/cosmos/chain-registry) publishes [up to date chain info](https://raw.githubusercontent.com/cosmos/chain-registry/master/chihuahua/chain.json) for Chihuahua.

This will be used automatically unless overridden with the `CHAIN_JSON` variable (use `0` to disable).

## Polkachu Chain Services

[Polkachu's Chain Services](https://www.polkachu.com/networks/chihuahua) make bootstrapping a node extremely easy. They provide live peers, seeds, statesync, addrbooks and pruned snapshots among other features.

The following configuration is available for Chihuahua nodes. [See the documentation](../README.md#polkachu-services) for more information.

|Variable|Value|
|---|---|
|`P2P_POLKACHU`|`1`|
|`P2P_SEEDS_POLKACHU`|`1`|
|`P2P_PEERS_POLKACHU`|`1`|
|`STATESYNC_POLKACHU`|`1`|
|`ADDRBOOK_POLKACHU`|`1`|

Polkachu also provide pruned snapshots for Chihuahua. Find the [latest snapshot](https://polkachu.com/tendermint_snapshots/chihuahua) and apply it using the `SNAPSHOT_URL` variable.
