# Crowdfunding dApp 🚀

A decentralized crowdfunding platform built on Ethereum, enabling creators to launch fundraising campaigns with multiple tiers, manage contributions, and securely handle funds — powered by **Thirdweb** for seamless blockchain integration.

---

## 📝 Overview

This project consists of two main smart contracts:

- **CrowdfundingFactory**  
  A factory contract that allows users to create their own crowdfunding campaigns dynamically.

- **Crowdfunding**  
  Each deployed campaign contract lets backers fund specific tiers, tracks contributions, and supports withdrawals/refunds based on campaign success.

The frontend is built with React and leverages **Thirdweb SDK** for wallet connection, contract interactions, and deployment.

---

## ⚙️ Features

- Create and manage multiple crowdfunding campaigns
- Define customizable tiers with funding amounts
- Backers can contribute exactly the tier amount
- Automatic campaign state updates: Active, Successful, or Failed
- Secure withdrawal by campaign owner upon success
- Refunds available for failed campaigns
- Pause/resume campaigns and factory contract
- User-friendly dashboard showing your campaigns
- Built with solidity ^0.8.0 and deployed on Sepolia testnet

---

## 🛠️ Tech Stack

- **Smart Contracts:** Solidity (v0.8.x)
- **Blockchain Integration:** [Thirdweb SDK](https://thirdweb.com)
- **Frontend:** React + TypeScript + Tailwind CSS
- **Network:** Sepolia Ethereum Testnet

---

## 🚀 Getting Started

### Prerequisites

- Node.js v16+
- Yarn or npm
- MetaMask or another Ethereum wallet connected to Sepolia

### Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/crowdfunding-dapp.git
cd crowdfunding-dapp
