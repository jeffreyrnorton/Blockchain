# Blockain

## References

[Six Month Free Trial to IBMs Blockchain Platform](https://www.ibm.com/account/reg/us-en/signup?formid=urx-32737)

[Solidity Documentation](https://solidity.readthedocs.org/en/latest/)  
[Ethereum.org](https://www.ethereum.org/)  
[Dapp Development Resources](https://github.com/ethereum/wiki/wiki/Dapp-Developer-Resources)

From [Hackernoon](https://hackernoon.com/getting-started-with-smart-contracts-3085611c95de):

[A 101 Noob Intro to Programming Smart Contracts on Ethereum](https://medium.com/@ConsenSys/a-101-noob-intro-to-programming-smart-contracts-on-ethereum-695d15c1dab4)  
[Getting Started as an Ethereum Web Developer](https://hackernoon.com/getting-started-as-an-ethereum-web-developer-9a2a4ab47baf)  
[How to deploy the smart contract](https://medium.com/hci-wvu/hello-world-in-solidity-3e7d3e025831)
[How to build your first Ðapp through web3.js](https://medium.com/hci-wvu/how-to-build-your-first-%C3%B0app-fe0c89d8f95f)  
[A simple smart contract Web UI using web3.js](http://hypernephelist.com/2016/06/21/a-simple-smart-contract-ui-web3.html)  
[Hyper-ledger Fabric and It’s purposes](https://medium.com/hci-wvu/hyper-ledger-fabric-and-its-purposes-c07d9973ad41)  
[The ultimate Ethereum blockchain startup guide](https://hackernoon.com/an-entrepreneur-programmer-and-user-walk-into-a-smart-contract-the-ultimate-ethereum-blockchain-7b8dbd0c8463)  
[Ethereum vs HyperLedger](https://blockchaintrainingalliance.com/blogs/news/ethereum-vs-hyperledger)  

# Blockchain Course

These are the [notes](https://gist.github.com/daqo/cb80cc8cc353145758ad588a01676293) taken on “IBM blockchain Essentials for Developers” course on Coursera [IBM Blockchain Foundation for Developers | Coursera](https://www.coursera.org/learn/ibm-blockchain-essentials-for-developers/) by Ant Cole.

A similar course from Ant Cole is offered through [CognitiveClass.ai](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/info) and it is **free**.

## Jargon 
*Ledger*: the system of record for a business

*Transaction*: an asset transfer onto or off the ledger

*Contract*: conditions for transaction to occur

*Blockchain*: a trusted distributed ledger with shared business processes

[What is Blockchain?](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/407a9f86565c44189740699636b4fb85/eeb5c3a61ee64258aedcb7865218ada2/)

## Blockchain in Business

[The Business Backdrop](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/407a9f86565c44189740699636b4fb85/12eab34ec218468995e4d06566ef4a32/)

[The Problem Area](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/407a9f86565c44189740699636b4fb85/5954a0d4016a4346b83ff34bd5edef84/)

## Bitcoin

[Blockchain relationship to Bitcoin](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/407a9f86565c44189740699636b4fb85/0bbe2601174649b78e44d5721ab666b7/)

* An unregulated shadow currency
* it has property of anonymity
	* we don’t know who we are sending a bitcoin to
	* we don’t know whom we are receiving a bitcoin from
* it’s very compute resource intensive to make the bitcoin network work

## Using blockchain for businesses is different from using it in bitcoin
* we prioritize identity over anonymity
* we prioritize selective endorsement over proof of work (we get to choose who in the network will validate a particular transaction - it’s more computationally efficient than bitcoin
* we prioritize assets over cryptocurrencies

## Requirements for blockchain for business
* Shared ledger: append-only distributed system of record shared across business network
* Privacy: ensuring appropriate visibility; transactions are secure, authenticated and verifiable
* Smart Contracts: business terms embedded in transaction database and executed with transactions
* Trust: transaction are endorsed by relevant participants

[Requirements for a blockchain in a business environment](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/407a9f86565c44189740699636b4fb85/570a870ea5764dbf85ed5c91a915648e/)
[Requirements Deep Dive](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/407a9f86565c44189740699636b4fb85/88647e58e1714e4385860469a3244460/)  
[Smart Contracts](https://blockgeeks.com/guides/smart-contracts/)  

### Going more in depth:

##### Shared ledger
* Shared between participants
* Participants have their own copy thru replication
* Permissioned: the participants only see appropriate transactions
* THE shared system of record

##### Smart Contract
* Smart contract is the way of encoding and sharing the shared business process in blockchain.
* you take the english contract and encode it in a programming language
* they are verified
* they are signed

##### Privacy 
* transactions need to be authenticated
* participants need an identity not linked to a transaction
* participants need appropriate confidentiality between subsets of participants
* making sure that blockchain is tamper-proof

##### Trust
* selected members from business network endorse the transactions.
* when transactions are endorsed they are added to the blockchain.
* this gives us the concept of Verifiable Audit Trail
	* transactions cannot be modified, inserted or deleted
* The concept of trust is achieved via:
	* consensus
	* provenance
	* immutability
	* finality

Discussion Prompt: Discussion prompt
---
Week 2

Blockchain for business has several advantages:

[Why is Blockchain Relevant for Business](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/76d637cbe8024e509dc445df847e6c3a/2d204ac4fa3143048a998da7e53702d7/)

* Saves time: transacti)on time becomes instantenios
* Reduces cost: removes overheads and cost intermediaries
* Reduces risk: tampering, fraud and cyber crime
* Increases trust: thru shared processes and record keeping

Example: For example, for financial services network, a business network that runs on a blockchain can speed up transaction processes and audits. That in turn reduces costs and can lead to greater customer satisfaction. A business that runs a supply chain network can benefit from blockchain by reducing errors in shipments, have better tracking or materials, and reduce the risk of illicit tampering of records.

Pop Quiz: 
Q: A traditional, or nonblockchain, network is more vulnerable to tampering. What main component of a blockchain network reduces this risk?
A: Distributed ledgers

## Industry use cases

[Consensus: Shared Reference Data Example](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/76d637cbe8024e509dc445df847e6c3a/6c377c9edbc6442c8612bee3250e9639/)  

#### Financial 
* Trade finance
* Cross currency payment
* Mortgages
#### Public Sector
* Asset Registration
* Citizen Identity
* Medical Records
* Medicine Supply Chain
#### Retail
* Supply Chain - [Provenance: Supply Chain Example](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/76d637cbe8024e509dc445df847e6c3a/87a6f38e1c6f407b86a1aabbb5e326c2/)
* Loyalty programs
* Information Sharing (supplier - retailer)
#### Insurance
* Claims processing
* Risk Provenance
* Asset usage history
* Claims file
#### Manufacturing
* Supply Chain
* Product Part
* Maintenance tracking

If the business network in your use case doesn’t exist, the chances are it’s not a good candidate for blockchain implementation. We can render it with a more traditional technology. 

There are four test words to find out whether the candidate is a good blockchain use case:
* Consensus
* Provenance
* Immutability - [Immutability: Audit and Compliance Example](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/76d637cbe8024e509dc445df847e6c3a/d5af8a2edda048bb9b256904e0ae9193/)
* Finality - [Finality: Letter of Credit Example](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/76d637cbe8024e509dc445df847e6c3a/dd11d1805d744541a5dba3a0f8662968/)

These four are key elements to achieve trust in blockchain.

[Industry Use Cases](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/76d637cbe8024e509dc445df847e6c3a/23da3ac2218f4ea2b03e9393b47246dc/)

## Patterns for customer adoption
Key to success: don’t try to boil the ocean, and don’t go for the big high powered, high fluted use case first. Look for something small and a room for improvement. 

A hierarchy of different usages in listed below. As you move downward. It’s much easier to start with something on the compliance ledger and work your way up the stack than really trying to start higher.

[Customer Adoption](https://courses.cognitiveclass.ai/courses/course-v1:developerWorks+BC0101EN+v1/courseware/76d637cbe8024e509dc445df847e6c3a/01e732ada7cd49cc9d4f185340a18987/)

#### Compliance Ledger (easiest to implement)
* Real-time view of compliance, audit & risk data
* Provenance, immutability & finality are key
* Transparent access to auditor & regulator
#### Consortium Shared Ledger
* Created by a small set of participants
* Share key reference data
* Consolidated, consistent real-time view
#### Asset Exchange
* Sharing of assets (voting, dividend notifications)
* Assets are information, not financial
* Provenance & finality are key
#### High Value Market (hardest to implement)
* Transfer of high value of financial assets
* Between many participants in a market
* Regulatory timeframes

So customers need to go thru an awareness journey to understand what like smart contracts can do for their business, and how can they improve the operations in their network using blockchain. 


## Key players for blockchain adoption
#### Regulator
* An organization who enforces the rule of play
* like a national bank
#### Industry Group
* Often funded by members of a business network
* Provide technical advice on industry trends
* Encourages best practice by making recommendations to members
#### Market Maker
* The organization who innovates
	* Creates a new good or service, and business process 
	* Creates a new business process for an existing good or service

We can start with any of the aforementioned players or even with a combination of them

---
Week 3

## Summary
IBM is a premier member of the Linux Foundation Hyperledger Project, which is an open source, collaborative effort that seeks to advance blockchain technologies. IBM also offers the IBM Blockchain Platform that can help you build and operate a complete business network. The Platform also provides tools to help you align the needs of developers and business leaders in your organization.
Transferring assets is the heart of blockchain. How can people buy and sell or transfer goods in a business network without any central governing body or policy?  (Look at web demo) [Hyperledger Composer](http://composer-playground.mybluemix.net/)

---
Week 4

## Hyperledger Composer
* A suite of high level application abstractions for business networks
* We model at the level of assets, participants and …
* It enables a quick solution creation for us

### Features
* Model your business network, test and deploy
* Applications use APIs to interact with a business network
* Integrate existing systems of record using loopback/REST

### Benefits
* Increases understanding: bridges simply from business concepts to blockchain
* Saves time: develop blockchain applications more quickly and cheaply
* Reduces risk: well tested, efficient design conforms to best practice
* Increases flexibility: Higher level abstraction makes it easier to iterate

Hyperledger Fabric is like the operating system. Hyperledger Composer is like the API.

### Conceptual Components and Structure
Business network is defined by *Models*, *Script Files*, *ACLs* and *Metadata* and packaged in a *Business Network Archive*.

#### Logic of business network is held in Script files
When a transaction is submitted, the blockchain run time is going to find the script functions that are interested in that transaction and then run them. And those script functions can have side effects on assets that are being managed in asset registries.

---

Week 5

## Components in a Blockchain
Ledger: A ledger is a channel’s chain and current state data which is maintained by each peer on the channel

Smart Contract: Software running on a ledger, to encode assets and the transactions instructions for modifying the assets

Peer network: A broader term overarching the entire transactional flow, which serves to generate an agreement on the order and to confirm the correctness of the set of transactions constituting a block.

Membership: membership services authenticates, authorizes and manages identities on a permissioned blockchain network

Events: creates notifications of significant  operations on the blockchain (e.g. a new block), as well as notifications related to smart contracts

Systems management: provides the ability to create, change and monitor blockchain components

Wallet: Securely manages a user’s security credentials

Systems Integration: Responsible for integrating blockchain bi-directionally with external systems. Not part of the blockchain


## Blockchain developer
Developers care about application and smart contracts.
They don’t care about peers, consensus and security


## Ledger’s data structure

A ledger often consists of two data structures: blockchain and world state

Blockchain is:
* A linked list of blocks
* Each block describes a set of transactions
* Immutable - blocks cannot be tampered

And also we have world’s state:
What it does is to record the current state of all your assets. 

World State is:
* An ordinary database (e.g. key/value store)
* Stores the combined outputs of all transactions
* Not usually immutable

## Consideration for the blockchain operator
Operators’ interests are in the deployment and operation of part of the blockchain:
* Peers
* Consensus
* Security

They don’t care about development concerns, such as:

* Application Code
* Smart Contract Code
* Events and Integration

Examples: 
* They make sure that peers are up to date. 
* Making them work together in the way that they should. 
* Ensuring that consensus is happening in the way that it should be taking place. 
* What security methods do we need? 

## How do we reach consensus
Consensus is the process of maintaining a consistent ledger

Consensus helps us to:
* keep all peers up-to-date
* fix any peers in error
* quarantine all malicious nodes

Some examples of consensus algorithms:

* Proof of work
* Proof of stake
* Solo
* Kafka/Zookeeper
* Proof of elapsed time
* PBFT-based (Hyperledger fabric uses this)

## Public vs. Private blockchains

Public: 
	* For example Bitcoin
	* Transactions are viewable by everyone
	* Participant identity is almost impossible to infer
Private: 
	* For example Hyperledger Fabric
	* Network members are known but transactions are secret

## Architect consideration
Architect should care about the following:
* Performance
	* amount of data being shared
	* number and location of peers
	* latency and throughput
	* batching characteristics
* Security 
	* type of data being shared and with whom
	* how is identity achieved
	* confidentiality of transaction queries
	* who verifies transactions
Resiliency
	* resource failure
	* malicious activity
	* no-determinism
