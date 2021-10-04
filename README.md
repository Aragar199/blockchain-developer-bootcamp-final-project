# blockchain-developer-bootcamp-final-project

# **NFT Recycler**

Everyone is minting NFTs! They are the new hotness, whether you want one because you appreciate art, you want a status symbol to show that you are a part of the crypto community, or you just are trying to become a millionnaire selling a jpeg of a hooded punk!

# **Problem**

What do you do if you bought an NFT that you are unable to sell? You bought a picture of a drunk, stoned, cartoon character thinking it would be worth many ETH one day and now you're stuck with an ugly jpeg that you want to set on fire.

# **Solution**

Set that NFT on fire! Or rather, burn the NFT in the NFT Recycler and generate a new NFT!

* Get rid of old NFTs
* Get a new NFT that you would actually want

# **Example Workflow**

NFT Recycler Website
* Click on NFT(s) that are eligible to be recycled (owned, has burn function)
* generative art would be created (gan (?), etc)
* confirm transaction
* mint + burn + fee all in one function to prevent reentrancy
- Save new image as metadata in multiple formats
  - centralized
  - ipfs
- properties
  - list of NFT(s) burned
  - number of NFT(s) burned to create the new NFT
