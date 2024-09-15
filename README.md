# What it does

DaoCredly is a decentralized reputation and credentialing system designed for members of decentralized autonomous organizations (DAOs). It allows members to accumulate and verify credentials based on their contributions and participation in DAO activities. These credentials are stored securely on the blockchain, allowing for trustless verification of an individual’s reputation and role within a decentralized community. Members can showcase their credentials as proof of expertise, roles, and involvement in various DAOs.


# The problem it solves

In decentralized ecosystems, reputation and credentials are critical, yet they are often difficult to verify or prove. Traditional systems rely on centralized institutions or third parties to manage certifications and professional histories. DaoCredly solves this by decentralizing the process, making reputation and credential verification transparent, immutable, and trustless. This ensures that members can easily prove their contributions without relying on intermediaries, while DAOs can assess the credibility of potential contributors more effectively.


# Challenges I ran into

Decentralized Identity: One of the key challenges was ensuring secure and reliable user identification in a decentralized way, without relying on traditional identity verification systems.

Credential Verification: Developing a system for verifying credentials without centralized authority posed significant difficulties, requiring a solution that leverages blockchain-based cryptographic proofs.

Integrating Wallets and Authentication: Seamlessly integrating multiple wallet providers (e.g., WalletConnect, Web3Auth) for authentication and signing transactions was complex due to their different APIs and compatibility issues.

Gas Fees: Managing on-chain transactions and ensuring that gas fees were minimized for issuing and verifying credentials was another hurdle that required optimization.


# Technologies I used

Next.js: For building the front-end of the application, ensuring a smooth and responsive user experience.

React.js: As the core front-end framework for creating dynamic components and handling user interactions.

Ethers.js: For interacting with the Ethereum blockchain, handling smart contract interactions and wallet management.

Hardhat: A development environment for compiling and deploying smart contracts.

Moralis: To simplify Web3 development, managing backend functions like user authentication and syncing on-chain data.

Magic SDK: For secure, passwordless login via email and wallet integration.

Web3Auth and WalletConnect: To support decentralized authentication and wallet connection.

Ant Design (antd): For UI components to create a professional and clean interface.

SWR: For data fetching and caching in the front end, ensuring smooth real-time updates


# How we built it

We began by setting up the Next.js framework and integrating React for component-based development. Ethers.js was used to interact with the Ethereum network, managing smart contracts that handled credential issuance and verification. For authentication, we integrated WalletConnect and Web3Auth to allow users to log in via decentralized wallets. We also leveraged Moralis and Magic SDK to simplify backend functions and secure login experiences.

We designed and deployed the smart contracts using Hardhat, ensuring that credentials were stored on-chain, while Ant Design helped us build a clean and user-friendly interface. SWR was employed for efficient data fetching and real-time updates, improving the overall user experience.