# SimpleMath.sol
Great insight, well explained.
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleMath {
    function add(uint a, uint b) public pure returns (uint) {
        return a + b;
    }

    function subtract(uint a, uint b) public pure returns (uint) {
        return a - b;
    }
}
Refactor code for readability
Remove unused code
Optimize gas usage
Update comments and docs
Update function logic
Refactor contract layout
Fix edge scenario
