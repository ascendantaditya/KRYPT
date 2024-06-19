---

# KRYPT

A web3-based APP that allows users to easily send cryptocurrencies from one account to another. Built with Hardhat and Zod integration for enhanced development and validation.

## Tech Stack

- **Frontend:** Vite + React
- **Styling:** Tailwind CSS
- **Smart Contracts:** Solidity
- **Programming Language:** JavaScript

## Features

- Send cryptocurrencies between accounts
- Integration with Web3 for seamless transactions
- Utilizes Hardhat for smart contract deployment and testing
- Schema validation using Zod

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- MetaMask or any Ethereum-compatible wallet

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ascendantaditya/KRYPT.git
   cd KRYPT
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add your environment variables. Example:

   ```
   REACT_APP_INFURA_PROJECT_ID=your_infura_project_id
   ```

4. **Compile smart contracts:**

   ```bash
   npx hardhat compile
   ```

5. **Deploy smart contracts:**

   ```bash
   npx hardhat run scripts/deploy.js --network your_network
   ```

6. **Start the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Connect your Ethereum wallet (e.g., MetaMask).
3. Enter the recipient's address and the amount of cryptocurrency to send.
4. Confirm the transaction.

## Demo



## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

---

Feel free to customize the details according to your specific setup and preferences.
