
# NounsDAO  contest details

- Join [Sherlock Discord](https://discord.gg/MABEWyASkp)
- Submit findings using the issue page in your private contest repo (label issues as med or high)
- [Read for more details](https://docs.sherlock.xyz/audits/watsons)

# Q&A

### Q: On what chains are the smart contracts going to be deployed?
Ethereum
___

### Q: If you are integrating tokens, are you allowing only whitelisted tokens to work with the codebase or any complying with the standard? Are they assumed to have certain properties, e.g. be non-reentrant? Are there any types of [weird tokens](https://github.com/d-xo/weird-erc20) you want to integrate?
Nouns DAO basically only uses ETH, WETH, and USDC. We hold stETH, but do not have code that directly interacts with it.
___

### Q: Are there any limitations on values set by admins (or other roles) in the codebase, including restrictions on array lengths?
No
___

### Q: Are there any limitations on values set by admins (or other roles) in protocols you integrate with, including restrictions on array lengths?
No
___

### Q: Is the codebase expected to comply with any specific EIPs?
No
___

### Q: Are there any off-chain mechanisms involved in the protocol (e.g., keeper bots, arbitrage bots, etc.)? We assume these mechanisms will not misbehave, delay, or go offline unless otherwise specified.
Not in this scope
___

### Q: What properties/invariants do you want to hold even if breaking them has a low/unknown impact?
No
___

### Q: Please provide links to previous audits (if any).
https://github.com/nounsDAO/nouns-monorepo/tree/master/packages/nouns-contracts/audits
___

### Q: Please list any relevant protocol resources.
https://nouns.wtf/
___

### Q: Additional audit information.
Here's our audit scope doc: https://docs.google.com/document/d/1gxLSkRQooJtcqMm3I86cOJpsnaObwEE5ergqkSl87kM/edit?usp=sharing
___



# Audit scope


[nouns-monorepo @ 794903316961911a90ab5493ca66592ccbdbd036](https://github.com/nounsDAO/nouns-monorepo/tree/794903316961911a90ab5493ca66592ccbdbd036)
- [nouns-monorepo/packages/nouns-contracts/contracts/NounsAuctionHouseV2.sol](nouns-monorepo/packages/nouns-contracts/contracts/NounsAuctionHouseV2.sol)
- [nouns-monorepo/packages/nouns-contracts/contracts/NounsAuctionHouseV3.sol](nouns-monorepo/packages/nouns-contracts/contracts/NounsAuctionHouseV3.sol)
- [nouns-monorepo/packages/nouns-contracts/contracts/StreamEscrow.sol](nouns-monorepo/packages/nouns-contracts/contracts/StreamEscrow.sol)
- [nouns-monorepo/packages/nouns-contracts/contracts/interfaces/INounsAuctionHouseV3.sol](nouns-monorepo/packages/nouns-contracts/contracts/interfaces/INounsAuctionHouseV3.sol)
- [nouns-monorepo/packages/nouns-contracts/contracts/interfaces/IStreamEscrow.sol](nouns-monorepo/packages/nouns-contracts/contracts/interfaces/IStreamEscrow.sol)
- [nouns-monorepo/packages/nouns-contracts/script/StreamEscrow/DeployAuctionHouseV3StreamEscrowBase.s.sol](nouns-monorepo/packages/nouns-contracts/script/StreamEscrow/DeployAuctionHouseV3StreamEscrowBase.s.sol)
- [nouns-monorepo/packages/nouns-contracts/script/StreamEscrow/DeployAuctionHouseV3StreamEscrowMainnet.s.sol](nouns-monorepo/packages/nouns-contracts/script/StreamEscrow/DeployAuctionHouseV3StreamEscrowMainnet.s.sol)
- [nouns-monorepo/packages/nouns-contracts/script/StreamEscrow/DeployAuctionHouseV3StreamEscrowSepolia.s.sol](nouns-monorepo/packages/nouns-contracts/script/StreamEscrow/DeployAuctionHouseV3StreamEscrowSepolia.s.sol)
- [nouns-monorepo/packages/nouns-contracts/script/StreamEscrow/ProposeUpgradeAHV3.s.sol](nouns-monorepo/packages/nouns-contracts/script/StreamEscrow/ProposeUpgradeAHV3.s.sol)

