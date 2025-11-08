# Avalanche Workshop Template (Go & EVM)

This repository is configured as a GitHub Codespaces Template to provide you with a zero-setup development environment pre-loaded with tools for both the native Go client and the EVM (C-Chain) development.

No need to install Go, Foundry, or the AvalancheGo client locally—everything works instantly in your browser!

---

## Tech Stack & Tools Included

| Technology | Purpose | Version Included |
| :--- | :--- | :--- |
| **Go** | The core language for the AvalancheGo client and building custom Subnets. | Latest Stable |
| **Foundry** | The Ethereum development toolchain (Forge, Cast, Anvil) for C-Chain development. | Latest Stable |
| **Node.js / npm** | For using Javascript/Typescript web3 libraries (e.g., Ethers.js, Web3.js). | LTS |
| **AvalancheGo** | The Avalanche client, installed for quick access to tools. | Latest Stable |

---

## Getting Started

Follow these two simple steps to launch your pre-configured environment in the cloud:

### 1. Open in Codespace

Click the green **"Code"** button and select **"Create codespace on main"** from the dropdown menu.

Alternatively, click this badge:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/YOUR-GITHUB-ORG/avalanche-workshop-template)

> **Note:** GitHub will create a fresh copy of this repository in a powerful cloud machine, which might take 1–2 minutes for the initial setup and dependency installation.

### 2. Verify Your Environment

Once the VS Code editor opens in your browser, the terminal should be visible at the bottom.

Run these commands to confirm all tools are correctly installed:

```bash
# Verify the core Go environment is ready
go version

# Verify the EVM tooling is ready
forge --version
```

## Clean Up: Deleting Your Codespace

Your Codespace is a cloud-hosted environment. While generous usage is free for all new accounts, we recommend deleting your Codespace once you are fully finished to avoid incurring unexpected charges.

Please follow this step to stop your cloud environment.

1.  Go to your codespaces list by navigating to: [https://github.com/codespaces](https://github.com/codespaces)

2.  Locate and delete the codespace:
    * Find the Codespace named for your workshop (e.g., `avalanche-workshop-template...`).
    * Click the **three dots ($\dots$)** on the right side.
    * Select **Delete**.