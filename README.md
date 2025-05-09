# BitNun Blockchain Platform

BitNun is a fully self-contained, next-generation Layer 1 blockchain platform built from scratch. It offers real-time mining, smart contracts (BN20/BN721), encrypted wallet system, token sale with direct off-chain payment options, P2P networking, and a hidden CEO admin dashboard for full internal governance — all live and working without simulation or third-party dependencies.

## 🌐 Live Features

- **Custom Blockchain Core** — Genesis block, PoW mining, staking, transaction pool, Merkle tree, consensus validation
- **BTN Token (BN20)** — Mintable/burnable smart contract token with secure transfers
- **Web Wallet System** — Encrypted wallets, HD key gen, transaction signing
- **P2P Network** — WebSocket-based peer sync, node discovery, real-time block broadcast
- **Signup Bonus** — New accounts receive 10 BTN automatically
- **Token Sale** — Direct payment with bank, card, or crypto (admin controlled)
- **Incentives** — Airdrops, staking, referrals, learn-to-earn
- **Admin CEO Dashboard** — Hidden interface to manage everything: token supply, payments, settings, logs

## 💻 Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Tailwind, Framer Motion  
- **Backend**: Node.js, Express, SQLite (Drizzle ORM), WebSocket  
- **Security**: JWT Auth, wallet encryption, hidden admin layer  
- **Hosting**: Runs live on Replit, optionally deployable anywhere

## 📦 Directory Structure

```bash
/bitnun
  /client        # Frontend UI
  /server        # Backend + Blockchain core
  /contracts     # BN20/BN721 smart contracts
  /dashboard     # Admin CEO hidden panel
  /db            # SQLite with Drizzle
  README.md
