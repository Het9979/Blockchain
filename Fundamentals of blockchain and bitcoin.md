
What is Blockchain?
Blockchain is a decentralized and distributed ledger that can be used for storing information in multiple locations without any centralized monitoring system. This allows people to store and securely transfer information and currency instantly. The transfer of information in blockchain acts as peer-to-peer without any middlemen or intermediaries.
Ex:- in case of money transferring we depend on banks that will verify and validate our transactions . these acts as intermediaries in our communication & transaction . blockchain eliminates this intermediaries and offer new way of communication.
Structure of Block:
In blockchain the data is stored in the form of blocks . the blocks later form a chain with other blocks of information, forming a blockchain.
Block contains information on transactions happening on a blockchain for cryptocurrency. These blocs are chained together by adding the previous block’s hash to the next block’s header.
The structure of block is different for every blockchain. The general structure if the block is as follows:

 ![image](https://user-images.githubusercontent.com/80376658/223030116-14cca8c5-6495-4fa4-8850-3703a52c6459.png)
A block consists of two main parts:
•	Header
•	Body
Header:
A block’s header contains information about the block and the miner. It is further divided into subparts which are as follows:
1.	Previous block’s hash: This is the hash of the previous block. It chains the block together and makes the data in the previous block immutable. If data in the previous block is changed , then hash if that block will change causing the unchaining of the blockchain. 
2.	Other block header fields: These fields can vary depending on the different requirements of different blockchains. 
a.	Nonce: this is an integer that a miner changes to change the hash of the block to achieve the network’s difficulty.
b.	Timestamp: This is the time at which the block was mined. 
c.	Difficulty:  it is the current difficulty level on the network.
d.	Merkel root hash: It is the hash of all the hashes of all the transactions that are part of a block in blockchain network.
e.	Block height: The number of blocks mined between the genesis block and the current block.
Body: It includes all the data stored in the block , such as transactions. Every blockchain has different format for storing transactions . An array of transactions is stored in the body of the block.
Merkle Root Hash diagram:
 
 ![image](https://user-images.githubusercontent.com/80376658/223030287-582b7f54-d9e7-4440-be05-b85a09a7e111.png)

Working of Blockchain:
Blockchain works in a decentralized way. It allows thousands of computer(nodes) to maintain its records. When a user creates a transaction over a blockchain network the requested transaction is broadcasted over the peer-to-peer network. The nodes in the network then validate the transaction. Once the transaction is validated , it is grouped with other verified transactions to create a new block. This block is then secured using the cryptographic principles . Each node in the network will create a block. From this one block is selected by the network using some selection criteria. This block is then added to the existing blockchain network confirming that it is secure and immutable.
Features of Blockchain:
1.	Immutable: every action is recorded and distributed in blockchain. It is timestamped and secured using cryptography. Once a block gets committed onto the blockchain , it cannot be modified, even if we want to.
2.	Decentralized system: Blockchain system is decentralized. There is no centralized authority for controlling the blockchain. A public blockchain is fully decentralized.
3.	Better security: blockchain transactions are cryptographically validated. Cryptography makes blockchain secure and edit-proof.
4.	Distributed peer-to-peer Network: distributed network enables sharing the ledger among network participant nodes.
How is bitcoin different from fiat currency?
Central jurisdictions like Bank/ government issue the fiat currency. It is a legal tender. Bitcoin isn’t issued or backed by any jurisdiction. Thus , no legal tender status for bitcoin. Fiat currency is in physical form whereas bitcoin is a virtual currency therefore, it cannot be printed.
Types of Blockchain: 
Based on the level of decentralization and access blockchains can be classified as follows.
Public Blockchain:  It is open to public and is not owned by anyone. Anyone with internet and computer can participate , all nodes hold copy of other nodes or block present in the network.
Eg: bitcoin , Ethereum.
Private Blockchain: it is not open to public and a single entity governs it. Used only when the participants of the network are known to each other. Operated in closed network and only a few are allowed to participate within in organization.
Eg: ripple.
Consortium Blockchain: Combines the features of public and private blockchains. It may not be accessible to the public. Multiple parties will be part of the network. Access to the network will be restricted.
Eg: Hyperledger Corda.
Difference between permissioned and permissionless blockchain?
Permissioned	Permissionless
Also known as private or permissioned sandbox.	Also known as public or trustless.
These are closed networks , only a set of groups are allowed to validate transactions or data in a given blockchain network.	These are open networks, available for anyone to participate in the blockchain process that use to validate the transactions or data. 
Used where high privacy and security are required.	Used in networks where high transparency is required.


Transactional flow difference between normal transaction and blockchain transaction with example.
 	 
Normal Transaction Flow:

![image](https://user-images.githubusercontent.com/80376658/223030349-623a7662-94fa-4875-9518-f8776ffc8eda.png)

Transaction in Bitcoin:

![image](https://user-images.githubusercontent.com/80376658/223030416-ada97f5d-e1f9-470b-9f61-39c43dc86157.png)


What is better programmable or non-programmable blockchain?
Programmable blockchains are better because they can be used to do certain other tasks other than sending and receiving cryptocurrencies. Example of programmable blockchain is Ethereum and example of non-programmable blockchain is bitcoin.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
BITCOIN
White paper named: Bitcoin: A peer-to-peer electronic cash system. By SATOSHI NAKAMOTO.
Note: 
Bitcoin: is a piece of software used for communication.
Bitcoin: is a digital currency used for transactions.
Blockchain: is an underlying technology running bitcoin.
Components of Bitcoin Network:
There are 4 components of Bitcoin Network:
•	Software: Bitcoin is a piece of software that uses cryptography to regulate the transfer of bitcoin between two parties. 
•	Cryptography: it is set of techniques for secure communication.
•	Hardware: to run bitcoin, it need hardware like any other software application. Bitcoin network is composed of thousands of computers called nodes operating around the globe.
•	Miners: Nodes that solves computationally hard cryptographic puzzle. They are responsible for validating transactions and creating new blocks. They also get rewarded when they solve the puzzle.
Types of Node:
•	Full Node: it maintains the latest complete blockchain of the network. It verify the transaction without any external reference.
•	Lightweight Node: it does not keep a copy of the complete blockchain. They only store the header information of each block-saving the storage space. 
•	Miner Node:  it engages in the mining operation of the blockchain using appropriate consensus algorithm. They are responsible for validating transactions and creating new blocks.
•	Router Node:  it acts as a bridge in directing requests to the appropriate device for processing transactions.
UTXO:  Unspent Transaction Output which keeps track of the transactions and account balances in the bitcoin blockchain. Each bitcoin transaction has two parts: inputs and outputs. The input specifies the amount of bitcoin used for that transaction. The output specifies the amount and address of the recipient.
 
Consensus:
A single regulatory body makes decisions in a centralized setup. On the other side , no single authority makes decisions in a blockchain. Blockchain works on a consensus model. It helps blockchain nodes to comeup with a favourable solution. It ensures every network works properly even in the presence of faulty nodes.
Based on the selection and addition of new blocks to the blockchain , blockchain consensus is classified into two:
1.	Voting Based consensus: This method depends on voting mechanisms to finalize the block to be published. It achieves consensus by sending signed messages as votes. Eg: PBFT, RAFT.
2.	Lottery Based Consensus: the consensus mechanism depends on the chance-based lottery election model to select the block to be published. Eg: PoW, PoS.
PoW (Proof of Work):
Bitcoin uses Proof Of Work (PoW) as their consensus mechanism to select the leader. We know that consensus is the base factor for deciding the next block of the blockchain network. In a public blockchain like bitcoin, anyone can create a block. Each block will be different , and each block may contain different transactions. Therefore the network should choose a single block from the different candidate blocks to maintain the blockchain’s consistency.
Selection of blocks: the network selects a node as a leader. The leader node publishes the block it creates . According to proof of work , the nodes competing as leaders need to solve a cryptographic puzzle. Whoever solves the puzzle will be chosen as the leader. By checking the leader’s solution to the puzzle , the authenticity is determined. The nodes competing to solve the puzzle are mining nodes or miners. These miners are responsible for the creation of the new block in bitcoin. Miners get rewarded with a fixed amount of Bitcoins for adding new blocks.
The cryptographic puzzle involves finding a hash value below a certain threshold, such that the generated hash value will have a certain number of zeroes  preceding it. For solving the cryptographic puzzle miners calculate the hash of their block’s header. The hash value is compared to the desired threshold value. If the hash value is higher than the threshold value , the hash is recalculated by increasing the nonce number in the header. This process is repeated until a hash value lesser than the desired threshold is found.
The puzzle is set for 10 minutes. Once a node finds the solution , it can publish the block along with the solution, to the network. The solution to this puzzle can be verified easily but finding the solution is very difficult. In order to check the solution , the miners calculate the hash of the winning block’s header along with the nonce included in it. If the hash falls below the threshold , the block is valid. Other nodes in the network can easily check if the solution is valid or not and accept the block accordingly. In other words, the winning node provides proof of the work done to its peers, hence the name Proof of Work.
Bitcoin networks depend on an incentive mechanism. Miners validate the transactions and create blocks , gets bitcoin as rewards. This process is known as Bitcoin mining. Reward gets halved every 4 years.
The Difficulty level: as more and more nodes joined the bitcoin network , the solutions emerged more frequently and there was a more frequent generation of blocks and incentives. This was against the bitcoin economic model. The concept of difficulty helped with this problem . Difficult decides how frequently the miners can find the solution for the puzzle and publish the block. The average block creation time is around 10 minutes which varies when large number of nodes enter the network. To maintain the block creation time , the time is readjusted after every 2016th block. Eg: if block creation time is less than 10 seconds , threshold will be decreased and if the block creation time is more than 10 mins then threshold value is increased.
When the mining nodes pool their resources and share their computational powers over the network – these are called as mining pool.
PoS (Proof of Stake) :
Proof of stake links the mining power to the number of coins a person possess rather the computational power. In PoS, the miner is limited to mining a percentage of transactions reflective to their ownership stake. It emphasis on obtaining a distributed consensus. The more the stakes, the more is the mining power.
Bitcoin network is vulnerable to 51% attack. A 51% attack is when a miner or mining pool controls 51% of the network’s computational power and creates fraudulent transactions for himself while invalidation the transactions of other in the network. With Pos, the attacker would need to obtain the 51% of the cryptocurrency to carry out 51% attack. It would be difficult and expensive to accumulate 51% of the total coins, a miner with a 51% stake in the coin would not attack a network he holds the majority share.
Working: the individuals validating the transactions, creating new blocks are called forgers. In most PoS networks, the digital currency units are built at the currency’s launch, and their number is fixed. Therefore the forgers receive transaction fee as rewards instead of cryptocurrencies. A forger must first put their coins at stake to validate transactions and create blocks. If forger validate a fake transaction , they lose their coins and their rights to participate as a forger in future. 
Time is divided into epochs, which are further sub-divides into 32 slots of 12 seconds each. Before the start of an epoch , each slot is assigned a validator as a block proposer, and a specific group of validators called a committee. A validator can only be in one committee per epoch. There can also be more than one committee per slot. All the committee must of same size. During each slot , its block proposer will select a block to append to the existing chain, and the committee will vote to add this to the main chain. These votes are proofs and are weighted by the validator’s deposit. The validators broadcast their votes, and a block which gets a two-third majority of validators votes is accepted. The majority is decided based on the weight of deposits rather than the number of validators.
Selection Criteria in POS:
•	Randomized block selection
•	Coin age-based selection
Variants of PoS
•	Delegated PoS
•	Liquid PoS
•	Bonded PoS
•	Hybrid Pos
PBFT (practical Byzantine Fault Tolerance):
PBFT model ensures that the network will achieve sufficient consensus despite of the malicious nodes present in the system. A node in PBFT gets to be the leader or primary node for a fixed amount of time. The time duration is known as view. In a given view primary node is responsible for the creation of new blocks. The primary node will create a block and publish it to the network. Participating nodes will do the preliminary verification of the blocks in order to make sure it’s valid.
PBFT works efficiently in the asynchronous system. It is optimized for low overhead time.
It has three phases.
•	Pre-Prepare: Primary node send pre-pare message to all nodes [block ID, block Number, primary view number, primary node’s ID].
•	Prepare: Each node send prepare message to every node [block ID, block Number, node’s view number, node’s ID]. Nodes must wait till they receive 2f+1 matching prepare messages from their peers, where f is the maximum number of faulty nodes allowed. Once the node gets 2f+1 prepare messages , the messages get added to their internal log.
•	Commit: Each node will send a commit message to the entire network including themselves. The commit messages contain [block ID, block Number, primary view number, primary node’s ID]. Just like prepare phase , nodes wait until they receive 2f+1 matching commit messages , the messages gets added to the log and the block gets committed to the blockchain.
What will happen if a node does not receive 2f+1 messages?
This means that the network failed to reach an agreement regarding the proposed block, implying more than f nodes in the network are faulty. There can also be scenarios where the primary node becomes faulty. This will affect the working of the blockchain. In order to prevent such scenarios , each view has a time period. If the network couldn’t reach an agreement within the view , any node in the network can request a view change. In the next view, a new node will be elected as primary and the process gets repeated.
Variants of PBFT:
RBFT (redundant byzantine fault tolerance) : Hyperledger Indy
IBFT: Hyperledger Besu
SBFT (Speculative Byzantine Fault Tolerance) 
Forks:
•	HardFork: it is a permanent change that can occur as a result of change in the underlying software or the consensus algorithm used by the chain. They are not backward compatible. This type of forks results in splitting the blockchains into two separate branches. Network gets divided based on the branch they follow. Once hard fork occurs the branches will continue to exist as separate blockchains with a common parent chain.
•	SoftFork: it takes place when two mining nodes find the solution at the same time. There will be two valid blocks in the network and nodes will add both the blocks to the blockchain resulting in forking. To avoid chain splitting the network should choose one single branch. Miners use the longest chain rule to choose a branch. The longest chain is the chain with the most cumulative difficulty. If branches of same length are there , summation of the work of the branches is calculated . branch with the highest work is considered as the longest chain. Miner nodes start mining on top of the longest chain. The hash of the last block from the longest chain is added as the previous hash value in the newly created block. Eventually the longest chain is accepted and the blocks in other chains is discarded. To avoid situations of block getting discarded , the bitcoin network suggests users to wait until sic blocks are added on top of a block. Transaction is said to be confirmed if 6 blocks go after.
Stale Block: A block that was successfully mined but not included on the current longest blockchain, usually because the block at the same height was added to the chain first. There is no reward for mining stale blocks.
Orphan Block: Blocks whose parent blocks are not processed by the local nodes are known as orphan block. The orphan block cannot be validated so they are stored in the orphan block pool until their parent is processed.
Bitcoin Limitations:
•	Complex Architecture: PoW requires heavy and complex infrastructure and computation requires expensive hardware.
•	Uselessness of Computation: miners consume great power for their computational work. The consumption remains unused later.
•	51% attack:
•	Slow transaction time: Btc network has a block creation time of approx 10 minutes. 
•	High Energy Consumption:  PoW algorithm uses powerful ASIC machines that consume a lot of electricity.
•	Transaction Finality: if a transaction is final it cannot be rolled back. It’s permanently recorded and immutable. It is required for six confirmations in bitcoin for a transaction to be final.
