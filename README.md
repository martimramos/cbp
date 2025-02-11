# Certified Bitcoin Professional (CBP) Study Guide

[Source: CryptoCurrency Certification Consortium (C4)](https://cryptoconsortium.org/certifications/cbp/)

---

## Table of Contents

1. [Introduction to Bitcoin](#introduction-to-bitcoin)
2. [Fundamental Concepts of Money](#fundamental-concepts-of-money)
3. [Bitcoin's Historical Timeline](#bitcoins-historical-timeline)
4. [Bitcoin's Economic Principles](#bitcoins-economic-principles)
5. [Cryptography in Bitcoin](#cryptography-in-bitcoin)
6. [Bitcoin Transactions and the Blockchain](#bitcoin-transactions-and-the-blockchain)
7. [Bitcoin Mining](#bitcoin-mining)
8. [Bitcoin Wallets](#bitcoin-wallets)
9. [Bitcoin Community and Governance](#bitcoin-community-and-governance)
10. [Security and Risk Management](#security-and-risk-management)

---

## Introduction to Bitcoin

### Centralized vs. Decentralized Ledgers

#### Centralized Ledgers:
- Internal and external reconciliation required.
- No restrictions imposed by design.
- Single point of failure/control.
- Requires a middleman for transactions.
- Actions are performed on behalf of fund holders.
- No inherent backup protection.

#### Decentralized Ledgers:
- Transactions are trustless and verified via cryptographic proof.
- No central authority or middleman required.
- No single point of failure.
- Distributed consensus ensures network integrity.
- Immutable and transparent record of transactions.

---

## Fundamental Concepts of Money

### Functions of Currency:
- **Medium of Exchange**: Facilitates trade.
- **Store of Value**: Retains purchasing power over time.
- **Unit of Account**: Standard measurement for valuing goods/services.

---

## Bitcoin's Historical Timeline

- **2007** – Satoshi Nakamoto conceptualizes Bitcoin.
- **2008** – Bitcoin whitepaper released, addressing double-spending problem.
- **2009** – Bitcoin network launched, first transaction between Satoshi and Hal Finney.
- **2010** – First real-world Bitcoin transaction (10,000 BTC for pizza).
- **2011** – Bitcoin surpasses $1 USD; first Bitcoin price bubble.
- **2012** – Bitcoin Foundation formed to standardize protocol development.
- **2013** – Market cap surpasses $1 billion USD.

---

## Bitcoin's Economic Principles

### Supply and Demand
- **Fixed Supply:** 21 million BTC hard cap.
- **Scarcity:** Anything scarce can be money if people agree to use it.
- **Mining Rewards:** BTC supply halves roughly every four years.

---

## Cryptography in Bitcoin

### Hash Functions
- **SHA-256 (Secure Hash Algorithm 256-bit)** ensures security.
- **One-way mathematical function:** Input cannot be derived from output.

### Encryption Methods

#### Asymmetric Encryption (Public-Key Cryptography):
- More secure and used in digital signatures.
- Examples: SSL/TLS, Bitcoin addresses.

#### Symmetric Encryption:
- Same key for encryption and decryption.
- Examples: AES, DES, Blowfish.

### Digital Signatures in Bitcoin
- **Ensures non-repudiable transactions.**
- **Bitcoin wallets generate public/private key pairs.**
- **Transactions are signed with a private key and verified with a public key.**

---

## Bitcoin Transactions and the Blockchain

### Components of a Bitcoin Transaction
- **Input:** Sending address.
- **Amount:** BTC being transferred.
- **Output:** Receiving address.
- **Fees:** Incentive for miners to validate transactions.
- **Verification:** Miners confirm transactions before adding them to the blockchain.

### Bitcoin Blockchain
- **Public ledger of all Bitcoin transactions.**
- **Transactions are added in chronological order.**
- **Each block has a 1MB data limit.**

---

## Bitcoin Mining

### Purpose of Mining
- Adds transactions to the blockchain.
- Secures the network.
- Distributes new BTC through block rewards.

### Mining Algorithm
- **SHA-256 Proof-of-Work (PoW).**

### Mining Hardware
- **CPU Mining:** Outdated.
- **GPU Mining:** More efficient but largely replaced.
- **FPGA (Field Programmable Gate Array):** Custom mining solutions.
- **ASIC (Application-Specific Integrated Circuit):** Industry standard, highly efficient.

### Mining Pools vs. Solo Mining
- **Pools:** Frequent but smaller rewards, shared among miners.
- **Solo:** Less frequent but full block rewards.

---

## Bitcoin Wallets

### Wallet Types
- **Web-Based Wallets** (e.g., Exchange wallets).
- **Paper Wallets** (Offline storage).
- **Hardware Wallets** (e.g., Ledger, Trezor).
- **Multi-Sig Wallets** (Require multiple keys to authorize transactions).
- **Hot Wallets** (Connected to the internet, convenient but riskier).
- **Cold Wallets** (Offline storage, more secure).

### Deterministic Wallets (BIP32)
- Generate multiple private keys from a single master seed.

### Secure Payment Protocol (BIP70)
- Improves security and refund capabilities.

---

## Bitcoin Community and Governance

### Key Participants
- Users, Exchanges, Developers, Educators, Miners, Investors.

### Bitcoin Improvement Proposals (BIPs)
- Developers propose protocol changes, miners vote (~55% consensus needed).

### Blockchain Explorers
- Provide a transparent view of all BTC transactions.

---

## Security and Risk Management

### 51% Attack
- If a miner or group controls >50% of network hash rate, they could:
  - Prevent specific transactions.
  - Reverse their own transactions.
  - Block other miners from confirming transactions.

### Secure Key Management
- **Private keys should never be shared.**
- **Backup private keys securely.**
- **Use multi-signature wallets for added security.**

### UTXOs (Unspent Transaction Outputs)
- Represents BTC available to spend at an address.

---

### Donation
If you found this guide helpful, consider donating a Satoshi! :D

- **BTC:** `1CUPMEpQtsEXLuudiEoRXpYNbCsh9A5Vvg`
- **ETH:** `0xedFd8dE06aAB43252864F1d9dA6fdd34C562a117`
- **LTC:** `La4MiQGGA9PYTadTbczuuRfyW9jt8LZTE4`

---

This document is designed as a **concise and structured** study guide for the **Certified Bitcoin Professional (CBP)** exam.
It covers core concepts, key definitions, security risks, and practical elements of Bitcoin use, ensuring a **solid foundation for certification success.**

