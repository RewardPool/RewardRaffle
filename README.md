# RewardRaffle
These are the smart contracts that make up the RewardPool RewardRaffle Protocol. 

All of the RewardPool Protocols are open-source and free to use. Please consider donating to the RewardPool treasury.

https://twitter.com/RewardPool <br/>
https://twitter.com/xrpant <br/>
https://rewardpool.xyz <br/>

There are two contracts that are available in flattened form:

1. The NFT contract
  A simple NFT contract cloned from https://github.com/HashLips
  
2. The Raffle contract
  A contract designed to delegate Wrapped Songbird tokens and raffle off the rewards earned each week. This contract will generate a random tokenId upon claiming rewards, query the NFT contract to find the owner of that token, and increase the allowance of that owner. The token owner will then be able to claim rewards by calling the collect() function.
  
For an example of how these contracts could be implemented in a website, see the our 'sgbrewardpool' repository and view PinkRaffle.js.
