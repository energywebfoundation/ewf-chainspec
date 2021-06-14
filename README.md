# EWF official chainspec repository
Chain specifications for EWF's blockchains.

This repository is used for automatic updates of the live network and must not be moved or deleted.

|      Chain       |                              Checksum                              |   URL   |
| ---------------- |:-----------------------------------------------------------------: | :------ |
| Volta            | `4dc9b793b372c532b0fe04ff94f8bbeeb1cc2772a94418084a0870aac6103f38` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/7a5f72a16566d50b4f35a9884c621e9fe6c6c08a/Volta.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/7a5f72a16566d50b4f35a9884c621e9fe6c6c08a/Volta.json) |
| EnergyWebChain   | `667f48e8d3cda708ad4502ebdec1fff612779abd534bf57224d71bddcdfeb2da` | [https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/7a5f72a16566d50b4f35a9884c621e9fe6c6c08a/EnergyWebChain.json](https://raw.githubusercontent.com/energywebfoundation/ewf-chainspec/7a5f72a16566d50b4f35a9884c621e9fe6c6c08a/EnergyWebChain.json) |

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
