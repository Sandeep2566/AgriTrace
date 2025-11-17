
# 🏷️ AgriTrace  
### **The Financial Justice & Transparent Harvest Platform**

---

## 🚀 Project Overview
**AgriTrace** is a blockchain-powered agricultural traceability platform designed to bring **financial fairness**, **trust**, and **transparency** to the supply chain.  
Using Smart Contracts, the platform ensures **instant payments to farmers**, while QR-based traceability provides **complete visibility** of the product journey for consumers.

- **Hackathon Goal:** Build an MVP demonstrating instant smart-contract-based payments + QR code traceability.  
- **Core Focus:** Financial justice, supply chain transparency, and mobile-first adoption.

---

## 💡 Problem Statement

### 1️⃣ **Farmer Exploitation**  
- Delayed payments (60–90 days)  
- Middlemen capture most of the profit  

### 2️⃣ **Consumer Mistrust**  
- No verifiable proof of origin  
- No transparency in pricing or product quality  

---

## ✨ Unique Selling Proposition (USP)

### ✔ **Instant Payment via Smart Contracts**  
Payments are automatically released to farmers after product verification and ownership transfer.

### ✔ **Transparent Price Journey**  
Consumers can scan the QR code to view:  
- Product origin  
- All transfer events  
- Immutable **price history**  

### ✔ **Low-Cost, Mobile-First Adoption**  
Optimized for QR codes and simple smartphones used by smallholder farmers.

---

## 🛠️ Technology Stack (MVP)

| Component             | Technology           | Purpose |
|----------------------|----------------------|---------|
| Blockchain Logic     | Solidity             | Smart Contracts (register, transfer, payment) |
| Local Environment    | Ganache / Truffle    | Ethereum local development |
| Frontend/UI          | React.js / Next.js   | Farmer, Distributor, Consumer dashboards |
| Backend/API          | Node.js (Express)    | Server + Web3 integration |
| Interaction Layer    | Web3.js / Ethers.js  | Linking frontend with blockchain |

---

## 🛣️ Getting Started

### ✔ Prerequisites
- Node.js (v18+)  
- npm (v9+)  
- Ganache (local blockchain)

---

### 🔧 Installation & Setup

#### 1. Clone the Repository
```bash
git clone this repo
cd agritrace
2. Install Dependencies

npm install

3. Start Local Blockchain

Open Ganache

Create a workspace

Copy RPC URL (default: http://127.0.0.1:7545)


4. Deploy Smart Contracts

npx truffle migrate --reset

5. Start Frontend

npm run start

Your app runs at: http://localhost:3000


---

🌟 MVP Features (Golden Path)

👨‍🌾 1. Farmer Module

Enter batch details (ID, quantity, price)

Writes produce to blockchain

Generates QR Code for traceability


🚚 2. Distributor Module

Scan QR Code

Perform quality check

Trigger ownership transfer

Smart Contract releases instant payment to farmer


🛒 3. Consumer Trace Page

Scan or enter Batch ID

View entire supply chain

Check price history and origin



---

🔮 Future Enhancements

IoT-based automated quality tracking (temp/humidity sensors)

Polygon / L2 Scaling for low gas fees

Full mobile application (Flutter / React Native)

DeFi micro-loans using tokenized produce records



---

👥 Team

Role	Name	Contribution

Blockchain/Backend Lead	[Sandeep Yadav, kurshid alam, Rahul Singh]	Smart Contracts, APIs
Frontend/UX Lead	[Aditya kushwaha]	React UI, QR Code Integration
Product/Pitch Lead	[Sandeep Yadav]	Market research, pitch, demo
