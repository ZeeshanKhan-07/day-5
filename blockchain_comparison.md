# Blockchain Platform Comparison

## 📊 Comparison Table (Simplified)

| Blockchain Name     | Type       | Consensus      | Permission   | TPS (Speed)       | Smart Contract | Token Support |
|---------------------|------------|----------------|--------------|-------------------|----------------|----------------|
| **Ethereum**        | Public     | PoS            | Open         | ~30 TPS (+L2)     | Yes (Solidity) | Native (ETH)   |
| **Hyperledger Fabric** | Private | Pluggable      | Permissioned | 1000+ TPS         | Yes (Go/Java/JS)| No             |
| **R3 Corda**        | Consortium | Notary-based   | Permissioned | 170+ TPS approx.  | Yes (Kotlin/Java)| No             |

---

## 📌 Platform Details

### 🔷 Ethereum
- **Use Cases:** Decentralized apps (dApps), NFTs, DeFi
- **Consensus:** Proof of Stake (PoS)
- **Smart Contracts:** Yes — written in Solidity
- **Token:** Native support (ETH)
- **Notable Feature:** Ethereum Virtual Machine (EVM), global adoption
- **Limitations:** Lower TPS (solved via Layer 2 solutions)

---

### 🔷 Hyperledger Fabric
- **Use Cases:** Enterprise systems, supply chain management
- **Consensus:** Pluggable (e.g., Raft, Kafka)
- **Smart Contracts:** Yes — Chaincode in Go, Java, JavaScript
- **Token:** No native token
- **Notable Feature:** Modular architecture, private transactions
- **Strength:** High performance, permissioned access

---

### 🔷 R3 Corda
- **Use Cases:** Financial services, inter-bank settlements
- **Consensus:** Notary-based consensus
- **Smart Contracts:** Yes — Kotlin and Java
- **Token:** No native token
- **Notable Feature:** Point-to-point data exchange, legal agreement modeling
- **Designed For:** Known participants in a trusted network

---

## 📝 Short Report

This comparison highlights Ethereum (Public), Hyperledger Fabric (Private), and R3 Corda (Consortium) blockchains. 

**Ethereum** is ideal for public-facing dApps, offering open access and native token support, though it suffers from relatively low TPS without scaling solutions.

**Hyperledger Fabric** is suited for enterprise use, offering high throughput and customizable modules with strict permission control, but lacks native token capabilities.

**R3 Corda** is best for financial applications between trusted parties. It emphasizes privacy and legal compliance, using smart contracts in Java/Kotlin, and supports selective data sharing.

### ✅ Platform Choice Summary

- 🟢 **Decentralized App:** Ethereum — global reach, token, smart contract support  
- 🟢 **Supply Chain Network:** Hyperledger Fabric — private, scalable, enterprise-ready  
- 🟢 **Inter-Bank App:** R3 Corda — secure, private, tailored for finance  
