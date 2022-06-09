# Blockhchain Journey

## 0. Prerequisites

- Basic fundamentals of Computer Science [CS50](https://youtube.com/playlist?list=PLhQjrBD2T380Xnv_v683p6UjiKJZe13ki)
- Programming Languages: HTML, CSS, Python, Javascript
- Git and Github
- Basic Data Structures and Algorithm Knowledge

The one mentioned above are primary requirements to start learning blockchain development. There are a few other things that can qualify as prerequisites for learning blockchain development. However, we can learn these concepts and topics as we progress.

- Core computer science concepts like *Computer Networking* and *Operating System* 
- Frontend library/framework: *React, Typescript, Next.js*
- Hashing, cryptography, specifically *ECDSA*(Elliptic Curve Digital Signature Algorithm) - *Elliptic curve cryptography*, *Asymmetric key cryptography.* 
- Distributed Systems
- Remote Procedure Calls
- [Async-Await Javascript](https://youtu.be/vn3tm0quoqE)

## 1. Fundamentals of Blockchain

As a blockchain app developer we should understand the fundamentals of blockchain. We should grasp the concept of **what** is a blockchain, **how** it works and **why** is it important.

1.1. [Introduction](https://www.ibm.com/in-en/topics/what-is-blockchain)

1.2. [How it works](https://docs.microsoft.com/en-us/archive/msdn-magazine/2018/march/blockchain-blockchain-fundamentals) - [Video Explanation](https://youtu.be/SSo_EIwHSd4)

1.3. [Visual Demo](https://youtu.be/_160oMzblY8)

1.4. [Asymmetric Key cryptography](https://youtu.be/AQDCe585Lnc), [Public Key Cryptography](https://youtu.be/GSIDS_lvRv4)

1.5. [Public/Private Key](https://youtu.be/xIDL_akeras)

1.6.  [Consensus Mechanism](https://ethereum.org/en/developers/docs/consensus-mechanisms/): [Proof-of-Work](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/), [Proof-of-Stake](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/)

1.7. [Smart Contracts](https://ethereum.org/en/developers/docs/smart-contracts/) - [Video Explanation](https://youtu.be/ZE2HxTmxfrI)

1.8. [Bitcoin White Paper](https://bitcoin.org/bitcoin.pdf) - with the above fundamental concepts cleared, its a good time to read about the bitcoin paper. 		Cryptocurrency is one of the use cases of blockchain and *bitcoin* was the very first cryptocurrency. You can use this 		[video](https://youtu.be/bBC-nXj3Ng4) to understand how it works.



## 2. Getting started with Ethereum

Most of our development will be on the **Ethereum** blockchain and its a good time to get [familiarized ](https://ethereum.org/en/developers/docs/)with it. Learn about the **blocks**, **nodes**, **Ethereum Virtual Machine (EVM)**, Ethereum **Mainnet** and **Testnet**(*Rinkeby, Kovan, Rapsten*,etc.), **Gas**

2.1. [Metamask](https://metamask.io/)

2.2 [Etherscan](https://academy.binance.com/en/articles/what-is-etherscan-and-how-to-use-it)

2.3 [Crypto Faucet](https://coinmarketcap.com/alexandria/article/what-is-a-crypto-faucet)

2.4. **Solidity**: Smart Contract is written in Solidity and is the key component of Decentralized Application(DApp)

​	2.4.1. [Learn by doing: Interactive Coding website](https://cryptozombies.io/)

​	2.4.2. [Video](https://youtu.be/M576WGiDBdQ): Jump to 01:31:00. There is also a nice tutorial on how to use **RemixIDE**

​	2.4.3. [Text-based](https://solidity-by-example.org/)

​	2.4.4. [Documentation](https://docs.soliditylang.org/en/v0.8.10/)

## 3. React

These are lot of new concepts to grasp and might be overwhelming to intake everything at once. This might be a good time to divert and enhance web2 development skills and learn [React](https://reactjs.org/). Maybe build some projects to round it up.

​	3.1. [Video 1](https://youtube.com/playlist?list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d)

​	3.2. [Video 2](https://youtu.be/4UZrsTqkcW4)

​	3.3. [text-based](https://reactjs.org/tutorial/tutorial.html)

​	3.4. [Interactive](https://scrimba.com/learn/learnreact)

## 4A. Web3.py and Brownie

**Web3.py** is a python library to interact with Ethereum. **Brownie** is a python-based development and testing framework for smart contracts targeting EVM.

3.1 [Web3.py](https://youtu.be/M576WGiDBdQ): Jump to 03:26:48.

3.2. [Brownie](https://youtu.be/M576WGiDBdQ): jump to 04:27:55.

3.4. [Ganache](https://medium.com/shyft-network-media/how-we-use-ganache-and-ganache-cli-11bb94aa2d1)

3.4. [Web3.py Documentation](https://web3py.readthedocs.io/en/stable/)

3.5. [Brownie Documentation](https://eth-brownie.readthedocs.io/en/stable/)

[Brownie provides a way to test smart contracts](https://eth-brownie.readthedocs.io/en/stable/tests-pytest-intro.html). Good unit tests are critical when it comes to smart contract development. In fact, given smart contracts are immutable and often responsible for managing large sums of money, one could argue that developing good unit tests for smart contracts is more important than traditional web and mobile applications.  Brownie tests is built on [pytest](https://docs.pytest.org/en/6.2.x/).

Learn how to **verify** and **publish** a smart contract on Etherscan. [Reference](https://wiki.rugdoc.io/docs/how-to-verify-a-smart-contract-on-etherscan/) 

## 4B. Hardhat

[Hardhat](https://hardhat.org/) is an environment which lets us test, deploy, and compile the smart contracts

[Video Tutorial](https://www.youtube.com/watch?v=9Qpi80dQsGU)

[Text Tutorial](https://hardhat.org/tutorial/)

## 5.  Blockchain Development Platform

Blockchain platforms allow the development of blockchain-based applications. They can either be permissioned or permissionless. Ethereum, Hyperledger, R3, Ripple, and EOS are a few names that have built blockchain frameworks, allowing people to develop and host applications on the blockchain. Think of them like the **AWS of the Blockchain**, it provides you the infrastructure needed to deploy your DApps in no time, with a **reliable and analytics-ready Node provider**, and Tools.

​	5.1. [Infura.io](https://infura.io/docs/ethereum)

​	5.2. [Alchemy](https://docs.alchemy.com/alchemy/): Alchemy will also provide you with **APIs to deploy NFTs collections** without writing a single Solidity line, 			notifications connected to on-chain events, and an **Enhanced Web3 library** with smart sockets and an expanded 			Ethereum API.

##  

Up until this point, we have almost covered all the tools necessary to start working on smart contract projects. From the next section onwards :

- We can either go in depth into specific divisions of Web 3.0 app development like [DApp](https://decrypt.co/resources/dapps), [NFTs](https://ethereum.org/en/nft/), [DeFi](https://ethereum.org/en/defi/), [DAOs](https://ethereum.org/en/dao/). Its good to explore all but go in depth with anyone to start with.
- Or learn specialised new tools to optimize our workflow like Chainlink, Moralis, IPFS.

## 6. DeFi

1) **[Aave](https://aave.com/)**
   - It is a decentralized [finance protocol](https://github.com/aave/aave-protocol) that allows people to lend and borrow cryptocurrency.
   - In this, when we deposit our ETH, it gets converted to a ERC-20 version of ETH known as [WETH](https://support.opensea.io/hc/en-us/articles/360063498293-What-s-WETH-How-do-I-get-it-#:~:text=WETH%20(Wrapped%20ETH)%20is%20a,directly%20on%20your%20OpenSea%20profile.)
   - aETH is a synthetic reward bearing bond asset that enables instant liquidity for the Ethereum 2.0 network. It represents the staked ETH plus all future staking rewards.
   - Check out [Developers Docs](https://docs.aave.com/developers/getting-started/v3-overview) on how to use Aave protocols

## 7. [NFTs](https://ethereum.org/en/nft/)

Most NFTs are built using a consistent standard known as [ERC-721](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/). However there are other standards that you might want to look into. The [ERC-1155](https://blog.enjincoin.io/erc-1155-the-crypto-item-standard-ac9cf1c5a226) standard allows for semi-fungible tokens which is particularly useful in the realm of gaming. And more recently, [EIP-2309](https://eips.ethereum.org/EIPS/eip-2309) has been proposed to make minting NFTs a lot more efficient. This standard lets you mint as many as you like in one transaction! 

[Openzepplin ERC721](https://docs.openzeppelin.com/contracts/2.x/erc721)

[On-chain vs Offchain NFTs](https://www.one37pm.com/nft/tech/on-chain-and-off-chain-nfts)

[Build, Deploy, and Sell Your Own Dynamic NFT](https://blog.chain.link/build-deploy-and-sell-your-own-dynamic-nft/)

[On-chain NFT development](https://youtu.be/9oERTH9Bkw0)

## 8. [IPFS](https://docs.ipfs.io/concepts/what-is-ipfs/#decentralization)

IPFS is decentralized way to store data in Web3.

[How IPFS work?](https://docs.ipfs.io/concepts/how-ipfs-works/)

NFTs metadata can be stored off-chain using IPFS. IPFS is decentralized but it takes a little bit of centrality to keep persisiting.

Refer [Technical Guide](https://www.freecodecamp.org/news/technical-guide-to-ipfs-decentralized-storage-of-web3/#:~:text=First%20of%20all%2C%20the%20IPFS,%2C%20unique%20content%20identifier%3A%20CID.)

## 9. Moralis

**[Moralis](https://moralis.io/) provides the full-stack workflow for building high performance dapps.** 

Moralis is the fastest way to build and deploy dApps on Ethereum, BSC, Polygon, Solana, and Elrond (more coming). All Moralis dApps are cross-chain by default. Building on Moralis ensures that your dApp is future-proof. Even if new blockchains are invented, your dApp will instantly work on any chain

[Best Resource- Documentation](https://docs.moralis.io/introduction/readme)

## 10. Chainlink

*For an extensive course refer to this [course](https://youtube.com/playlist?list=PLVP9aGDn-X0QwJVbQvuKr-zrh2_DV5M6J)*

- [Blockchain Oracle Problem](https://blog.chain.link/what-is-the-blockchain-oracle-problem/). **Oracles** provide a bridge between the real-world and on-chain smart contracts by being a source of data that smart contracts can rely on, and act upon. Oracles are most popularly used with [*Data Feeds*](https://docs.chain.link/docs/using-chainlink-reference-contracts/). DeFi platforms like [AAVE](https://aave.com/) and [Synthetix](https://www.synthetix.io/) use Chainlink data feed oracles to obtain accurate real-time asset prices in their smart contracts.
- [Chainlink VRF](https://docs.chain.link/docs/chainlink-vrf/): For generating random numbers on blockchain.

## 11. ERC-20

**ERC-20 tokens** are tokens that are deployed on a chain using [ERC-20 token standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/). We need to follow [EIP-20](https://eips.ethereum.org/EIPS/eip-20) standard interface to build ERC-20 tokens.



## 12. OpenZepplin

OpenZeppelin provides a complete suite of security products to build, manage, and inspect all aspects of software development and operations for Ethereum projects.

- Implementations of standards like [ERC20](https://docs.openzeppelin.com/contracts/4.x/erc20) and [ERC721](https://docs.openzeppelin.com/contracts/4.x/erc721).
- Flexible [role-based permissioning](https://docs.openzeppelin.com/contracts/4.x/access-control) scheme.
- Reusable [Solidity components](https://docs.openzeppelin.com/contracts/4.x/utilities) to build custom contracts and complex decentralized systems.

## 13. The Graph

**[The Graph](https://thegraph.com/en/)** is an indexing protocol for querying networks like Ethereum and IPFS. Anyone can build and publish open APIs, called **subgraphs**, making data easily accessible. It is used to build decentralised APIs.

Before The Graph, teams had to develop and operate proprietary indexing servers. This required significant engineering and hardware resources and broke the important security properties required for decentralization.

[Video Tutorial](https://youtu.be/Y-4Rf6OX3YM)

[Text Tutorial](https://ethereum.org/ig/developers/tutorials/the-graph-fixing-web3-data-querying/)

[Documentation](https://thegraph.com/docs/en/)

[Graph Networks in depth](https://thegraph.com/blog/the-graph-network-in-depth-part-1)

[Advanced Reading: Graph Networks in depth- Part 2](https://thegraph.com/blog/the-graph-network-in-depth-part-2)

## 13. Design

- [Decentralized Applications Architecture: Back End, Security and Design Patterns](https://www.freecodecamp.org/news/how-to-design-a-secure-backend-for-your-decentralized-application-9541b5d8bddb/)
- [Designing a decentralized profile dApp](https://uxdesign.cc/designing-a-decentralized-profile-dapp-ab12ead4ab56)

## Projects

1. [Decentralized Lottery Application.](https://github.com/syamantak01/dLottery)
1. How To Develop A Cryptocurrency (https://vitto.cc/how-to-develop-a-cryptocurrency-the-complete-2022-guide/)

## Courses

[Solidity, Blockchain, and Smart Contract Course – Beginner to Expert Python Tutorial](https://youtu.be/M576WGiDBdQ) 

[Blockchain, Solidity, and Full Stack Web3 Development with JavaScript](https://youtu.be/gyMwXuJrbJQ)

[Learn Web3](https://www.learnweb3.io/)

[Web3 University](https://www.web3.university/getting-started)

[udemy Blockchain A-Z](https://www.udemy.com/course/build-your-blockchain-az/?ranMID=39197&ranEAID=CuIbQrBnhiw&ranSiteID=CuIbQrBnhiw-2qquAqwU2jmhuwHuyRg_ew&LSNPUBID=CuIbQrBnhiw&utm_source=aff-campaign&utm_medium=udemyads)

[Coursera Blockchain Specialization](https://www.coursera.org/specializations/blockchain?ranMID=40328&ranEAID=JVFxdTr9V80&ranSiteID=JVFxdTr9V80-TDHuZSJliXzf.A5SCD.8kw&siteID=JVFxdTr9V80-TDHuZSJliXzf.A5SCD.8kw&utm_content=10&utm_medium=partners&utm_source=linkshare&utm_campaign=JVFxdTr9V80)

[udemy Ethereum and Solidity: The Complete Developer's Guide](https://www.udemy.com/course/ethereum-and-solidity-the-complete-developers-guide/?ranMID=39197&ranEAID=CuIbQrBnhiw&ranSiteID=CuIbQrBnhiw-hkc36pfCVgyTXSygIkAmnw&LSNPUBID=CuIbQrBnhiw&utm_source=aff-campaign&utm_medium=udemyads)



