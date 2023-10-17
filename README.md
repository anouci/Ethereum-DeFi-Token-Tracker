## Ethereum DeFi Token Tracker 📊🌐

A specialized tool tailored for DeFi enthusiasts on Ethereum. Seamlessly track, analyze, and categorize your DeFi ERC20 tokens, ensuring you're always on top of your decentralized finance game.

![DeFi/Mobula Logo](https://i.imgur.com/v4J2tK6.png)

---

## Table of Contents 📖

- [Features](#features-)
- [Usage](#usage-)
- [Setup Guide](#setup-guide-)
- [API Reference](#api-reference-)

---

## Features ✨

- **DeFi Token Insights:** Quick access to performance metrics of your ERC20 DeFi tokens.
  
- **Category Filters:** Filter and sort tokens based on DeFi sectors – lending, DEX, stablecoins, yield farming, etc.
  
- **Alerts & Thresholds:** Set custom alerts based on token performance or market movements.

---

## Usage 💡

1. Input your Ethereum-compatible wallet address.
2. Browse and analyze your DeFi ERC20 tokens.
3. Apply sector filters to narrow down your token view.
4. Customize alerts to stay informed about significant token metrics or price changes.

---

## Setup Guide 🖥️

### 1. **Framework & Base:**
   - Use a Node.js environment, incorporating the Express.js framework.
   - Utilize a frontend framework like React for dynamic and responsive UI.

### 2. **Data Fetch & Processing:**
   - Link up with the Mobula API via Axios to pull DeFi ERC20 token information.
   - Parse and categorize tokens based on predefined DeFi sectors.

### 3. **Alerts & Notifications:**
   - Set up a notification mechanism using websockets for real-time alerts.
   - Offer users the ability to define custom alert thresholds.

---

## API Reference 🌐

Our tool leverages the following Mobula API endpoint:

- **Token Holdings:** 
  - **Method:** GET
  - **Endpoint:** `https://api.app-mobula.com/api/1/wallet/portfolio`
  - **Description:** Retrieve all ERC20 token holdings from any EVM-compatible wallets.
  
To delve deeper into the API's specifics, consult the [Mobula API documentation](https://developer.mobula.fi/reference/).

---

### Crafted with ❤️ using [React](https://reactjs.org/) and powered by [Mobula API](https://developer.mobula.fi/).
