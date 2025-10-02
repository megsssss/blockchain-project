# blockchain-project
## TradeTrust - Secure Cross-Border Trade Platform

TradeTrust is a blockchain-based platform for facilitating secure, transparent, and compliant cross-border trade agreements, with a focus on integrating Environmental, Social, and Governance (ESG) data and adhering to WTO standards. It is developed for the NFC4 hackathon.

### Features

  * **Smart Contract Integration:** Utilizes Ethereum smart contracts (`TradeAgreement.sol`) for immutable and verifiable trade lifecycle management.
  * **Decentralized Identity:** Implements role-based access control with an `IdentityRegistry` for platform participants (Admin, Exporter, Importer, Customs).
  * **Trade Lifecycle:** Supports key stages of a trade: creation, funding, shipment update, and completion.
  * **ESG & Compliance:** Allows for the inclusion of ESG (Environmental, Social, and Governance) data and is designed with WTO standards in mind to generate compliance reports.
  * **Frontend UI:** A React application using `wagmi` and `RainbowKit` for a seamless web3 experience, allowing users to interact with the deployed smart contracts.

###  Technologies

  * **Smart Contracts:** Solidity
  * [cite\_start]**Blockchain Framework:** Hardhat, including `hardhat-deploy`, `hardhat-gas-reporter`, and `solidity-coverage`[cite: 4].
  * **Frontend:** React, using Vite
  * **Web3 Libraries:** `wagmi`, `ethers`, `RainbowKit`
  * **Language:** JavaScript/TypeScript (in various dependencies)


#### Prerequisites

  * Node.js (v16 or higher)
  * MetaMask browser extension




[cite\_start]This project is licensed under the MIT License[cite: 1].
