# WalletConnect using React + Vite

## Usage

1. Go to [WalletConnect Cloud](https://cloud.walletconnect.com) and create a new project.
2. Copy your `Project ID`.
3. Rename `.env.example` to `.env` and paste your `Project ID` as the value for `VITE_PROJECT_ID`.
4. Run `yarn` to install dependencies.
5. Run `yarn dev` to start the development server.

## WalletConnect in React and Vite

This project uses WalletConnect to enable connections with various cryptocurrency wallets such as MetaMask, Trust Wallet, and others. WalletConnect is a protocol for connecting decentralized applications (DApps) to mobile wallets with QR code scanning or deep linking. This makes it easier for users to interact with DApps securely and conveniently.

## wagmi Library

The project also utilizes the `wagmi` library, which provides hooks and utilities for working with Ethereum, and other EVM-compatible chains. It simplifies the process of connecting to Web3 providers, managing wallet connections, and handling blockchain interactions.
