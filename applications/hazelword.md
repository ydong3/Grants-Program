# W3F Grant Proposal

* **Project Name:** Hazelword
* **Team Name:** Legal name of your team (e.g. Duo)
* **Payment Address:** BTC or Ethereum (USDT/DAI) payment address. We don't accept payments for the program in other currencies at this stage. If this is an Ethereum address, please specify USDT or DAI. (e.g. 0x8920... (DAI))


## Project Overview :page_facing_up:

    this application is in response to an RFP


### Overview

Hazel is a blockchain-oriented prediction service which features decentralization, or more specifically, a new generation of verifiable oracle machine based on Polkadot. It aims to exactly support the on-chain operation of enterprise-level Internet applications with high-concurrency through consensus mechanisms, smart contracts, trusted computing, privacy protection and the interaction of on-chain and off-chain data.

Hazleword is set to build a data infrastructure by applying Off-chain Worker under Polkadot/Substrate Framework. The mission of Hazleword racle is to provide real-time, transparent, reliable and efficient on-chain/off-chain market statistics and social data sources.Hazleword is to build a decentralized Oracle system with advanced technologies. The Off-chain Worker for Hazleword will allow execution of expensive, long-running and private tasks such as the Computation-based Data Verification,and Through the collaborative application of TEE, MPC and on-chain contracts, Hazel will realize the privacy protection of high-value data from oracle and complete consequent collaborative calculation as well as application, making it possible that the transaction of value flow under the premise that all parties involved are invisible one another.

The Internet has realized the efficient transmission of information where the concept of Internet of Everything and its application have greatly changed human life. As the next-generation "Internet of Value", blockchain is expected to deliver and exchange value as accurately, efficiently and safely as information while the digital assets based on the native blockchain system are important carriers in transmission of value.As an objective measurement of value, price is an important basic component for realizing value exchange. With the rapid development of blockchain, whether value can be exchanged at low cost safely and efficiently has become a core standard for measuring the application value of blockchain. Therefore, as it were, the measurement of application value of blockchain is inseparable from the objective measurement of assets on any chain.We expect to provide a data-driven prediction service based on the “asset-backed events” and a data-correction mechanism based on fact checking. The oracle machine could resolve fundamental problems about trusted source of data of blockchain through the mechanism of market arbitrage.


### Project Details

**Dapp (Web test network)**
https://test.hazelword.org


![alt Contract Architecture](https://github.com/Hazelword/hzl-sol/blob/main/doc/hzl-en.jpg)

* An overview of the technology stack to be used
* Documentation of core components, protocols, architecture, etc. to be deployed
* PoC/MVP or other relevant prior work or research on the topic
* What your project is _not_ or will _not_ provide or implement
  * This is a place for you to manage expectations and to clarify any limitations that might not be obvious

### Ecosystem Fit

In the indirect oracle, the credit risk of the node uploading the data determines the cost of attacking the data of the oracle. If 1 trillion dollars of assets are derived based on the price provided by the oracle, the credit of the oracle node should also match it. This is obviously impossible in reality. No matter what node randomness is used, it cannot be guaranteed. This is an essential problem, not a technical problem, so indirect oracles can only be used in small-scale, non-financial scenarios.


* Where and how does your project fit into the ecosystem?
* Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
* What need(s) does your project meet?

| Number | Deliverable | Specification | Data Verification Time|
| -----: | ----------- | ------------- | --------------------- |
|ChainLink |Off-chain centralized submission, on-chain aggregation|YES|Post, after the data becomes effective|
|API3 |Off-chain centralized submission (removal of the middle party), on-chain aggregation |YES |Post, after the data becomes effective|
| Band|Off-chain aggregation, on-chain voting verification | YES|Post, after the data becomes effective|
| Tellor|Competing for computing power to obtain data reporting rights, aggregation on the chain |NO |Post, after the data becomes effective|
| HazelWord| Decentralized submission on the chain, real-time verification and aggregation on the chain|NO |Before, before the data becomes effective|




## Team :busts_in_silhouette:

### Team members

   Name of team leader：HuangShouYi

### Contact

* **Contact Name:** Full name of the contact person in your team
* **Contact Email:** Contact email (e.g. john@duo.com)
* **Website:**

### Legal Structure

No legal Entity

### Team's experience

One of them Coming from the financial advisory sector and specialist in Token Economics, has designed and developed various smart contracts on Ethereum.
One of them is also a Substrate runtime developer. He is proficient in distributed financial blockchain development.
One of them has more than 7 years product/program/project management experience in Blockchain and high-tech industry.
The rest are front-end developers, ui designers, and Android IOS developers
### Team Code Repos

* https://github.com/Hazelword
* https://github.com/qksl

the GitHub accounts of all team members. 

* https://github.com/ydong3
* https://github.com/ywdlucking
...

### Team LinkedIn Profiles (if available)
no

## Development Status :open_book:

1.  The smart contract complete phase 1.0 development
2.  Deployed contract on test network
3.  Complete DAPP Web UI development


## Development Roadmap :nut_and_bolt:

### Overview

* **Total Estimated Duration:**  3 month
* **Full-Time Equivalent (FTE):**  45 days with 4 Full-Time 
* **Total Costs:** $3000

### Milestone 1 Example — Implement Substrate Modules

* **Estimated duration:** 2 month
* **FTE:**  1
* **Costs:** 3,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | GPLv3 |
| 0b. | Documentation | We provide documents on how users can participate in HAZEL quotation |
| 0c. | Testing Guide | (1) We will provide how to run the complete quotation (2) How to call the interface by the third party |
| 0d. | Docker | We provide documentation for all modules for easy testing |
| 0e. | Article | We will provide an article in which we will publish what Hazel has done
| 1. | Smart Contract | Quoting and generating price chains in the market（Detailed explanation below），The smart contract can be deployed to any substrate chain with evm pallet. |  
| 2. | Tests | Unit Test and also we will test it |  
| 3. | Dapp | A page UI for viewing prices |  
| 4. | Other | TEE module（Detailed explanation below） |  


### Milestone 2 Example — Additional features

no


## Future Plans

Shares token design for governance.
Products include well-matched back-end and front-end, which support iOS, Android, and WEB.
The product for consulting service Blockchain Forest will be connected to Hezel data service
More partners in the blockchain ecology will be introduced and accessed to.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website 

