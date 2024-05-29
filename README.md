# Blockchain

First, we should know this is just a data structure like the others! It is not a separate layer in the network that we have to merge them! :pinched_fingers: <br>
<p align="justify">
With blockchain technology, we can create an environment in which nodes that do not trust one another can share data they can trust. The idea is based on several concepts that are simple to consider but difficult to put into practice. First, data is logically presented as a ledger. The data isn't really stored that way; you can just think of it as a ledger.
</p>

:bulb: Let's have an abstraction about BC first:
* A ledger is a way of recording data as transactions occur.
* You can only add data to a ledger. You cannot change anything after you've added it. So, the only two operations you can perform on this ledger are <b>"add"</b> and <b>"read"</b>.
* Data is added to this ledger in blocks. blocks are collections of transactions, each with an owner's address.
* Addresses are the unique IDs of accounts in our ledger system.
* When there are enough transactions to make a new block, some of the blockchain participants begin the process of adding a new block to the ledger.
* Each new block is linked to the previous block, making a chain.
* Then, The entire set of blocks, or the entire blockchain, is shared with other participants that are called nodes.
* These nodes communicate with one another and each store an exact copy of the blockchain.
* <p align="justify">Before any new block is added to the blockchain, a majority of nodes must agree that the new block is valid. All nodes agree to accept the majority decision. That's how the blockchain stays in sync.</p>
* Nodes essentially vote on all new blocks. Different blockchains use different voting methods (e.g. solving very hard mathematical puzzles).
* Each node periodically scans the blockchain to ensure that nothing has changed. This is how nodes can be sure that the blockchain is the same across the entire network.

<p align="justify">
Putting it all together, a blockchain makes it possible to share a set of data with many nodes that you don't trust. You can trust the democracy of the network, though. <b>As long as you can trust that more than half of the nodes on the blockchain network are going to be honest, you can trust the blockchain.</b>
</p>

### Smart Contract
<p align="justify">
The last big advantage to blockchain is that you can put rules of operation in blocks on the BC as well. These rules are called "<em>smart contract</em>". A smart contract is just a program that lives in a blockchain block and governs how data is added to the BC. Because all blockchain data is immutable, even the smart contract code is immune from changes.
</p>

<p align="justify">
  For example, suppose you want to buy a car. You have enough digital currency in your blockchain account to buy the car, and the car owner has the car’s title stored in the blockchain. You can offer to buy the car and if the seller accepts your offer, a smart contract handles the transaction.
The smart contract would verify that the title is owned by the seller and that you have enough money in your account to 
make the purchase. If those two requirements are met, the smart contract will
transfer the sales amount into the seller’s account and transfer the title to your
account. Without any middleman, you have purchased a car and paid for it without
carrying a wad of cash around.
</p>

<p align="justify">
Of course, you really purchased a title to a car. Blockchain handles digital assets You still have to physically get the keys and the car from the seller!
</p>

## Ethereum

