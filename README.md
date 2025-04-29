# 🧾 Pinocchio Escrow Program

This project is a minimal **Escrow smart contract** built using the **Pinocchio framework** on Solana. It demonstrates how to create a trustless, conditional token exchange mechanism without relying on the SDK or Anchor.

---

## 🎯 Purpose

The goal of this repo is to **teach and illustrate** how escrow logic works on-chain using low-level tools. It’s intentionally kept small and focused, ideal for developers looking to learn how to:

- Write secure, conditional programs in Rust
- Use Pinocchio instead of Anchor
- Manage program-derived accounts (PDAs) manually

---

## ⚙️ Features

- Create token offers (escrow initialization)
- Accept and fulfill offers
- Cancel open offers
- Safe token transfers with account validation
- Manual PDA generation and signature checks

---


## 🧪 Usage

### Prerequisites

- [Rust](https://www.rust-lang.org/)
- [Solana CLI](https://docs.solana.com/cli)
- [Mollusk](https://github.com/kevinheavey/mollusk) (testing framework for Pinocchio)
- [Pinocchio](https://github.com/anza-xyz/pinocchio)

### Build

```
cargo build-bpf
```

### Run Tests

```
cargo test
```

## 🛠 Tech Stack

Solana – On-chain program runtime
Pinocchio – Lightweight Solana development library
Mollusk – Rust-native testing for Solana programs
Rust – Core language for program logic

## 📜 License
MIT License




