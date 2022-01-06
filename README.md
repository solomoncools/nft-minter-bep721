# 🥷 BEP 721 NFT MINT
Smart contract template for a BEP721 NFT minter. Written in solidity. Deployable to the Binance Smart Chain and Ethereum Network.

<h1>Getting Started</h1>
1. Go here  https://remix.ethereum.org/
2. Create a new .sol file and add the code from mint.sol

3. Compile using a solidity version > 0.8.0

4. Connect your metamask wallet and select the chain you want to deploy to.
- This contract supports blockchain networks IDs: ETH [1, 3, 4, 42] and Binance [97, 56]

4. Select "Deploy and Run Transaction" on Remix
5. Set environment to "Injected Web3"
6. Select your NFT_Factory contract from the list of contracts
7. Deploy to the network and approve transaction in Metamask

<h1>Operating the Minter Contract</h1>
8. Prime your NFT minter by calling the "startSale" function
9. Call the mintContract function with your desired quantity and address

All functions in this contract can be called from a Dapp using JS and Web3
