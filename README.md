# PatronPlus

## Description

PatronPlus is a platform designed to revolutionize creator support by providing a decentralized and censorship-resistant ecosystem. It enables fans and supporters to directly contribute to their favorite creators using cryptocurrencies and other means of support. With PatronPlus, creators can access their funds without worrying about account suspension or deplatforming, as the platform is built on smart contracts deployed to the blockchain network.

## Problem

Existing creator support platforms suffer from centralization and lack of censorship resistance. Creators often face the risk of being suspended or deplatformed, resulting in restricted access to their funds. Moreover, these platforms are not universally accessible, leaving creators in certain regions or countries at a disadvantage.

## Solution

PatronPlus addresses the challenges of centralized platforms by providing a decentralized creator support solution. It empowers fans to support their favorite creators and idols using cryptocurrencies and NFTs. By leveraging smart contracts and blockchain technology, PatronPlus ensures worldwide accessibility for creators and supporters.

## Key Features

- Dashboard: A dedicated space for creators to manage their accounts and track support from their fans.
- Crypto Token Support: Supporters can contribute to creators using cryptocurrencies such as MATIC, DAI, USDT, and USDC.
- NFT Support: Creators can receive support in the form of NFTs, opening up new avenues for interaction and appreciation.
- NFT Marketplace: Creators can sell their own NFTs, allowing fans to collect and engage with their unique digital assets.
- Supporter Rewards: Random rewards powered by Chainlink VRF add an element of surprise and delight for supporters.
- Creator Pages: Each creator has a personalized page to showcase their work, share updates, and connect with their audience.
- Social Profile Integration: Creators can add their social media profiles, enhancing their online presence and visibility.

## Technologies Used

- Solidity: Smart contracts are written in Solidity, ensuring secure and efficient execution on the blockchain.
- Vue.js: The frontend is built with Vue.js, providing an interactive and user-friendly interface for creators and supporters.
- Moralis: Integration with Moralis enables wallet connectivity, interaction with smart contracts, and database management.
- The Graph Protocol: The Graph Protocol is utilized to index and retrieve data from the smart contracts, enhancing efficiency and accessibility.
- Alchemy: Alchemy powers the retrieval of NFT data and metadata for seamless user experiences on PatronPlus.
- IPFS (web3.storage): IPFS is utilized to store creators' profile images and support links JSON, ensuring decentralized and permanent data storage.
- **Chainlink**: Chainlink plays a crucial role in PatronPlus by providing two key functionalities:
    - Token Price Smart Contract: Chainlink Data Feeds are used to obtain accurate and up-to-date token prices, ensuring transparent and reliable valuation for supporter contributions.
    - Random Number Generation: Chainlink VRF (Verifiable Random Function) is employed to generate random rewards for supporters, adding an element of unpredictability and fairness to the platform.

## Challenges Faced

Building PatronPlus presented several challenges throughout the development process. Some notable hurdles included:

- Internal errors encountered when Chainlink VRF called the "fulfillRandomWords" callback function.
- Initial difficulties deploying a subgraph for the first time.
- Delayed file reflection on IPFS after uploading to web3.storage, resulting in troubleshooting efforts.
- Resolving errors related to web3.storage usage.

## Accomplishments

Despite the challenges faced, we are proud to have built a proof of concept (POC) for PatronPlus. This achievement demonstrates the viability of our idea and serves as the foundation for further optimization and development.

## Lessons Learned

Throughout the development of PatronPlus,

 we gained valuable insights and knowledge. Some of the key lessons learned include:

- Working with Chainlink data feeds and Chainlink VRF to obtain accurate token prices and ensure secure random number generation.
- Indexing smart contract data with The Graph protocol to enhance efficiency and accessibility for users.

## What's Next for PatronPlus

In the future, we plan to:
- Optimize and enhance the security of the smart contracts, addressing potential vulnerabilities.
- Collaborate and partner with social influencers and creators to onboard them and their fans onto the PatronPlus platform, fostering a thriving community of support.
