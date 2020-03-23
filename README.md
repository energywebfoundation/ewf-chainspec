# EWF official chainspec repository
Chain specifications for EWF's blockchains.

This repository is used for automatic updates of the live network and must not be moved or deleted.

|      Chain       |                              Checksum                              |   URL   |
| ---------------- |:-----------------------------------------------------------------: | :------ |
| Volta            | `ccfcc287b329c0660840215c8d4be7546b9ef9f4636ca32505a715d6323684a5` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/7a5f72a16566d50b4f35a9884c621e9fe6c6c08a/Volta.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/7a5f72a16566d50b4f35a9884c621e9fe6c6c08a/Volta.json) |
| EnergyWebChain   | `47877ba58dd6238ae114b2c740eadf968d4b593a06f30cd8f73310ead9a5810d` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/7a5f72a16566d50b4f35a9884c621e9fe6c6c08a/EnergyWebChain.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/7a5f72a16566d50b4f35a9884c621e9fe6c6c08a/EnergyWebChain.json) |

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
