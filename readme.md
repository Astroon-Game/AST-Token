### Security Audit Report
- 

## Contract Details
`Astroon.sol` is an ERC20/BEP20 standard smart-contract named AST. The contract inherits from the ERC20, ERC20Burnable, and Ownable contracts. The token can be used for any type of transactions on the BSC blockchain. The contract mints 1,000,000,000 AST tokens to the address that deploys the contract, and does not have the ability to mint any more tokens after the deployment.

- <b>Network:</b> Binance Smart Chain (BEP20)
- <b>Token Name:</b> Astroon
- <b>Token Symbol:</b> AST
- <b>Total Supply:</b> 1,000,000,000 (1 billion)
- <b>Decimals:</b> 18

### Solidity
- <b>License:</b> `SPDX-License-Identifier: MIT`
- <b>Solidity Version:</b> `pragma solidity ^0.8.20;`
- <b>The Astroon.sol contract imports the following OpenZeppelin smart-contracts:</b><br>
`import "@openzeppelin/contracts/token/ERC20/ERC20.sol";`<br>
`import "@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol";`<br>
`import "@openzeppelin/contracts/access/Ownable.sol";`<br>