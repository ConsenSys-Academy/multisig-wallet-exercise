# Project 3: Create a Multi-signature Wallet

**Background:** Blockchains are tricky things; the promise of immutability seems oh-so-nice until you accidentally lose your private key that controls most of your net worth. Then, immutability sucks.

To protect themselves against this type of loss, users quickly realized they could use a multiple signature wallet. Depending on the implementation, this wallet allows for a quorum (say, 50%) of keys that control it to use the funds. 

These wallets are also used by companies/projects that control large amounts of crypto-currency, to reduce the risk that a team member will run away with huge sums of money. To protect our class from such an event, we will all be making multi-sig wallets of our own. 

If you want to read more about multi-sig wallets, and see what they were like in the Bitcoin era. 
1. https://en.bitcoin.it/wiki/Multisignature
2. https://ethereum.stackexchange.com/questions/6/how-can-i-create-a-multisignature-address-on-ethereum

**Objectives:**
- To learn how to handle complex interactions between multiple users on one contract
- Learn how to avoid loops and implement voting
- To learn to assess possible attacks on contracts.

**Directions:** 
Implement a multi-signature wallet. [See here for function stubs.](./multisig/contracts/MultiSignatureWallet.sol) 

Thanks to Nate Rush
