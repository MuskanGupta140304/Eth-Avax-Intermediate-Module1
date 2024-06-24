
# Eth-Avax-Intermediate-Module1 Project

Metacrafters Eth-Avax-Intermediate-Module1 Project

## Description

This project fulfills the requirements for the Eth-Avax Intermediate Module 1 course offered by Metacrafters. It demonstrates the use of `require()`, `assert()`, and `revert()` functions in a smart contract.

## Getting Started

### Executing the program

1. Clone this repository to your local machine:


git clone https://github.com/MuskanGupta140304/Eth-Avax-Intermediate-Module1.git


2. Navigate into the project directory:


cd Eth-Avax-Intermediate-Module1


3. Install dependencies:


npm install


4. Compile contracts:


npx truffle compile


5. Migrate contracts to the blockchain:


npx truffle migrate


6. Start the Truffle console:


npx truffle develop


7. In the Truffle console, interact with the deployed smart contract:


let instance = await FunctionsAndErrors.deployed();
// Example interaction: instance.requireEvenNumber(2);


### Note

- To check the value of `evenCount`, enter `(await instance.evenCount()).toString()`.
- You can create a simple async function to get `evenCount` easily:


let getEvenCount = async () => (await instance.evenCount()).toString();


### Callable Variables and Functions

- `uint public evenCount`
- `function requireEvenNumber(uint number) external`
- `function assertEvenNumber(uint number) external`
- `function revertEvenNumber(uint number) external`

## Author

Muskan Gupta (MuskanGupta140304@gmail.com)

## License

This project is licensed under the MIT License file for details.