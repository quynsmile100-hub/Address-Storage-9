# Address-Storage-9
Address Storage.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract AddressStorage {
    address public owner;

    function setOwner(address _owner) public {
        owner = _owner;
    }
}
