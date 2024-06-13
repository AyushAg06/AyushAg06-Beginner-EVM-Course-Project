# Implementation of tokens using Solidity 

This is a solidity project which is based on tokens creation and Implementation using solidity. It performs some of the operations of solidity and also gives us a brief idea of what solidity is all about.
## Description
This project gives us a clear understanding about solidity. In this project we have entered the details of three public variables that are tokanName,tokanabbrv and TotalSupply. And we have mapped the address to the balences of the tokans.We have created an function with the name of increase which does the work of adding the values to the TotalSupply and balances[abbrv]. Then we create a function with the name decrease which reduces the values from the totalSupply anf balance when a certain conditions is met.Otherwise it will print zero.
## Operations used
#### Mapping
Mapping is very similar to hash table or dictionary in other programming languages. It is basically used to store the datas in key values pair. Mapping is usually used to associate the unique Ethereum address with the associated value type.

Syntax:-
```bash
contract mapping_example {
    struct employee {
        string name;
        string id;
        uint salary;
    }
    // Creating mapping
    mapping (address => employee) increment;
    address[] student_increment; 
```
### Functions
A function is a set of code that can be reused and called multiple number of times in a program. It reduces complexity in the code and helps in the re-usability of the code of a number of times.

Syntax:-
```bash
contract MyToken 
{
    string public TokanName = "Ayush06";
    string public TokanAbbrv = "sol";
    uint public TotalSupply = 0;
    mapping (address => uint) public balance;
    function increase (address addr,uint value)public 
    {
        TotalSupply += value;
        balance[addr] += value;
    }
```

### If Statement
An if statement is a type of conditional statement that is used to check the condition for a given set of code and if the condition is met then it prints the desired outputs otherwise it prints the other set of code.

Syntax:-
```bash
contract IfElse {
    function max(uint a) public pure returns (uint) {
        if (a < 10) {
            return 0;
        } else if (a < 20) {
            return 1;
        } else {
            return 2;
        }
    }
```


## Summery

Solidity is a high-level programming language that is widely used around the globe to develop smart contracts on Blockchain platform mainly ethereum. The solidity code is executed with the help of EVM(Ethereum Virtual Machine).Solidity consits of the some of the key features like Smart contract development, Libraries and Interfaces, Event Logging, Supports Inheritance, Access Control etc.
## Conclusion

In this project we tried to use all the possible variables and keywords present in the Solidity. It defines a program which is used for the implementation and creation of Tokens in Solidity. It helps us in understanding Solidity which is key component of Web3 and Blockchain. By the help of this we can create multiple decenterlizes applications in todays world.
## Authors

- Mr. Ayush Agarwala
## License

This project is licensed under the MIT License- see the LICENSE.md file for details.

