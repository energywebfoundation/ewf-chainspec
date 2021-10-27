# EWF official chainspec repository

Chain specifications for EWF's blockchains, Volta and Energy Web Chain.

This repository is used for automatic updates of the live network and must not be moved or deleted.

|      Chain       |                              Checksum                              |   URL   |
| ---------------- |:-----------------------------------------------------------------: | :------ |
| Volta            | `2c2d73850c209de89b1ef55e329b59661a4047cae340d44b343fc075c602f976` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/Volta.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/Volta.json) |
| EnergyWebChain   | `7c940552f47b50de584260e1d851e8f18b147109de9d68e2a1f1b363c24a4dc9` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/EnergyWebChain.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/EnergyWebChain.json) |

## Maintainers

**Primary**: Adam Nagy (@ngyam)

## Quickstart

Connect to the Energy Web Chain using the latest stable version of Parity Ethereum:

```
parity --chain "EnergyWebChain.json"
```

To connect to the Volta TEST network, type:

```
parity --chain "Volta.json"
```

## How to verify checksum

```
openssl dgst -sha256 path/to/your/chainspec.json
```
