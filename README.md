# Token-Contract
MediLiVes (MLIV) Token Contract

The MediLives Token (MLIV)is an ERC20-compliant token. You may track the deployed token at the Ethereum address: 
0x228195E5EBa436f8e45d6F9C8Da2a8bA003188e1

MediLiVes Crowd-sale contract can be tracked at Etherscan : 
https://etherscan.io/address/0x5c28D0683BE8143e5eCdd5fd0b39D702D98B1Bb9

MediLiVes Crowd-sale smart contract can be viewed at the Ethereum address: 
0x5c28D0683BE8143e5eCdd5fd0b39D702D98B1Bb9 (All contributions shall be sent to this address)


The MediLiVes Crowdsale contract handles the payments for the crowdsale and keeps track of each address contribution and token credit. Each time someone sends ETH to the crowdsale, the contract checks if the buyer's address hasn't exceed the contribution cap, it computes how many MLIV, taking into account the current bonus, the buyer will receive and keeps track of each buyer's token credit.

The funds sent to the crowdsale are stored in a RefundVault contract. At the end of the Crowdsale, if the goal hasn't been reached, each user can reclaim the funds they've sent.

After the KYC/ AML checks, the tokens will be distributed to each contributor.
