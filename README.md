# EWF official chainspec repository

Chain specifications for EWF's blockchains, Volta and Energy Web Chain.

This repository is used for automatic updates of the live network and must not be moved or deleted.

|      Chain       |                              Checksum                              |   URL   |
| ---------------- |:-----------------------------------------------------------------: | :------ |
| Volta            | `5f897743eaa1a6d901c377d1b7a8a385ec836c7588cf11a1b6c72172c5fdfc37` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/Volta.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/Volta.json) |
| EnergyWebChain   | `2f4b9138c08f9048cbdd3c3296d0f21cfb7ac30704db626d06440379459bedec` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/EnergyWebChain.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/EnergyWebChain.json) |

## Maintainers

**Primary**: EWF DevOps (<devops@energyweb.org>)

## Quickstart

Connect to the Energy Web Chain using the latest stable version of OpenEthereum(Previously Parity Ethereum):

```shell
openethereum --chain "EnergyWebChain.json"
```

To connect to the Volta TEST network, type:

```shell
openethereum --chain "Volta.json"
```

Connect to the Energy Web Chain using the latest stable version of Nethermind:

```shell
nethermind -c energyweb
```

To connect to the Volta TEST network, type:

```shell
nethermind -c volta
```

## How to verify checksum

```shell
openssl dgst -sha256 path/to/your/chainspec.json
```
