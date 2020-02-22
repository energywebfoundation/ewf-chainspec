# EWF official chainspec repository
Chain specifications for EWF's blockchains.

This repository is used for automatic updates of the live network and must not be moved or deleted.

|      Chain       |                              Checksum                              |   URL   |
| ---------------- |:-----------------------------------------------------------------: | :------ |
| Volta            | `6c83b3f61d171d2742f8f100c2aa95318ef51de336dcadfedc9785e628307998` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/bcec3cbdcb09bef627f97e9f23925e024f035e67/Volta.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/bcec3cbdcb09bef627f97e9f23925e024f035e67/Volta.json) |
| EnergyWebChain   | `955231dd8b5720003f68bce7836e1e2a862e6fd054f4f68f9b3ee2802e5ba9d9` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/bcec3cbdcb09bef627f97e9f23925e024f035e67/EnergyWebChain.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/bcec3cbdcb09bef627f97e9f23925e024f035e67/EnergyWebChain.json) |

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
