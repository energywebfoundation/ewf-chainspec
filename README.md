# EWF official chainspec repository

Chain specifications for EWF's blockchains.

This repository is used for automatic updates of the live network and must not be moved or deleted.

|      Chain       |                              Checksum                              |   URL   |
| ---------------- |:-----------------------------------------------------------------: | :------ |
| Volta            | `2c2d73850c209de89b1ef55e329b59661a4047cae340d44b343fc075c602f976` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/Volta.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/Volta.json) |
| EnergyWebChain   | `e3ef22b27f9976df34f6e7dde92fbc8045da641a3259caee87a78cb0957387e7` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/EnergyWebChain.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/EnergyWebChain.json) |

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
