

// SPDX-License-Identifier: MIT

pragma solidity ^0.8.0;

// 1️⃣ Make a contract called Calculator
// 2️⃣ Create Result variable to store result
// 3️⃣ Create functions to add, subtract, and multiply to result
// 4️⃣ Create a function to get result

contract Calculator {
    int256 Result = 0;

    function add(int256 num) public {
        Result += num;
    }

    function substract(int256 num) public {
    Result -= num; 
    }

    function multiplication(int256 num) public {
        Result *= num;
    }

    function get() public view returns (int256) {
        return Result;
    }
}
