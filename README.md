This DApp provides both public and wallet-specific information related to the staking of the Monapepe token on the Monad Testnet. It is built using HTML, CSS, and JavaScript (with ethers.js) and offers the following features:

## Overview

- **Public Dashboard (Read-Only)**
  - **Price of Monapepe (in MON):** Automatically fetched from the Uniswap V2 pool.
  - **Total Staked Value (in MON):** Calculated based on the total staked tokens in the staking contract.
  - **APR:** Computed from an annual reward of 8765 MON.
  - **Auto-Refresh:** This public data is refreshed automatically every 5 seconds without requiring a wallet connection.

- **Wallet Dashboard**
  - **Token Balance**
  - **Your Staked Amount**
  - **Pending Reward**
  - **Staking Interface:** Once you connect your wallet via MetaMask, you can stake, unstake, and claim rewards.
  - **Auto-Refresh:** Wallet-specific data is also updated every 5 seconds.

- **Quick Links**
  - **Telegram:** [https://t.me/themonapepe](https://t.me/themonapepe)
  - **Defined.fi:** [https://www.defined.fi/mon-test/0x4a0a2b293a34c54d0965d23f8131a3d2c0b91290?quoteToken=token1&cache=ce97d&quoteCurrency=TOKEN](https://www.defined.fi/mon-test/0x4a0a2b293a34c54d0965d23f8131a3d2c0b91290?quoteToken=token1&cache=ce97d&quoteCurrency=TOKEN)
  - **nad.fun:** [https://testnet.nad.fun/tokens/0xB31be452692c5d7e2C1c3eD3FbD769a2723e3BEA](https://testnet.nad.fun/tokens/0xB31be452692c5d7e2C1c3eD3FbD769a2723e3BEA)

## Technologies Used

- **HTML/CSS/JavaScript:** For the front-end UI.
- **ethers.js:** To interact with the blockchain.
- **MetaMask:** For wallet connection.
- **Monad Testnet RPC:** Read-only provider using `https://testnet-rpc.monad.xyz` (chain ID 10143).

## Contract Addresses

- **Uniswap V2 Pool:** `0x4a0A2B293A34c54d0965D23f8131A3D2c0b91290`
- **wETH Token:** `0x3bb9AFB94c82752E47706A10779EA525Cf95dc27`
- **Monapepe Token:** `0xB31be452692c5d7e2C1c3eD3FbD769a2723e3BEA`
- **Staking Contract:** `0x9a6F85f4090292eE248B2C999a3E1422B1297177`

## Getting Started

### Prerequisites

- **MetaMask:** Ensure you have MetaMask installed in your browser.
- **Monad Testnet:** Set your MetaMask to the Monad Testnet or use the read-only provider which fetches public data from the RPC endpoint.

### Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
