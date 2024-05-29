# Blockchain

First, we should know this is just a data structure like the others! It is not a separate layer in the network that we have to merge them! :pinched_fingers: <br>
<p style="text-align: justify;">With blockchain technology, we can create an environment in which nodes that do not trust one another can share data they can trust. The idea is based on several concepts that are simple to consider but difficult to put into practice. First, data is logically presented as a ledger. The data isn't really stored that way; you can just think of it as a ledger.</p>

:bulb: Let's have an abstraction about BC first:
* A ledger is a way of recording data as transactions occur.
* You can only add data to a ledger. You cannot change anything after you've added it. So, the only two operations you can perform on this ledger are <b>"add"</b> and <b>"read"</b>.
* Data is added to this ledger in blocks. blocks are collections of transactions, each with an owner's address.
* Addresses are the unique IDs of accounts in our ledger system.
* When there are enough transactions to make a new block, some of the blockchain participants begin the process of adding a new block to the ledger.
* Each new block is linked to the previous block, making a chain.
* Then, The entire set of blocks, or the entire blockchain, is shared with other participants that are called nodes.
* These nodes communicate with one another and each store an exact copy of the blockchain.
* <p style="text-align: justify;">Before any new block is added to the blockchain, a majority of nodes must agree that the new block is valid. All nodes agree to accept the majority decision. That's how the blockchain stays in sync.</p>
* Nodes essentially vote on all new blocks. Different blockchains use different voting methods (e.g. solving very hard mathematical puzzles).
* Each node periodically scans the blockchain to ensure that nothing has changed. This is how nodes can be sure that the blockchain is the same across the entire network.

<p style="text-align: justify;">Putting it all together, a blockchain makes it possible to share a set of data with many nodes that you don't trust. You can trust the democracy of the network, though. <b>As long as you can trust that more than half of the nodes on the blockchain network are going to be honest, you can trust the blockchain.</b></p>

