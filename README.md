# Solidity

1. Built the Create a Joint Savings Account Contract in Solidity using the Starter Code
    * From the provided starter code, opened the Solidity file named joint_savings.sol in the Remix IDE.
    * Defined a new contract named JointSavings.
    * Defined variables in the new contract
    * Defined a function named withdraw that accepts two arguments: amount of type uint and recipient of type payable address.
    * Defined a public payable function named deposit. 
    * Defined a public function named setAccounts that takes two address payable arguments, named account1 and account2. 
    * Added a fallback function so the contract can store ether that’s sent from outside the deposit function.

2. Compiled and Deploy the Contract in Injected Web3

3. Interacted with the Deployed Smart Contract following these steps
    * Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.
![image](https://github.com/nhc12/Solidity/blob/main/Execution%20Results/Step%201%20-%20setAccounts%20function%20to%20define%20the%20authorized%20Ethereum%20address.jpg)
    * Tested the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, used the contractBalance function to verified that the funds were added to the contract:
       * Transaction 1: Send 1 ether as wei.
![image](https://github.com/nhc12/Solidity/blob/main/Execution%20Results/Step%202%20-%20Test%20the%20deposit%20functionality%20to%20Send%201%20ether%20as%20wei..jpg)
       * Transaction 2: Send 10 ether as wei.
![image](https://github.com/nhc12/Solidity/blob/main/Execution%20Results/Step%202%20-%20Test%20the%20deposit%20functionality%20to%20Send%2010%20ether%20as%20wei..jpg)
       * Transaction 3: Send 5 ether.
![image](https://github.com/nhc12/Solidity/blob/main/Execution%20Results/Step%203%20-%20Test%20the%20deposit%20functionality%20to%20Send%205%20ether%20.jpg) 
       * Tested the contract’s withdrawal functionality by withdrawing 5 ether into accountOne and 10 ether into accountTwo
![image](https://github.com/nhc12/Solidity/blob/main/Execution%20Results/Step%204%20-%20Test%20the%20contract%E2%80%99s%20withdrawal%20functionality%20by%20withdrawing%2010%20ether%20into%20accountTwo.jpg)

![image](https://github.com/nhc12/Solidity/blob/main/Execution%20Results/Step%204%20-%20Test%20the%20contract%E2%80%99s%20withdrawal%20functionality%20by%20withdrawing%205%20ether%20into%20accountOne.jpg)

6. Attachmnents:
      
      * Starter Code (joint_savings.sol)
      * Code for deployment .txt 
      * Screenshots of Deployment
