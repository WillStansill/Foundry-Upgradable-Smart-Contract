# Foundry UUPS Upgradeable Contracts

This project demonstrates the implementation of **UUPS (Universal Upgradeable Proxy Standard)** upgradeable contracts using **Foundry**. It includes everything from local node deployment, contract testing, to deployment on **Sepolia testnet**.

## 🚀 Features

-   **UUPS Upgradeable Contracts**: Secure and gas-efficient upgradable contracts.
-   **Foundry Deployment**: Deploy contracts locally or to testnets (e.g., Sepolia).
-   **Testing & Coverage**: Includes unit tests and test coverage using Foundry.
-   **Gas Estimation**: Estimate contract deployment gas costs.
-   **Code Formatting**: Automatically format code with `forge fmt`.

## 🛠 Tech Stack

-   **Smart Contracts**: Solidity
-   **Testing & Deployment**: Foundry (Forge, Anvil)
-   **Blockchain**: Ethereum (Sepolia testnet)

## 🚀 Quickstart

1.  **Clone the repository**:

    ```bash
    git clone [https://github.com/yourusername/foundry-upgrades-cu](https://github.com/yourusername/foundry-upgrades-cu)
    cd foundry-upgrades-cu
    ```

2.  **Build the project**:

    ```bash
    forge build
    ```

3.  **Start a local node**:

    ```bash
    make anvil
    ```

4.  **Deploy to the local node**:

    ```bash
    make deploy
    ```

## 🌐 Deploy to Other Networks (e.g., Sepolia)

1.  **Set your environment variables in a .env file**:

    ```
    PRIVATE_KEY: Your wallet's private key (use a key without real funds for development).
    SEPOLIA_RPC_URL: URL of the Sepolia testnet (e.g., from Alchemy).
    ```

2.  **Deploy to Sepolia**:

    ```bash
    make deploy ARGS="--network sepolia"
    ```

## 🧪 Testing

1.  **Run Tests**:

    ```bash
    forge test
    ```

2.  **Test Coverage**:

    ```bash
    forge coverage
    ```

3.  **Debugging Coverage**:

    ```bash
    forge coverage --report debug
    ```

## 💨 Gas Estimation

1.  **Estimate gas costs for deployment**:

    ```bash
    forge snapshot
    ```

    A `.gas-snapshot` file will be generated.

## 🔧 Code Formatting

1.  **Format the code using Foundry’s `forge fmt`**:

    ```bash
    forge fmt
    ```

## 📬 Contact

📧 Email: willstansill@gmail.com

💼 LinkedIn: linkedin.com/in/will-stansill

🐙 GitHub: github.com/yourusername

Secure, gas-efficient upgradeable contracts with Foundry 🚀
