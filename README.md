# Rate Caster

## Introduction
Rate Caster is a decentralized application (Dapp) built on the BSC blockchain, designed to enhance transparency and trust within the Web3 ecosystem. This directory contains the core application, which includes the website and the smart contracts. The app is built using Scaffold-ETH 2, an open-source toolkit for building Dapps.

## Why Rate Caster?
The Web3 space is rapidly growing with numerous Dapps available to users. However, this vast array often leaves users overwhelmed and uncertain about the security, reliability, and trustworthiness of these applications. Rate Caster addresses this challenge by leveraging the BNB Attestation Service (BAS), providing a platform where community feedback leads the way in determining the trustworthiness of Dapps and their decisions.

## Features

### Website
* **Home Page**: Displays a list of registered Dapps along with their community ratings. Users can search and filter through the list to find applications of interest.
* **Dapp Registration**: Allows users to register new Dapps on the platform, ensuring the database is continually updated with the latest applications.
* **Dapp Rating and Reviews**: Users can leave detailed reviews and rate Dapps, contributing to the overall trust score of each application.
* **My Reviews**: Users can view and manage their review history, with options to update or delete their past contributions.
* **Profile Management**: Users can link their wallet addresses to enhance review credibility and manage their platform identity.
## Quickstart

To get started with the Rate Caster application, follow the steps below:

1. **Clone this repository & install dependencies**

    ```bash
    git clone https://github.com/Rainbow1nTheDark/RateCaster.git
    cd RateCasterDapp
    yarn install
    ```

2. **Run a local network**

    In the first terminal, start a local Ethereum network using Hardhat:

    ```bash
    yarn chain
    ```

3. **Deploy the test contract**

    In a second terminal, deploy the test smart contract to the local network:

    ```bash
    yarn deploy
    ```

4. **Start the NextJS app**

    In a third terminal, start your NextJS app:

    ```bash
    yarn start
    ```

    Visit your app on: [http://localhost:3000](http://localhost:3000). You can interact with your smart contract using the `Debug Contracts` page.

## Future Directions

We believe in decentralized social applications and will be focusing on integrating and mapping Farcaster IDs to provided reviews. This will allow us to see Warpcaster profiles attached to the reviews, enhancing credibility and trust.

## Contact Us

For support or further inquiries, reach us at [@crypto_fencer](https://twitter.com/crypto_fencer) / [#0xbuilders](https://0xbuilders.org) or by email at [web3enthusiast@icloud.com](mailto:web3enthusiast@icloud.com).

Testnet:
Resolver: 0x879CB3144def6047d1c3eA9784E82932d55Ebe67
Schema: 0x0beb97f79e873b717add4df7d5d32bed7f19ba0ebdb81b66212048fd12ca89ba
RatingSystem: 0x8fE2F121BBBa62AE00cbF34d4B58a16221e07c57

Mainnet:
Resolver 0x5e905F77f59491F03eBB78c204986aaDEB0C6bDa
Schema: 0x0beb97f79e873b717add4df7d5d32bed7f19ba0ebdb81b66212048fd12ca89ba
RatingSystem: 0x708FBBB40323780b7E29537F25804D10b9168474