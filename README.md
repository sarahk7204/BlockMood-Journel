# 🌈 BlockMood Journal dApp

A simple decentralized application (dApp) built with **Solidity**, **Ethers.js**, and **MetaMask** on the **Sepolia Testnet**.  
Users can record their daily moods on the blockchain and view their personal mood history.

---

## 📜 Smart Contract

**Name:** `BlockMoodJournal`  
**Network:** Sepolia Testnet  
**Contract Address:** `0xYOUR_CONTRACT_ADDRESS_HERE`

### Key Functions
| Function | Type | Description |
|-----------|------|-------------|
| `logMood(string _mood)` | Write | Logs a new mood with timestamp |
| `getMyMoods()` | Read | Returns all moods logged by the sender |
| `getLatestMood(address _user)` | Read | Fetches the latest mood for a user |
| `clearMyMoods()` | Write | Deletes all moods of the sender |

---

## 💻 Frontend Setup

### Requirements
- MetaMask extension installed in Chrome
- Ethers.js (included via CDN)
- Sepolia testnet account with test ETH

### Steps to Run Locally
1. Clone or download this repository.  
2. Open a terminal inside the folder.  
3. Run a simple local server:
   ```bash
   python -m http.server 5500
