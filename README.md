# EWF official chainspec repository
Chain specifications for EWF's blockchains.

This repository is used for automatic updates of the live network and must not be moved or deleted.

|      Chain       |                              Checksum                              |   URL   |
| ---------------- |:-----------------------------------------------------------------: | :------ |
| Volta            | `1b7b18fb240a11f3d63180d59533a7f449dc936a30ec9c802d704392463f6925` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/Volta.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/Volta.json) |
| EnergyWebChain   | `ac7fd9464f978129dc52d503712706ccd455ede70d799b62297402c9271a7cf1` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/EnergyWebChain.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/master/EnergyWebChain.json) |

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
