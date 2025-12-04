# 🐢 Tortie Chain  
### An open-source, developer-friendly blockchain built with the Cosmos SDK

Tortie Chain is a sovereign Layer-1 blockchain designed as an **open platform for developers**, researchers, and open-source contributors.  
Anyone can build, deploy, and run decentralized applications, modules, or tooling on top of the Tortie ecosystem.

---

## ✨ Features
- **Cosmos SDK-based** → modular, secure, battle-tested  
- **Tendermint/CometBFT consensus** → instant finality  
- **Built for developers** → easy to run, deploy, and extend  
- **Open source** → MIT/Apache license (choose one)  
- **Local, testnet, and mainnet ready**  
- **REST + gRPC APIs enabled**  
- **Upgradeable** → seamless network upgrades  
- **Future support for CosmWasm & smart contracts**  

---

## 🚀 Quick Start

### Requirements
- Go 1.22+  
- Ignite CLI 29+  
- Linux/macOS/WSL2 (Windows)

### Clone the repository

```
git clone https://github.com/tarunharit/tortie-chain.git
cd tortie-chain
```

### Build the binary

```
ignite chain build
```

You should now have the `tortied` binary installed.

---

## 🧪 Run a Local Node

```
ignite chain serve
```

This starts a full blockchain node with:

- RPC: http://localhost:26657  
- REST API: http://localhost:1317  
- Faucet: http://localhost:4500  

---

## 🔧 Interact with the Chain

### Check balances:
```
tortied q bank balances <address>
```

### Send a transaction:
```
tortied tx bank send <from> <to> 100utortie --fees 5000utortie -y
```

---

## 🧱 Directory Structure

```
app/         → Main application wiring  
cmd/         → Binary entry points  
x/           → Custom modules  
proto/       → Protobuf definitions  
config.yml   → Ignite chain configuration  
```

---

## 🛠 Planned Roadmap
- Public **testnet**  
- Explorer + indexer  
- CosmWasm smart contracts  
- JS/TS/Python SDKs  
- Developer documentation portal  
- Grants + open-source funding  
- Public mainnet launch  

---

## 🤝 Contributing
Tortie Chain is an open-source project and welcomes contributions of all kinds:

- Modules  
- Tools  
- Documentation  
- Bug fixes  
- Tutorials  

Please open an issue or pull request to get started.

---

## 📄 License
Copyright © 2025  
Licensed under **Apache 2.0** (recommended) or **MIT**.

---

## 🌐 Links
Website (coming soon)  
Documentation (coming soon)  
Explorer (coming soon)

---

### 🐢 Tortie Chain — Built for developers. Built for the open-source future.
