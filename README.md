# Blockchain

**What is blockchain?**

**Hash Cryptography?**
- SHA256 is developed by NSA
- There are 5 requirements for hash algorithm:
  - One way
  - Deterministic
  - Fast computation
  - The avalanche affect 
  - Must withstand collision 

**Imutable ledger**

**Distributed P2P network**
- Users in blockchain network can be connected each other. Each user has blockhain of system. 
- When a user insert a block into blockchain, rest of user will update their blockchain.

**Mining**
- This is while loop, to increase Nounce, one of element in Block, calculate the hash of block to satafied the target format. For example: 8 zero lead in the hash.

**Why mining**?
- The block needs to be mined to brings the actual value into currency, by mean of creating arfifical scarity. If there wouldn't be any difficulity to create new block, the currency would be worthless. 
- Rule of thumb: your blockchain does not demand you to have a nonce to be valid. It just depends on what it is made for and who will use it.
- If it's a cryptocurrency, you need a nonce because that is the only way you can regulate the production of fresh currency in your system. In the financial world, central banks are creating fresh money. Ideally, they are adding money overall, as much as wealth is created by the country using that money (e.g., the US have an average of 4% GDP increase per year, so to ensure there are enough circulating Dollars, the Federal Reserve would increase the total mass of Dollars circulating by 4%, emitting new Dollars: and that is how you make and maintain the face value of a money compare to the others. If the Fed creates more Dollars, it will then start to devaluate compare to other currencies, if it creates less Dollars, it will start to increase its value compare to other currencies). With a cryptocurrency, no central authority is creating the currency (I will use Bitcoins as an exemple), so the workaround was to come up with a way to add  more Bitcoins. But this way has to be burdensome, otherwise too many Bitcoins would be created too easily and, very quickly, Bitcoins would worth just nothing at all (if you could easily create as much Bitcoin as you'd like, it would turn into Monopoly money :D) Hence the crypto puzzle: it's the way to create fresh Bitcoins, and regulate a low creation rate to maintain the value of Bitcoins on a whole. And, of course, it serves as well as incentive to people who are willing to maintain the blockchain of Bitcoins transactions, otherwise no-one would do it and, again, your crypto would crumble.
- But if your blockchain serves another purpose, you might not need nonce and crypto puzzle at all. Let's get back to the previous exemple of estate transactions of property ownership: if all the estate agents and tax services of a country could agree upon, they would gladly maintain a blockchain of all estate transactions and accept to be part of its distributed network. The insurance, for tax services, to automatically collect taxes on each sales and the insurance, for estate agents, to have a very practical and reliable tool to keep traces of transactions, is most certainly enough of an incentive. And in this situation you don't need to create a reward or wealth out of the processing of a transaction in your chain.


