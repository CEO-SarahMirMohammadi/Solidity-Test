# Solidity-Test

This repository contains simple Solidity smart contracts for learning and testing purposes, including:

- `exampleToken.sol` — A basic ERC-20 token example.
- `SimpleAuction.sol` — A simple auction contract.

You can run and test these contracts using [Remix IDE](https://remix.ethereum.org/).

---

## How to Run the Contracts in Remix
Follow these steps:

### 1. Open Remix IDE
Go to [https://remix.ethereum.org](https://remix.ethereum.org/) in your browser.

### 2. Create a New File
- Click on the **File Explorers** panel (📁 icon on the left).
- Click **Create New File**.
- Name it exactly like your contract file, e.g., `exampleToken.sol` or `SimpleAuction.sol`.

### 3. Copy & Paste the Code
- Open the `.sol` file from this repository in VS Code.
- Copy the entire Solidity code.
- Paste it into the new file in Remix.

### 4. Compile the Contract
- Click the **Solidity Compiler** panel (🛠️ icon on the left).
- Select the compiler version matching your contract (`^0.8.20` is recommended here).
- Click **Compile `<ContractName>.sol`**.

### 5. Deploy the Contract
- Click the **Deploy & Run Transactions** panel (⚡ icon on the left).
- Choose **JavaScript VM** for testing in a local environment.
- Select your contract from the dropdown menu.
- Click **Deploy**.
- Remix will create a new instance of your contract for testing.

### 6. Interact with the Contract
- Once deployed, you can:
  - Call functions by clicking buttons for each public function.
  - Enter values for payable functions like `bid()` in `SimpleAuction.sol`.
  - Check state variables like `highestBid` or `owner`.

---

## Notes
- Always use Remix for testing before deploying to real Ethereum networks.
- You can modify and experiment with these contracts to better understand Solidity concepts.
- Make sure to save your changes locally before pushing to GitHub.

---

## Resources
- [Remix IDE](https://remix.ethereum.org/)
- [Solidity Documentation](https://docs.soliditylang.org/)
- [ERC-20 Token Standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)

