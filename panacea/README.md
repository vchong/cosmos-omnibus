# Medibloc

| | |
|---|---|
|Version|`v2.2.0`|
|Binary|`panacead`|
|Directory|`.panacea`|
|ENV namespace|`PANACEAD`|
|Repository|`https://github.com/medibloc/panacea-core`|
|Image|`ghcr.io/akash-network/cosmos-omnibus:v1.2.23-panacea-v2.2.0`|

## Examples

- Run on Akash with the [example deploy.yml](./deploy.yml)
- Run with Docker using the [example docker-compose.yml](./docker-compose.yml)

## Chain information

The [Cosmos Chain Registry](https://github.com/cosmos/chain-registry) publishes [up to date chain info](https://raw.githubusercontent.com/cosmos/chain-registry/master/panacea/chain.json) for Medibloc.

This will be used automatically unless overridden with the `CHAIN_JSON` variable (use `0` to disable).
