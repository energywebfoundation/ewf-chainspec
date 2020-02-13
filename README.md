# EWF official chainspec repository
Chain specifications for EWF's blockchains.

This repository is used for automatic updates of the live network and must not be moved or deleted.

|      Chain       |                              Checksum                              |   URL   |
| ---------------- |:-----------------------------------------------------------------: | :------ |
| Volta            | `42131b445f04e07579880c8f58148eab1973be7f337536a0343bd44e0e0a40d8` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/4f0c2cf8eb0fe5735873d0491916ddfd6e8ef94c/Volta.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/4f0c2cf8eb0fe5735873d0491916ddfd6e8ef94c/Volta.json) |
| EnergyWebChain   | `bb38110e12a6f88a5f75e35a27ac640581df3ca636c32781b9108094e73f2e17` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/4f0c2cf8eb0fe5735873d0491916ddfd6e8ef94c/EnergyWebChain.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/4f0c2cf8eb0fe5735873d0491916ddfd6e8ef94c/EnergyWebChain.json) |

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
