# solidity12
// SPDX-License-Identifier: MIT

pragma solidity >= 0.5.0 < 0.9.0;

contract state
{
    uint public age=10;

function setter() public
{
    age = age+1;
}
}
