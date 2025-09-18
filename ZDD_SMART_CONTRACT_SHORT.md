# ZDD_SMART_CONTRACT_SHORT.md

## Zimbabwe Digital Dollar (ZDD) Smart Contract - Short Version

This document provides a simplified snippet of the Zimbabwe Digital Dollar (ZDD) smart contract.  

It is intended for demonstration and educational purposes only. The full enterprise-grade contract is maintained separately under strict audit and security controls.

---

## Smart Contract Snippet

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

/// @title Zimbabwe Digital Dollar (ZDD) - USD-pegged stablecoin
/// @Creator - Simon Kapenda
/// @notice Simplified snippet for demonstration only
contract ZDD is ERC20, Ownable {
    constructor() ERC20("Zimbabwe Digital Dollar", "ZDD") {}

    /// @notice Mint new ZDD tokens (only owner)
    function mint(address to, uint256 amount) external onlyOwner {
        _mint(to, amount);
    }

    /// @notice Burn ZDD tokens (only owner)
    function burn(address from, uint256 amount) external onlyOwner {
        _burn(from, amount);
    }
}
