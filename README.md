# Ethereum-foundation
# A brief overview of erc standards
Here I would like to write about different ERC standards available in Ethereum ecosystem that acts as a backbone for building different decentralized protocol. First EIPs(Ethereum Improvement Proposals) are proposed by the community members and then it is architected and improved and published in the form of ERCs. Once it is famous it becomes a integral part of the ecosystem.

There are differnet ERC standards like ERC-20, ERC-721, ERC-1155, ERC-4626 are some famous one. ERC-20 is the fungible token, used like a dollar in any DAO ecosystem. It's use is also very simple. One can create token using `mint()` function and burn them using `burn()`. The token can be transfered by calling `transfer()` function. We can also approve another address to spend some amount of token on behalf of me, which helps us to interact with DAO protocols.
ERC-721 is another token standard called non-fungible standard whcih means every token are unique and cannot be interchangbly used. 
The use of these token also very similar with ERC20 having similar types of functions. Here `tokenURI()` function is used to store the metadata url to tokenids. ERC-1155 allows to create multiple tokens of both erc-20 and erc-721 standard. We can also make batch transfers with erc-1155 which is useful for web3 games and metaverse projects.

Vault token standard is useful for Defi projects such as lending protocol where once we transfer some assets to the smart contract it gives erc tokens in return. When the value of erc token increases we return the tokens and it burn those tokens and gives equal valued assets.

These are common token standard we use when designing a defi protocols.
