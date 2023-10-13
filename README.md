# Module-20-Challenge

## Description

For this assignment I will be building and deploying a smart contract via Solidity. I will use the  two dummy addresses  provided that will be allowed to withdraw from the contract I created. First I must create the "Joint Savings Account" contract and then compile and deploy it all within Solidity. 

## Smart Contract Testing


Step 1: Using the setAccounts function which will define the authorized Ethereum addreses.

![setaccounts](https://github.com/jpark716/Unit20_hw/blob/main/setaccount%20function.PNG?raw=true)

Step 2: Testing transactions and the deposit functionality of the smart contract by sending various amounts of ether and checking the contract balance.

Sending 1 ether as wei:

![transaction1](https://github.com/jpark716/Unit20_hw/blob/main/transaction1.PNG?raw=true)

Sending 10 ether as wei:

![transaction2](https://github.com/jpark716/Unit20_hw/blob/main/transaction2.PNG?raw=true)

Sending 5 ether:


![transaction3](https://github.com/jpark716/Unit20_hw/blob/main/transaction3.PNG?raw=true)

Step 3: After these funds have been successfully deposited into the smart contract, I must test the withdrawal function. In doing so I will withdraw 5 ether into accountOne and 10 into accountTwo. I will verify that it is working by checking the contract balance, last to withdraw and last withdraw amount functions as a whole.

Withdrawal 1: Withdrawing 5 ether into accountOne:


![withdraw1](https://github.com/jpark716/Unit20_hw/blob/main/withdraw1.png?raw=true)

Withdrawal 2: Withdrawing 10 ether into accountTwo:

![withdraw2](https://github.com/jpark716/Unit20_hw/blob/main/withdraw2.png?raw=true)

As shown above, the smart contract functionality was proven to work effectively.

## Tech Used
Remix IDE - the website to create, compile and deploy a smart contract. https://remix.ethereum.org/