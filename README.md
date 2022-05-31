# JavaScript-Blockchain-from-Scratch
# Follow on Twitter for any questions. https://twitter.com/Anni_Maan
Create your own Blockchain in javaScript from the ground up.
# The steps to run it correctly are listed below.
1. On your local machine, download or clone the repository.
2. Go to the local directory in VSCODE or any other IDE. For example, if you have this repository saved at C:/users/abc/desktop/anni maan
3. Run npm install from the anni maan directory. It will install all of the Project's essential dependencies.
4. You'll need a free MongoDB online atlas account. Simply create a user account. If you don't know how to make a mongoDB account, there are numerous YouTube videos available. 
5. You should now have an Url that you may use to connect to MongoDB on your local PC. 
6. You must generate two .env files, one in the anni maan/Blockchain/Backend/**core**/.env directory and the other in the anni maan/Blockchain/Backend/**database**/.env directory.
7. That's all there is to it; you should now be able to work on your projects.
8. **cd blockchain/backend/core and make sure you're on anni maan.**
9. Replace private key with your own Private key in /core/Tx.js, or use the same key mentioned in Tx.js. 
   If you replace the private key, make sure to update the MINER ADDRESS as well, because this is the address where you will receive your mining earnings,
   and you will be able to send money to any other address with the specified private key.
11. You may also use core/wallet.js to generate fresh Private/Public key pairs. Make sure you are inside the correct directory **blockchain/backend/core** on your computer.Just type node wallet.
13. Start your Blockchain node by tyrping **node blockchain**
14. Voila! Your blockchain mining node is now up and running.

# Frontend 
1. http://localhost:3000/
2. There 3 main sections, Blocks, Transfer and Mempool. 
3. Block is to see all the Blocks in our Blockchain.
4. Transfer is to send coins to any address. You can type any random intergers and it will automatically generate your Public Address. Make sure from the from and to addresses are correct.
5. once you hit the Submit button, you should be able to see your transaction in mempool. Once Transaction is confirmed it will be automatically removed from the mempool.
6. You can goto back to blocks and one the block should have 2 transaction. First transaction will always be COINBASE transaction which is the mining reward and other transaction you just initiated. 
