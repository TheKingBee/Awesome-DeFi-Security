# Awesome Decentralized Finance Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome DeFi security-related projects, research, tools, and resources.

## What is Decentralized Finance?

Decentralized finance (#defi) is the movement that leverages open source software and decentralized networks to transform traditional financial products into trustless and transparent protocols that operate without unnecessary intermediaries. One could envision decentralized finance impacting the financial world the same way that open source software has changed software products.

## What is security?

## What are the challenges of security in Decentralized Finance?

## Contents

* [Learning](#learning)
  * [Security references](#security-references)
  * [Insecurity references](#insecurity-references)
  * [Capture the Flag and Wargames](#capture-the-flag-and-wargames)
    * [Writeups](#writeups)
  * [Coordinated disclosure](#coordinated-disclosure)
  * [Blogs](#blogs)
  * [Notable blog posts](#notable-blog-posts)
  * [Conference talks](#conference-talks)
  * [Podcasts and Episodes](#podcasts-and-episodes)
    * [Podcasts](#podcasts)
    * [Episodes](#episodes)
* [Tools](#tools)
  * [Visualization](#visualization)
  * [Linters](#linters)
  * [Bug finding tools](#bug-finding-tools)
  * [Verification tools](#verification-tools)
  * [Reversing tools](#reversing-tools)
* [Communities](#communities)
* [Other Awesome Lists](#other-awesome-lists)

## Learning

### Security references

* [Comprehensive list of known attack vectors for Solidity](https://blog.sigmaprime.io/solidity-security.html)
* [Consensys Best Practices](https://github.com/ConsenSys/smart-contract-best-practices)
* [Decentralized Application Security Project](https://www.dasp.co/)
* [Solidity Security Considerations](https://solidity.readthedocs.io/en/latest/security-considerations.html)
* [Solidity v0.5.0 Breaking Changes](https://solidity.readthedocs.io/en/latest/050-breaking-changes.html)
* [Solidity v0.6.0 Breaking Changes](https://solidity.readthedocs.io/en/latest/060-breaking-changes.html)
* [Solidity v0.7.0 Breaking Changes](https://solidity.readthedocs.io/en/latest/070-breaking-changes.html)
* [Solidity v0.8.0 Breaking Changes](https://solidity.readthedocs.io/en/latest/080-breaking-changes.html)


### Insecurity references

* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens)
* [EVM Analyzer Benchmark](https://github.com/ConsenSys/evm-analyzer-benchmark-suite)
* [Not So Smart Contracts](https://github.com/trailofbits/not-so-smart-contracts)

### Capture the Flag and Wargames

* [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/)
* [Capture the Ether](https://capturetheether.com/)
* [Ethernaut](https://ethernaut.zeppelin.solutions/)
* [EtherHack](https://etherhack.positive.com/)
* [SI Blockchain CTF](https://blockchain-ctf.securityinnovation.com/)

#### Writeups

* [Hands on the Ethernaut CTF](https://blog.trailofbits.com/2017/11/06/hands-on-the-ethernaut-ctf/) - Writeups for various Ethernaut CTF challenge contracts.
* [Ethernaut - Naught Coin (ERC20) Exploitation](https://medium.com/coinmonks/ethernaut-naught-coin-erc20-exploitation-218c86bb953b) - Writeup for a vulnerable ERC20 from the Ethernaut CTF.
* [EtherHack CTF Writeup](https://blog.positive.com/phdays-8-etherhack-contest-writeup-794523f01248) - Writeup for EtherHack CTF challenges.
* [PolySwarm Smart Contract Hacking Challenge Writeup](https://raz0r.name/writeups/polyswarm-smart-contract-hacking-challenge-writeup/) - Demonstrates advanced use of Manticore


## DeFi Science:


- [Formal Analysis of Composable DeFi Protocols ](https://arxiv.org/pdf/2103.00540.pdf) - In this paper, authors propose a formal process-algebraic technique that models DeFi protocols in a compositional manner to allow for efficient property verification.

- [Transaction Fee Mechanism Design](https://arxiv.org/pdf/2106.01340.pdf) - Authors explain the behavior of fees in blockchains.

- [DeFi-ning DeFi: Challenges & Pathway](https://arxiv.org/pdf/2101.05589.pdf) - Good Retrospective into the beginning of decentralized finance.

- [A theory of Automated Market Makers in DeFi](https://arxiv.org/pdf/2102.11350.pdf) -  Authors exploit our theory to formally prove a set of fundamental properties of AMMs, characterizing both structural and economic aspects. 

- [Leveraged Trading on Blockchain Technology](https://arxiv.org/pdf/2102.13488.pdf) -  Authors document an ongoing research process towards the implementation and integration of a digital artefact, executing the lifecycle of a leveraged trade with permissionless blockchain.

- [From banks to DeFi: the evolution of the lending market](https://arxiv.org/pdf/2104.00970.pdf) -  Authors discuss the persisting reliance of DeFi lending on the traditional financial system, and conclude with the outlook of the lending market in the IOV era.

- [Towards Self-Regulating AI](https://arxiv.org/pdf/2010.04827.pdf) - Challenges and Opportunities of AI Model Governance in Financial Services.

- [On the Just-In-Time Discovery of Profit-Generating Transactions in DeFi Protocols](https://arxiv.org/pdf/2103.02228.pdf) -In this paper, authors investigate two methods that allow them to automatically create profitable DeFi trades.

- [Maximizing Extractable Value from Automated Market Makers](https://arxiv.org/pdf/2106.01870.pdf) -  In this paper authors formally characterize rational miners as players which follow an optimal strategy in the mining game. 

- [The Decentralized Financial Crisis](https://arxiv.org/pdf/2002.08099.pdf) -  In this paper authors explore how design weaknesses and price fluctuations in DeFi protocols could lead to a DeFi crisis.

- [Liquidations: DeFi on a Knife-edge](https://arxiv.org/pdf/2009.13235v4.pdf)- In order to protect protocols from suffering losses, undercollateralized positions can be liquidated. In this paper, authors present empirical analysis of liquidations on protocols for loanable funds (PLFs).

- [Measuring Asset Composability as a Proxy for DeFi Integration](https://arxiv.org/pdf/2102.04227.pdf) -  Authors seek to understand the degree to which this practice may contribute to financial integration on Ethereum by examining transactions in 'composed' derivatives for the assets DAI, USDC, USDT, ETH and tokenized BTC for the full set of 344.8 million Ethereum transactions computed in 2020. 

- [Dynamic Curves for Decentralized Autonomous Cryptocurrency Exchanges](https://arxiv.org/pdf/2101.02778.pdf) -  Authors propose in this work a new approach to constructing the AMM by proposing the idea of dynamic curves.

- [High-Frequency Trading on Decentralized On-Chain Exchanges](https://arxiv.org/pdf/2009.14021.pdf) - In this work authors formalize, analytically exposit and empirically evaluate an augmented variant of front-running: sandwich attacks, which involve front- and back-running victim TXs.

- [Flashot](https://arxiv.org/pdf/2102.00626.pdf) - A Snapshot of Flash Loan Attack on DeFi Ecosystem.

- [DeFiRanger](https://arxiv.org/pdf/2104.15068.pdf) -  Detecting Price Manipulation Attacks on DeFi Applications.

- [Attacking the DeFi Ecosystem with Flash Loans for Fun and Profit](https://arxiv.org/pdf/2003.03810.pdf) - Flash Loans. DeFi. Classic.

- [SoK: Decentralized Finance (DeFi) ](https://arxiv.org/pdf/2101.08778.pdf) - In this Systematization of Knowledge (SoK), authors delineate the DeFi ecosystem along its principal axes. SCSGuard: Deep Scam Detection for Ethereum Smart Contracts

- [Empirical Evidence from four Governance Token Distributions](https://arxiv.org/pdf/2102.10096.pdf) -  This paper provides a framework to quantify decentralization of governance power among blockchain applications.

- [The Adoption of Blockchain-based Decentralized Exchanges](https://arxiv.org/pdf/2103.08842.pdf) -  Authors show that liquidity providers lose token value if exchange rates are volatile due to the order execution mechanism of the blockchain-based exchange.

- [An analysis of Uniswap markets](https://arxiv.org/pdf/1911.03380.pdf) -One of the best studies on Uniswap DEX activity, authors started researching in 2019 and recently released fresh 2021 analysis.

- [Finance 4.0: Design principles for a value-sensitive cryptoecnomic system to address sustainability](https://arxiv.org/pdf/2105.11955.pdf) - Authors provide new insights on designing crypto systems.

- [Behavior of Liquidity Providers in Decentralized Exchanges](https://arxiv.org/pdf/2105.13822.pdf) - Authors aim to understand how liquidity providers react to market information and how they benefit from providing liquidity in DEX.

- [Cyclic Arbitrage in Decentralized Exchange Markets](https://arxiv.org/pdf/2105.02784.pdf) - Good Read. This paper suggests that with the smart contract technology and the replicated state machine setting of Ethereum, arbitrage strategies are easier implemented in DEXes than in CEX.

- [SoK: Oracles from the Ground Truth to Market Manipulation](https://arxiv.org/pdf/2106.00667.pdf) - In this SoK, authors systemize the design alternatives for oracles, showcase attacks, and discuss attack mitigation strategies.

- [Composing Networks of Automated Market Makers](https://arxiv.org/pdf/2106.00083.pdf) - This paper proposes a mathematical model for AMM composition.


## Security & Safety:

- [ The Eye of Horus: Spotting and Analyzing Attacks on Ethereum Smart Contracts](https://arxiv.org/pdf/2101.06204.pdf) -Investigation shows that the number of attacks did not necessarily decrease over the past few years, but for some vulnerabilities remained constant.

- [Analysis of Bitcoin Vulnerability to Bribery Attacks Launched Through Large Transactions](https://arxiv.org/pdf/2105.07501.pdf) -  In this paper, authors design a novel bribery attack and show that this guarantee can be hugely undermined.

- [Vulnerability of Blockchain Technologies to Quantum Attacks](https://arxiv.org/pdf/2105.01815.pdf) - Here authors analyze the major blockchain-based cryptocurrencies deployed today -- including Bitcoin, Ethereum, Litecoin and ZCash, and determine risk exposure to quantum attacks. 

- [BLOCKEYE](https://arxiv.org/pdf/2103.02873.pdf) - Hunting For DeFi Attacks on Blockchain. In this paper, authors proposed BLOCKEYE, a real-time attack detection system for DeFi projects on the Ethereum blockchain. 

- [Topological Anomaly Detection in Dynamic Multilayer Blockchain Networks](https://arxiv.org/pdf/2106.01806.pdf) - Authors introduce a new topological perspective to structural anomaly detection in dynamic multilayer networks.

- [Ponzi Scheme Detection in Ethereum Transaction Network](https://arxiv.org/pdf/2104.08456.pdf) - Authors discover new ways of detecting Ethereum-based Ponzi schemes.

- [Verification of the Incremental Merkle Tree Algorithm with Dafny](https://arxiv.org/pdf/2105.06009.pdf) - Authors present our new and original correctness proof of the algorithm along with the Dafny machine-checkable version.

- [GoHammer Blockchain Performance Test Tool](https://arxiv.org/pdf/2105.00847.pdf) - This tool will help in developing more efficient decentralized systems and will affect decreasing the costs of developing decentralized application projects.

- [EtherClue: Digital investigation of attacks on Ethereum smart contracts ](https://arxiv.org/pdf/2104.05293.pdf) - In this work, authors study the problem of post-factum investigation of Ethereum attacks using Indicators of Compromise specially crafted for use in the blockchain.

- [Requirement Analyses and Evaluations of Blockchain Platforms per Possible Use Cases](https://arxiv.org/pdf/2103.03209.pdf) - This document provides a generic model of understanding blockchain and its applications.

- [A Note on Privacy in Constant Function Market Makers](https://arxiv.org/pdf/2103.01193.pdf) -  In this note, authors show that privacy is impossible with the usual implementations of CFMMs under most reasonable models of an adversary and provide some mitigating strategies.

- [A Survey of Security Vulnerabilities in Ethereum Smart Contracts](https://arxiv.org/pdf/2105.06974.pdf) -  This paper explains eight vulnerabilities that are specific to the application level of BT by analyzing the exploitation case scenarios of these vulnerabilities.

- [Low-cost attacks on Ethereum 2.0 by sub-1/3 stakeholders](https://arxiv.org/pdf/2102.02247.pdf) - Authors outline two dishonest strategies that can be cheaply executed on the Ethereum 2.0 beacon chain, even by validators holding less than one-third of the total stake: malicious chain reorganizations ("reorgs") and finality delays. 

- [An approach to detect Denial of Service Vulnerability in Ethereum Smart Contracts](https://arxiv.org/pdf/2106.01340.pdf) -  In this paper, authors propose a framework that combines static and dynamic analysis to detect DoS due to an unexpected revert in ETH Smart Contracts.

- [AGSolT: a Tool for Automated Test-Case Generation for Solidity Smart Contracts](https://arxiv.org/pdf/2102.08864.pdf) - Authors found that AGSolT is capable of achieving high branch overage with both approaches and even discovered some errors in some of the most popular Solidity smart contracts on Github.

- [Temporal-Amount Snapshot MultiGraph for Ethereum Transaction Tracking](https://arxiv.org/pdf/2102.08013.pdf) - Authors propose TASMG to model Ethereum transaction records as a temporal-amount network and then present TAW to effectively embed accounts via their transaction records, which integrates temporal and amount information of the proposed network.

- [Smart Contract Vulnerability Detection: From Pure Neural Network to Interpretable Graph Feature and Expert Pattern Fusion](https://arxiv.org/abs/2106.09282) - Understanding smart contracts scan tools. 

- [Ethereum Name Service: the Good, the Bad, and the Ugly](https://arxiv.org/pdf/2104.05185.pdf) - Yet, no existing work has studied this emerging system, the security issues and misbehaviors in ENS. Authors present the first study of ENS by analyzing millions of event logs related to ENS.

- [The Anatomy of a Cryptocurrency Pump-and-Dump Scheme](https://arxiv.org/pdf/1811.10109.pdf) - This paper represents the first detailed empirical query of pump-and-dump activities in cryptocurrency markets.

- [Distinguishing manipulated stocks via trading network analysis](https://arxiv.org/pdf/1110.2260.pdf) - These findings may help to detect manipulated stocks. Distinguishing manipulated stocks via trading network analysis.

- [From Innovations to Prospects: What Is Hidden Behind Cryptocurrencies?](https://arxiv.org/pdf/2103.08924.pdf) -  In this paper, an empirical study on existing altcoins is carried out to offer a thorough understanding of various aspects associated with altcoin innovations.

- [Demystifying Cryptocurrency Mining Attacks: A Semi-supervised Learning Approach Based on Digital Forensics and Dynamic Network Characteristics](https://arxiv.org/pdf/2102.10634.pdf) - This paper addresses the detection of crypto mining attacks in a generic network environment using dynamic network characteristics. 

- [FASTEN: Fair and Secure Distributed Voting Using Smart Contracts](https://arxiv.org/pdf/2102.10594.pdf) - Authors prove that the probability of privacy breaches is negligibly small. Further, cost analysis of executing FASTEN over Ethereum is comparable to most of the existing cost of elections.

- [Interdependencies between Mining Costs, Mining Rewards and Blockchain Security](https://arxiv.org/pdf/2102.08107.pdf) - This paper studies to what extent the cost of operating a proof-of-work blockchain is intrinsically linked to the cost of preventing attacks, and to what extent the underlying digital ledger security budgets are correlated with the cryptocurrency market outcomes

- [HyperSec: Visual Analytics for blockchain security monitoring](https://arxiv.org/pdf/2103.14414.pdf) - HyperSec, a visual analytics monitoring tool that provides relevant information at a glance to detect ongoing attacks on Hyperledger Fabric. 

- [Reentrancy Vulnerability Identification in Ethereum Smart Contracts](https://arxiv.org/pdf/2105.02881.pdf) - In this paper, authors present a framework that combines static and dynamic analysis to detect Reentrancy vulnerabilities in Ethereum smart contracts.

- [A General Framework for the Security Analysis of Blockchain Protocols](https://arxiv.org/pdf/2009.09480v2.pdf) - This paper presents a parsimonious abstraction sufficient for capturing and comparing properties of many well-known permissionless blockchain protocols.

- [SoK: Blockchain Solutions for Forensics](https://arxiv.org/pdf/2005.12640.pdf) - In this paper, authors provide an overview and classification of the available blockchain-based digital forensic tools, and further describe their main features.

- [Coinbugs: Enumerating Common Blockchain Implementation-Level Vulnerabilities](https://arxiv.org/pdf/2104.06540.pdf) -  The paper is aimed at security testers aiming to start out in blockchain security reviews and blockchain developers as a reference on common pitfalls.

- [Vulnerabilities and Open Issues of Smart Contracts: A Systematic Mapping](https://arxiv.org/pdf/2104.12295.pdf) - This paper conducted a systematic literature mapping identifying initiatives and tools to analyze SCs and how to deal with the identified vulnerabilities.

- [SuMo: A Mutation Testing Strategy for Solidity Smart Contracts](https://arxiv.org/pdf/2105.03626.pdf) - Authors report a first evaluation of SuMo on open-source projects for which test suites were available. The results authors got are encouraging, and they suggest that SuMo can effectively help developers to deliver more reliable smart contracts.

- [(In)Stability for the Blockchain: Deleveraging Spirals and Stablecoin Attacks](https://arxiv.org/pdf/1906.02152.pdf) - The possibility of deleveraging spirals was first predicted in the initial release of this paper in 2019 and later observed in the Black Thursday crisis in Dai in 2020.

- [An Anonymous Trust-Marking Scheme on Blockchain Systems](https://arxiv.org/pdf/2010.00206.pdf) - In this paper, authors propose an anonymous trust-marking scheme on blockchain systems that is universally applicable to any cryptocurrency.

- [A Framework and DataSet for Bugs in Ethereum Smart Contracts](https://arxiv.org/pdf/2009.02066.pdf) -  In this paper, to fill the gap, authors first collect as many smart contract bugs as possible from multiple sources and divide these bugs into 9 categories by extending the IEEE Standard Classification for Software Anomalies.

- [A Secure Multi-chains Consensus Scheme Against Diverse Miners Behaviors Attacks in Blockchain Networks.](https://arxiv.org/pdf/2106.02383.pdf) - Experimental results show that PoDT is secure against DMB attacks and more effective than traditional consensus schemes in multi-chains environments.

- [A Survey on Consortium Blockchain Consensus Mechanisms](https://arxiv.org/pdf/2102.12058.pdf) - This paper highlights several state-of-the art solutions in consensus algorithms for enterprise blockchain. 

- [Extracting Smart Contracts Tested and Verified in Coq](https://arxiv.org/pdf/2012.09138.pdf) - Authors implement extraction of Coq programs to functional languages based on MetaCoq's certified erasure. 

- [Trustless, privacy-preserving blockchain bridges](https://arxiv.org/pdf/2102.04660.pdf) - In this paper, authors present a protocol for facilitating trust-less cross-chain cryptocurrency transfers that preserve privacy of bridge withdrawals.

- [Measuring Financial Advice: aligning client elicited and revealed risk](https://arxiv.org/pdf/2105.11892.pdf) - This paper compares client Know Your Client (KYC) profile risk allocations to their investment portfolio risk selections using a value-at-risk discrepancy methodology.

- [Security checklists for Ethereum smart contract development: patterns and best practices](https://arxiv.org/pdf/2008.04761.pdf) - Authors cover the phases of design, coding, and testing and deployment of the software lifecycle.

- [Dynamic Vulnerability Detection on Smart Contracts Using Machine Learning](https://arxiv.org/pdf/2102.07420.pdf) - In this work authors propose Dynamit, a monitoring framework to detect reentrancy vulnerabilities in Ethereum smart contracts. 

- [Detecting Malicious Accounts showing Adversarial Behavior in Permissionless Blockchains](https://arxiv.org/pdf/2101.11915.pdf) - Authors identify that Neural Networks (NN) holds up the best in the face of such bias inducing dataset at the same time being robust against certain adversarial attacks.

- [Targeting the Weakest Link: Social Engineering Attacks in Ethereum Smart Contracts](https://arxiv.org/pdf/2105.00132.pdf) - In this work, authors explore the possibility and existence of new social engineering attacks beyond smart contract honeypots.

- [OptSmart: A Space Efficient Optimistic Concurrent Execution of Smart Contracts](https://arxiv.org/pdf/2102.04875.pdf) - In this paper, authors develop a concurrent miner that proposes a block by executing the AUs concurrently using optimistic Software Transactional Memory systems (STMs).

- [The Doge of Wall Street: Analysis and Detection of Pump and Dump Cryptocurrency Manipulations](https://arxiv.org/pdf/2105.00733.pdf) - Authors monitored crypto chats for more than 3 years detecting and analysing around 900 individual events. Then, authors move on to the crowd pump, a new phenomenon that hit the news in the first months of 2021, when a Reddit community inflates the price of the GameStop stocks (GME) and XRP with Dogecoin.

- [DEFECTCHECKER: Automated Smart Contract Defect Detection by Analyzing EVM Bytecode](https://arxiv.org/pdf/2009.02663.pdf) - Experimental results show that DefectChecker performs much better than these tools in terms of both speed and accuracy. 

- [SmartBugs: A Framework to Analyze Solidity Smart Contracts](https://arxiv.org/pdf/2007.04771.pdf) - Authors show how it enables easy integration and comparison of analysis tools by presenting a new extension to the tool SmartCheck that improves substantially the detection of vulnerabilities related to the DASP10 categories Bad Randomness, Time Manipulation, and Access Control (identified vulnerabilities increased from 11% to 24%).

- [Profiling Gas Leaks in Solidity Smart Contracts](https://arxiv.org/pdf/2008.05449.pdf) -  In this paper, authors identify a set of 19 Solidity code smells affecting the deployment and transaction costs of a smart contract, and assess the relevance of such smells through a survey involving 34 participants. 

- [Securing Parallel-chain Protocols under Variable Mining Power](https://arxiv.org/pdf/2105.02927.pdf) -  In this paper, authors consider the design of provably secure parallel-chain protocols which can adapt to such mining power variations. 

- [Blockchain in Cyberdefence: A Technology Review from a Swiss Perspective](https://arxiv.org/pdf/2103.02606.pdf) -  Review is targeted to readers with little prior domain knowledge as a support to decide where it makes sense to use a blockchain and where a blockchain might not be the right tool at hand.

- [Ethereum SmartContract Vulnerability Detection using Deep Neural Network and Transfer Learning](https://arxiv.org/pdf/2103.12607.pdf) - ESCORT framework enables transfer learning on new vulnerability types with minimal modification of the DNN model architecture and re-training overhead.

- [Detecting and Quantifying Wash Trading on Decentralized Cryptocurrency Exchanges](https://arxiv.org/pdf/2102.07001.pdf) - In this paper, authors illustrate how wash trading activity can be identified on two of the first limit order book-based exchanges on the Ethereum blockchain.

- [SCSGuard: Deep Scam Detection for Ethereum Smart Contracts](https://arxiv.org/pdf/2105.10426.pdf) - Experimental results manifest that SCSGuard achieves high accuracy (0.94), precision (0.96\%) and recall (0.98) for both Ponzi and Honeypot scams, and new Phishing smart contracts.

- [Securing Cyber-Physical Systems Through Blockchain-Based Digital Twins and Threat Intelligence](https://arxiv.org/pdf/2105.08886.pdf) - This article focuses on securing CPSs by integrating Artificial Intelligence (AI) and blockchain for intelligent and trusted DTs. 

### Coordinated disclosure

* [Blockchain Security Contacts](https://github.com/trailofbits/blockchain-security-contacts) - Security contact info for blockchain projects

### Blogs

* [Hacking Distributed](http://hackingdistributed.com/) - Emin Gün Sirer, professor in Cornell Tech’s IC3 lab focused on blockchain security.
* [Phil Does Security](https://pdaian.com/blog/) - Phil Daian, grad student behind KEVM, Hydra, and other Ethereum academic projects
* [Trail of Bits](https://blog.trailofbits.com/) - Cybersecurity R&D firm with a blockchain security practice
* [Martin Holst Swende](http://swende.se/) - Martin Swende, programmer and appsec consultant
* [SmartDec blog](https://blog.smartdec.net/) - Company blog about security issues and practices within blockchain ecosystem

### Notable blog posts

* [Contract upgrade anti-patterns](https://blog.trailofbits.com/2018/09/05/contract-upgrade-anti-patterns/)
* [How the winner got Fomo3D prize — A Detailed Explanation](https://medium.com/coinmonks/how-the-winner-got-fomo3d-prize-a-detailed-explanation-b30a69b7813f)
* [How to debug Solidity Smart Contracts with Tenderly and Truffle](https://medium.com/tenderly/how-to-debug-solidity-smart-contracts-with-tenderly-and-truffle-da995cfe098f)
* [Lashing out at a Spank Channel](https://medium.com/coinmonks/lashing-out-at-a-spank-channel-2b42b23f0dc6)
* [Malicious GasToken Minting](https://medium.com/level-k/public-disclosure-malicious-gastoken-minting-236b2f8ace38)
* [Missing return value bug in ERC20 tokens](https://medium.com/coinmonks/missing-return-value-bug-at-least-130-tokens-affected-d67bf08521ca)
* [Not A Fair Game – Fairness Analysis of Dice2win](http://blogs.360.cn/post/Fairness_Analysis_of_Dice2win_EN.html)
* [Initial Formal Verification of Ethereum Casper Protocol](https://runtimeverification.com/blog/runtime-verification-completes-formal-verification-of-ethereum-casper-protocol/)
* [Security considerations for Shamir's secret sharing](https://ethresear.ch/t/security-considerations-for-shamirs-secret-sharing/4294)
* [SmartDec smart contract audit beginner's guide](https://blog.smartdec.net/smartdec-smart-contract-audit-beginners-guide-d04cc7f1c571)
* [The Anatomy of a Block Stuffing Attack](https://osolmaz.com/2018/10/18/anatomy-block-stuffing/)
* [The phenomenon of smart contract honeypots](https://medium.com/@gerhard.wagner/the-phenomena-of-smart-contract-honeypots-755c1f943f7b)
* [Use our suite of Ethereum security tools](https://blog.trailofbits.com/2018/03/23/use-our-suite-of-ethereum-security-tools/)
* [Vertcoin (VTC) was successfully 51% attacked](https://medium.com/coinmonks/vertcoin-vtc-is-currently-being-51-attacked-53ab633c08a4)

### Conference talks

| Title | Conference | Year |
| --- | --- | --- |
| [Predicting Random Numbers in Ethereum Smart Contracts](https://schd.ws/hosted_files/appseccalifornia2018/00/AppSecCali%202018%20-%20Predicting%20Random%20Numbers%20in%20Ethereum%20Smart%20Contracts.pdf) | OWASP AppSec | 2018 |
| [Blockchain Autopsies - Analyzing Smart Contract Deaths](https://github.com/trailofbits/publications/tree/master/presentations/Blockchain%20Autopsies%20-%20Analyzing%20Smart%20Contract%20Deaths) | Blackhat USA | 2018 |
| [Rattle - an EVM binary analysis framework](https://www.trailofbits.com/presentations/rattle/) | reCON | 2018 |
| [Blackhat Ethereum](https://github.com/trailofbits/publications/blob/master/presentations/Blackhat%20Ethereum) | CanSecWest | 2018 |
| [Smashing Ethereum Smart Contracts for Fun and Profit](https://github.com/b-mueller/smashing-smart-contracts) | HITB Amsterdam | 2018 |
| [Automatic Bug Finding for the Blockchain](https://github.com/trailofbits/publications/blob/master/presentations/Automatic%20bugfinding%20for%20the%20blockchain) | EkoParty | 2017 |

### Podcasts and Episodes

#### Podcasts

* [CoinSec Podcast](https://coinsecpodcast.com/)
* [The Smartest Contract](http://www.thesmartestcontract.com/)
* [Zero Knowledge](http://www.zeroknowledge.fm/)

#### Episodes

* [The Smartest Contract #15](http://www.thesmartestcontract.com/15) - Trail of Bits’ Outlook on Security w/ JP Smith
* [The Smartest Contract #8](http://www.thesmartestcontract.com/8) - Smart Contract Security and Honeypots w/ Gerhard Wagner
* [Zero Knowledge #29](http://www.zeroknowledge.fm/29) - The DAO, the White Hat Hacker Group & Giveth w/ Griff Green
* [Zero Knowledge #16](http://www.zeroknowledge.fm/16) - Talking security with JP Smith from Trail of Bits
* [Risky Business #488](https://risky.biz/RB488/) - JP Smith about all things blockchain

## Tools

### Visualization

* [ethereum-graph-debugger](https://github.com/fergarrui/ethereum-graph-debugger) - A graphical EVM debugger. Displays the entire program control flow graph.
* [Slither](https://github.com/trailofbits/slither) - Slither can map method visibility and modifiers, state variables that are read and written, calls, and can print the inheritance graph of a smart contract
* [Solgraph](https://github.com/raineorshine/solgraph) - Generates DOT graphs with function control flow of a solidity contract
* [Surya](https://github.com/ConsenSys/surya) - Generates various visual outputs of function call graphs
* [sol-function-profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler

### Linters

* [Remix](https://remix.ethereum.org/) - Browser-based Solidity IDE with linting features
* [SmarrtCheck](https://tool.smartdec.net/) - A linter for Solidity and Vyper that checks code for security issues and bad practices.
* [Solhint](https://github.com/protofire/solhint) - Linter for both security and style-guide validations. It strictly adheres to the [Solidity Style Guide](https://solidity.readthedocs.io/en/latest/style-guide.html).
* [Solium](https://github.com/duaraghav8/Solium) - Linter for both security and style-guide validations. Does not strictly adhere to the Solidity Style Guide.

### Bug finding tools

* [Echidna](https://github.com/trailofbits/echidna) - Fuzzer for Ethereum smart contracts. Uses property testing to generate malicious inputs that break smart contracts.
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for Ethereum smart contracts that includes detectors for common security flaws
* [Mythril OSS](https://github.com/ConsenSys/mythril/) - Open-source security analysis tool for Ethereum smart contracts built around detector modules
* [Securify](https://github.com/eth-sri/securify) - Static analysis tool from ChainSecurity
* [Slither](https://github.com/trailofbits/slither) - Static analysis framework, written in Python, with detectors for many common Solidity issues

### Verification tools

* [KEVM](https://github.com/kframework/evm-semantics) - K Semantics of the Ethereum Virtual Machine (EVM)
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for EVM

### Reversing tools

* [abi-decompiler](https://github.com/beched/abi-decompiler) - EVM reverse engineering helper utility
* [ethereum-dasm](https://github.com/tintinweb/ethereum-dasm) - EVM disassembler with static and dynamic analysis abilities, including function signature lookup
* [Ethersplay](https://github.com/trailofbits/ethersplay) - Visual disassembler for EVM bytecode built on Binary Ninja
* [evmlab](https://github.com/ethereum/evmlab) - Utilities for interacting with the Ethereum virtual machine
* [IDA-EVM](https://github.com/trailofbits/ida-evm) - IDA plugin to view EVM instructions
* [Panoramix](http://eveem.org/about)
* [pyevmasm](https://github.com/trailofbits/pyevmasm) - EVM assembler and disassembler with a CLI and a Python API
* [Rattle](https://github.com/trailofbits/rattle) - EVM binary static analysis framework. Produces SSA representations of EVM code.

### Custody

* [Subzero](https://medium.com/square-corner-blog/open-sourcing-subzero-ee9e3e071827) - Subzero is an HSM-backed method for cold storage of Bitcoin developed by Square

## Communities

* [Enterprise Ethereum Alliance Security Task Force](https://entethalliance.org/working-groups/)
* [Empire Hacking Slack](https://empireslacking.herokuapp.com/) #ethereum

## Other Awesome Lists

* [Awesome AppSec](https://github.com/paragonie/awesome-appsec)
* [Awesome Ethereum Virtual Machine](https://github.com/pirapira/awesome-ethereum-virtual-machine)
* [Awesome Solidity](https://github.com/bkrem/awesome-solidity)
* [Crypto projects that might not suck](https://github.com/sweis/crypto-might-not-suck)

## Contributing

We welcome contributions that help curate this awesome list. Please refer to the [contributing guidelines](CONTRIBUTING.md) when submitting PRs. Thanks!
