# Waku - Idea Board 💡

Below is a compilation of innovative project ideas curated by the Waku community. These ideas cover a wide range of use cases and applications, showcasing the versatility and potential of the Waku protocol for decentralized, privacy preserving communication and beyond.

<br>

> Note : Numerous traditional chat applications have already harnessed Waku's capabilities. To truly innovate and avoid re-inventing the wheel, we encourage hackers to explore untapped possibilities and unique projects that integrate Waku in other novel ways apart from chat.

<br>

<details>
<summary><b>Polling/Voting</b></summary>
<br>
Enable polling or voting off-chain, vote results could be aggregated and submitted on-chain in one transaction.
</details>

<details>
<summary><b>Marketplace (buy/sell goods or NFTs, ride-share, llm, etc)</b></summary>
<br>
Send offer and negotiate off-chain. Highest bids sent over Waku could be binding and submitted to the contract by the seller.
This could include using Waku to enable LLM marketplace where several providers compete to be the one to generate a user's request.
</details>

<details>
<summary><b>Collaborative Editing</b></summary>
<br>
Use Waku for live collaborative editing of documents, saved versions of documents can then be stored on decentralized storage.
</details>

<details>
<summary><b>Multiplayer Games</b></summary>
<br>
Waku can be used to communicate game moves off-chain, the final state (e.g., winner) can then be submitted on-chain for a reward (e.g., NFT mint or winner takes stake).
</details>

<details>
<summary><b>IoT Systems</b></summary>
<br>
Enable devices to communicate or report small data payloads in a decentralized manner.
This can be an interesting way for a government agency or health organization to collect data from the population to study, in a privacy preserving manner.
For example, indoor air quality sensors could be distributed to residents across a city.
The authentication for data push could be done using zk tech: zk credentials of a given device is added to a zk group for a postcode, when pushing data to Waku, zk proof is used so that agency can auth the data and assign it to the right area/postcode but individual indentification or IP harvesting cannot be done.
This can also become an open data initiative: anyone can collect the data from the Waku network for study (DeSci).
</details>

<details>
<summary><b>Decentralized Wallet Address Ownership Verification</b></summary>
<br>
Use Waku to enable communication between dApps and wallets, such as signature or zero-knowledge proof exchange to prove identity.
</details>

<details>
<summary><b>Notifications Centre</b></summary>
<br>
Use an SDK (probably go-waku?) to build a general Notification protocol over Waku and a mobile app allowing you to replace centralized Push Notifications provided by Apple/Google.
</details>

<details>
<summary><b>API Generator</b></summary>
<br>
Build a tool to generate a Waku protocol (and code) from a provided OpenAPI specification.
</details>

<details>
<summary><b>Leader Election Protocol</b></summary>
<br>
Leader election can be viewed as a soft consensus mechanism. Implement something like [RAFT](https://raft.github.io/) as a library on top of Waku (using any SDK), so that users can easily plug it into their applications.
</details>

<details>
<summary><b>Reputation Systems</b></summary>
<br>
Using Waku to create reputation systems that can provide a reputation score for a particular identity (wallets, smart contracts etc.,)
</details>

<details>
<summary><b>Censorship-Resistant Reviews Plugin</b></summary>
<br>
An embeddable plugin which can be used for collecting and displaying censorship-resistant reviews
</details>

<details>
<summary><b>Privacy-Preserving Location Tracker</b></summary>
<br>
A location tracker that does not expose user's location and enables them to share it with each other provided that they are shared access
</details>

<details>
<summary><b>Medical Systems for Remote Diagnosis</b></summary>
<br>
Tracking medical data from sensors and IoT devices and sending them to a doctor for remote diagnosis
</details>

<details>
<summary><b>Decentralized Smart Grid System</b></summary>
<br>
Decentralized smart grid system optimizes energy distribution and consumption by leveraging Waku to efficiently manage energy resources across a network of users and devices
</details>

<details>
<summary><b>Decentralized Autonomous Vehicle Coordination</b></summary>
<br>
Decentralized Autonomous Vehicle Coordination powered by Waku enables self-driving vehicles to securely communicate and coordinate their actions, enhancing traffic efficiency and safety within a decentralized network</details>

<details>
<summary><b>Crowd-Sourced Weather Data Network</b></summary>
<br>
A Crowd-Sourced Weather Data Network utilizes Waku to collect and share real-time weather information from diverse sources, creating a comprehensive and accurate weather data resource for enhanced forecasts and monitoring while maintaining decentralization and privacy.
</details>

<details>
<summary><b>P2P Chess</b></summary>
<br>
A simple 2 player game where users can stake crypto and winner gets the stake
</details>

<details>
<summary><b>P2P TicTacToe</b></summary>
<br>
A simple 2 player game where users can stake crypto and play to win
</details>

<details>
<summary><b>Privacy-Focused Fitness Tracker</b></summary>
<br>
A fitness tracker which stores your health metrics and allows you to securely share it with your friends
</details>

<details>
<summary><b>Decentralized and Privacy-Focused Hiring Platform (Web3 version of BambooHR)</b></summary>
<br>
A bias-less HR platform that does not discriminate applicants based on diversifying factors
</details>

<details>
<summary><b>DAO/Governance Tooling</b></summary>
<br>
Using Waku to create, vote or approve proposals passed in a governance system
</details>

<details>
<summary><b>Satellite Communication Systems</b></summary>
<br>
Using Waku to harness satellite based communication systems that do not rely on a centralised provider
</details>

<details>
<summary><b>Decentralized Web Walkie-Talkie</b></summary>
<br>
Real-time audio communication channels built on Waku
</details>

<details>
<summary><b>Crypto ATMs</b></summary>
<br>
Decentralised ATM cards that can be used to withdraw / approve transactions at POCs
</details>

<details>
<summary><b>Smart Access Cards</b></summary>
<br>
NFC cards that can be used for various use cases like unlocking devices, signing transactions or interacting with real life elements
</details>

<details>
<summary><b>Secure DeFi</b></summary>
<br>
When a user wants to perform a transaction, ensure the transaction is made to the correct counter-party address within the correct chain.
</details>

<details>
<summary><b>News over Waku</b></summary>
<br>
Platform where people can publish news which can be voted and commented.
</details>

<details>
<summary><b>Budget approval app</b></summary>
<br>
Allow a community to approve and decide the best way to handle the common funds, and make the transactions transparent to the community.
</details>

<details>
<summary><b>Privacy preserving AI assistant</b></summary>
<br>
A privacy preserving AI assistant that does not reveal the identity of the user who sends prompts to the AI model.
</details>

<details>
<summary><b>Federated Learning Platform</b></summary>
<br>
A federated learning platform leveraging Waku for communication among edge devices. Waku ensures privacy by enabling encrypted communication channels, allowing devices to collaborate on model training tasks without sharing raw data.
</details>

<details>
<summary><b>Supply Chain Transparency Solution</b></summary>
<br>
A supply chain transparency solution incorporating Waku for secure communication and data sharing among stakeholders. Waku enables encrypted communication channels, allowing participants to exchange information about product origins, manufacturing processes, and logistics while maintaining data privacy and integrity.
</details>

<details>
<summary><b>Decentralised brainstorming tool</b></summary>
<br>
An anonymous tool for collaborative brainstorming where users can describe their ideas without having to worry about them being judged when they share ideas.
</details>

<details>
<summary><b>Privacy preserving confessions board</b></summary>
<br>
An anonymous and gamified tool for sharing confessions to other users.
</details>

<details>
<summary><b>Privacy preserving governance platform</b></summary>
<br>
A governance platform where votes are not linked to Wallets. ZK can be used to find if a wallet has the voting power but the user's vote is not transparent to other users.</details>

<details>
<summary><b>Privacy preserving APIs and Data sources</b></summary>
<br>
REST APIs can log IP addresses of the data source and the receiver. Building a decentralized layer for enabling privacy preserving APIs alongside rate-limiting with RLN can be quite impactful</details>

<details>
<summary><b>Decentralized disaster communication</b></summary>
<br>
Decentralized network that allows for communication in disaster-stricken areas where traditional infrastructure may be unavailable or affected. Devices can connect directly to each other, forming a resilient network.
</details>

## Interested to contribute?

Do you wish to see your idea listed above? Refer to our [contribution guide](https://github.com/waku-org/ideas/blob/master/CONTRIBUTE.md)

