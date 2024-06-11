# ETHassessment

# Project:Create A Token
Description:
This Solidity smart contract defines a basic ERC20-compatible token called "SANSKRITI" (with the abbreviation "SANS"). It allows for token minting and burning functionalities. The contract includes public variables to store token details such as name, abbreviation, and total supply. It also utilizes a mapping to track token balances for each address. The mint function increases the total token supply and the balance of a specified address, while the burn function decreases the total supply and the balance of a specified address, contingent upon the availability of tokens in the address's balance. Additionally, the burn function includes conditionals to ensure that the amount to be burned does not exceed the available balance of the address. Overall, this contract provides a simple framework for creating and managing tokens on the Ethereum blockchain.


## Getting Started
To test this contract you can either just copy and paste it in remix ide or test it locally in your code editors or ides.


### Executing program

We will first compile our program. We then move to deploy and run transactions.
We can observe Public Variables:
•	tokenName: "SANSKRITI"
•	tokenAbbrv: "SANS"
•	totalsupply: 0

We then we copy the address and paste it in to mint addresss and add the balance 2000 and click on transact, we will check the total supply which will be 2000. 
Now we will burn 1000 balance similarly and check the total supply which will be 1000 now after burning. 




## Authors

Harsh Jha - +91 6299928212
