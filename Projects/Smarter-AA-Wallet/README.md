### 项目概述

Empowered by the interoperability of Web3 and intelligent automation of AI agents, our entrepreneurship project is a demand abstraction wallet to enable a better new way of user interaction from Web2 based on Apps to Web3 based on the demand of users. Users can just express their needs and then directly get what they want with no need to operate the blockchain by themselves in a fully natural, straightforward, and convenient way. To do so, we will intelligently understand and analyze the needs of users to generate the optimal solutions including a series of on-chain operations and transactions. After users confirm and authorize, we will automatically execute the solution to operate the corresponding crypto assets and run through different DApps for users, and get back the results to meet their demands. In this way, we can lower the threshold and complexity of on-chain operations and Web3 interaction, thus improving the efficiency and experience of crypto users especially those newcomers with no blockchain knowledge and background for the mass adoption of Web3.

### 技术架构

AI Agent: AI can intelligently understand the inputs of users via interface, text, or speech to precisely analyze and get the demand of users. To meet user demands, AI will find, compare, choose, and combine all different Apps to generate the best solution schemes including what operations should be performed on which Apps. The agent will also intelligently execute the solution and react to different kinds of variations under actual situations to meet the demands of users.
Account Abstraction: After getting users' authorization, the decentralized bundlers enabled by account abstraction based on ERC-4337 can execute the solution scheme to run DApps and operate digital assets for users via smart contracts in the account of users. Finally, bundlers will get what users need back to users as the execution results. Different bundlers will compete with each other for the generation and execution of optimal solutions, so users can compare and choose the best one to best meet their demands.
Chain abstraction: With chain abstraction, we will help users intelligently choose the optimal chain to best meet their demands, and seamlessly help them perform cross-chain operations if needed. Users don't need to switch among different chains by themselves, and they don't need to be aware of the existence of different chains.
Zero-knowledge Proofs: Users can easily and quickly verify the correctness and effectiveness of both solution schemes and execution results provided by the bundlers. Users can also protect the privacy of their demands from being known or leaked by bundlers to avoid potential attacks like front-running.

合约语言：solidity

前端框架：nextjs

### 核心功能

Register & login: local password + MPC email verification

Homepage: show the account balances of each kind of assets and historical transactions 

Cross-chain swap and transfer: When the user wants to transfer token to someone, he/she can directly tell and do so in our wallet even if the user and receipt are in different chains with different tokens because we can identify and do the swap and cross-chain for them automatically. For instance if a user on Polkadot wants to send 100 USDC to Alice on Ethereum, besides finding the optimal cross-chain bridge and DEX, our agent will analyze:

1. whether the user has enough USDC on Ethereum. If so, we can directly send them to Alice on Ethereum. Otherwise our agent would consider and compare: 
2. whether the user has any other equivalent tokens on Ethereum. If so, we can swap them to USDC first, and then send them to Alice. Alternatively:
3. whether the user has enough USDC on Polkadot. If so, we will do cross-chain transfer to transfer his/her USDC from Polkadot to Ethereum, and then send USDC to Alice on Ethereum. Otherwise, our agent would compare and consider:
4. swap any other equivalent tokens like DOT on Polkadot to USDC, then do cross-chain transfer to transfer USDC from Polkadot to Ethereum, and finally send USDC to Alice on Ethereum. Alternatively,
5. do cross-chain transfer first to send other tokens like DOT on Polkadot to Ethereum, then swap to USDC and transfer to Alice on Ethereum. 

Trading strategy recommendation: If the user has remaining balance on his/her account, we will recommend him/her to put his balance into some DeFi protocols to earn stable and certain returns like staking and loans with low risks. We can also intelligently generate the optimal trading schemes for him/her like the highest APR and interests. After he/she chooses and confirms the trading scheme, we will automatically execute it for the user to trade in those protocols. Users can earn the corresponding return everyday, and they can freely withdraw at any time. 


### 项目团队

develop ：

Blockchain developer and researcher Jel Yin graduated from Carnegie Mellon University and he has rich entrepreneurship experiences on blockchain, Web3 and Fintech. His previous crypto projects covered DeFi MEV, DAO, and creator economy. He got the funding from Ethereum Foundation, Ripple, and Metagov. He also won several Hackathon prizes in Arweave and Circle. https://github.com/mryings 

Blockchain developer Myron Zhang is the core developer of our project with strong capacity and expertise in smart contracts and blockchain development. He formerly worked in a famous CEX and he led a team to develop a crypto wallet successfully there. He was also a smart contract and backend developer in RCT AI. https://github.com/zhangzhishun 

UI&UX designer Jingwen Luo graduated from University of Pennsylvania majoring in Integrated Product Design. She has two years of experience as a product designerin SaaS startups, including edtech, healthtech, and ecommerce, and three years of experience as an architecturaldesigner on crafting spatial and 3D experiences. She previously worked as a UI&UX designer at a digital health company called Allay and a New York-based O2O startup called Poom.  https://www.jingwenluo.com/

### 项目链接
Github: https://github.com/smarterwallet

Prototype: https://www.figma.com/file/79vQtcOkQeVd0s6g9Ykonr/Demand-abstraction-AA-Wallet?type=design&node-id=0-1&mode=design

Deck: https://drive.google.com/file/d/1cWYS6YHwSmCPUTnGrJlMSLqPkn-rKnHn/view?usp=sharing

### 联系方式
Telegram: @smarteraawallet
E-mail: demandabstraction@gmail.com

