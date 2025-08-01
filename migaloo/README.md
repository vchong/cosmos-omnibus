# Migaloo

| | |
|---|---|
|Version|`v5.0.0`|
|Binary|`migalood`|
|Directory|`.migalood`|
|ENV namespace|`MIGALOOD`|
|Repository|`https://github.com/White-Whale-Defi-Platform/migaloo-chain`|
|Image|`ghcr.io/akash-network/cosmos-omnibus:v1.2.23-migaloo-v5.0.0`|

## Examples

- Run on Akash with the [example deploy.yml](./deploy.yml)
- Run with Docker using the [example docker-compose.yml](./docker-compose.yml)

## Chain information

The [Cosmos Chain Registry](https://github.com/cosmos/chain-registry) publishes [up to date chain info](https://raw.githubusercontent.com/cosmos/chain-registry/master/migaloo/chain.json) for Migaloo.

This will be used automatically unless overridden with the `CHAIN_JSON` variable (use `0` to disable).

## Polkachu Chain Services

[Polkachu's Chain Services](https://www.polkachu.com/networks/migaloo) make bootstrapping a node extremely easy. They provide live peers, seeds, statesync, addrbooks and pruned snapshots among other features.

The following configuration is available for Migaloo nodes. [See the documentation](../README.md#polkachu-services) for more information.

|Variable|Value|
|---|---|
|`P2P_POLKACHU`|`1`|
|`P2P_SEEDS_POLKACHU`|`1`|
|`P2P_PEERS_POLKACHU`|`1`|
|`STATESYNC_POLKACHU`|`1`|
|`ADDRBOOK_POLKACHU`|`1`|

Polkachu also provide pruned snapshots for Migaloo. Find the [latest snapshot](https://polkachu.com/tendermint_snapshots/migaloo) and apply it using the `SNAPSHOT_URL` variable.
