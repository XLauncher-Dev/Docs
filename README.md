# XLauncher Docs
Xlauncher is an autonomous agent designed for seamless token deployment. Users can request the deployment of tokens on the Solana blockchain by tagging @Xlauncher on X (formerly Twitter). The service supports efficient, secure token launches tailored for the Solana ecosystem and it will be launched with Pump.fun
## Our Mission
To pioneer AI solutions that align with the principles of decentralization. Inspired by the ethos of crypto, we aim to foster innovation that is transparent, autonomous, and community-driven.
## Getting started with XLauncher
XLauncher allows users to request the deployment of tokens on the Solana blockchain with ease. To use XLauncher, the only requirement is an active X (formerly Twitter) account. Each X account is permitted to request one token deployment per day.
How to Request a Token Deployment:

1. Tag @XLauncher in a Tweet on X.
2. Include the following information in the Tweet:
  - Token Name
  - Token Ticker
  - Optional: Image or GIF

Once the request is submitted, XLauncher will respond with one of the following outcomes:

1. Successful Deployment: XLauncher will reply with a link to the deployed token’s page on Ourwebsite.ai.
2. Clarification Needed: If the request is unclear, XLauncher will respond with follow-up questions to gather the necessary details (token name, ticker, and confirmation to proceed with deployment).

## Token Deployment
After receiving a valid token deployment request, XLauncher deploys an SPL token on Solana by calling the XLauncher.sol contract:

1. Mint the Token:
  - A new SPL token is created and assigned to the deployer’s Solana account.

2. Create a Liquidity Pool:
  - A liquidity pool is created on a Solana DEX (like Raydium or Serum) with an initial market cap (e.g., ~$30k).

3. Provide Liquidity:
  -The minted token is sent to the liquidity pool to provide single-sided liquidity (or token pair liquidity).

## Technology Stack
### Blockchain:
  - Solana: Used to deploy and manage tokens through smart contracts.
### Languages:
  - Rust: For writing smart contracts on Solana.
  - Python: For the AI module that processes commands (like social media inputs).
  - JavaScript (Node.js): For building the backend that connects AI and the blockchain.
  - React: For building the frontend user interface.
### Frameworks:
  - Anchor: A tool to simplify smart contract development on Solana.
  - Express.js: A framework to build the backend APIs for connecting everything.

## Stay Connected
- [X (Twitter)](URL)
- [Website](URL)
- [Telegram](URL)
