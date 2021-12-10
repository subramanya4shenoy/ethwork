# Ethwork
Project to build a system with  ethereum block chain. Building a supply chain project (from the tutorials)
decentralized Application to create your own token(crypto currency) and allow only the specific participants to do the purchase. And use the same token to be used in the supply chain.

Allowing only few participants because each time any read write operation happens in the block chain we need to pay a agasprice and that we dont want and this is just a first dApp created for testing on Ethereum network.

Creating a token based on commonly used ERC20 token. 

# Knowledge and Tool set Requiered
🥷 Truffle suite : To run the whole projects. takes care of boilerplate and environments. <br>
🥷 Ganache: Provides the test ether network with dummy 100eth (10 accounts) to test the smart contracts <br>
🥷 Solidity: Programing language to write the smart contract for block chain. <br>
<br>

# Additional Knowledge & tools: 
🥷 MetaMask : which is like a wallet, this holds your private key.

Boiler plate can be easily generated via Truffle. once done change the config to set the network port to point to test.
Test is nothing but Ganache, so keep the ganache up and running. and also update the port number in the boiler plate (default :7545).
Write your smart contracts and run it in ganache. 

# Conclution:
Not persuing on this project. It looked like blockchain and solidity might require few more years to catch up with developers and make things easier to integrate.

Solidy is still in version 0.8.x .

All the code looks like Boiler plates and templates.

Once deployed in main net there is a gas price to be payed (real money ~ Ether ~ crypto) which is a setback. Money gets deducted for each transaction. Even though the fee is less it doesn't makes any sense to deploy a test project in main net. Just the way a regular/pet projects we host, it will never be possible.

Currently, we use blockchain to a 'producer to consumer chained process'. Or a system which runs 100% autonomously without any user interventions. Best example of this is Currencies. Currencies are mined automatically and circulated and all the flow and transactions are kept in the network. each currency is nothing but a hash string. but this string is uniq and cannot be recreated (decoded). So, every entity say, currency or NFT is nothing but a hash string. The value of this increase/decreases via trading. AS many hash strings (or many coins) get mined it will be very difficult to mine more coins (or the hash string) so there is a fee which goes towards mining (it will go to a miner who finds the hash). Also, once found this particular hash will be updated throughout the network and even then a small fee is payed. Both of these fee included is called as gas fee. This gas fee can be charged to the owner who requests for the new key.

Based on the top points the industry these features are required is Banking transactions and currency related. So there are hand full of companies/projects which flaunt about using block chains for this. Those are called as deFi = decentralised Finance.

Just like deFi, we do see lot of other projects too.. like, deSo = decentralised Social etc.. But I do not see any actual use of blockchains in them. They are probably using token system (deFI) inside their projects and the front cover is always a regular Web2.0  social networking sites.

Currently, I don't see any practical use of blockchains in our regular projects or activities. I might be wrong (I hope). If you know anywhere blockchains implemented differently or some of the project if you can suggest me that will help me to change my perspective.
