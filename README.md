# 🥷 BEP 721 NFT MINT
Smart contract template for a BEP721 NFT minter. Written in solidity. Deployable to the Binance Smart Chain and Ethereum Network.

<h1>Getting Started</h1>
<ul>
  <li>Go here  https://remix.ethereum.org/</li>
  <li>Create a new .sol file and add the code from mint.sol</li>

  <li>Compile using a solidity version > 0.8.0</li>

  <li>Connect your metamask wallet and select the chain you want to deploy to.
  <br />
  - This contract supports blockchain networks IDs: ETH [1, 3, 4, 42] and Binance [97, 56]
  </li>

  <li>Select "Deploy and Run Transaction" on Remix</li>
  <li>Set environment to "Injected Web3"</li>
  <li>Select your NFT_Factory contract from the list of contracts</li>
  <li>Deploy to the network and approve transaction in Metamask</li>
</ul>

<h1>Operating the Minter Contract</h1>
<ul>
  <li>Prime your NFT minter by calling the "startSale" function</li>
  <li>Call the mintContract function with your desired quantity and address</li>
</ul>

All functions in this contract can be called from a Dapp using JS and Web3
