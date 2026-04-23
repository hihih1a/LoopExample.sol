# LoopExample.sol
LoopExample.sol
pragma solidity ^0.8.20;
contract LoopExample {
    function sum(uint n) public pure returns(uint) {
        uint s;
        for(uint i = 1; i <= n; i++) {
            s += i;
        }
        return s;
    }
}
