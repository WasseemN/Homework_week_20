# Joint Savings Account
<center><img src="Images/20-5-challenge-image.png"/></center>


## **Overview of the Smart Contract**
The Solidity smart contract permits the withdrawl and deposit transactions between two specified adresses on the ethereum blockchain.
****

## **Folder Structure**

* The `joint_savings.sol` contains the solidity smart contract code.
* The `Execution_Results` folder contains snapshots of the process execution of the smart contract on *Remix*.


## **Deploying and Testing the Smart Contract on Remix**
The following presents the step-by-step execution of the smart contract on the *Remix* IDE as the testing platform. Once the contract is successfully compiled and deployed on the ethereum blockcahin, Ether deposits are made into the contract and withdrawls to the addresses are exhibited.


![compile](Execution_Results/compile.png)

##### <center>Figure 1 - Compiling the smart contract


![deploy](Execution_Results/deploy.png)



##### <center>Figure 2 - Deploying the smart contract


![function_check](Execution_Results/function_check.png)


##### <center>Figure 3 - Function checks


![set_accounts](Execution_Results/set_accounts.png)

##### <center>Figure 4 - Setting the accounts


![deposit_1EthAsWei](Execution_Results/deposit_1EthAsWei.png)



##### <center>Figure 5 - Deposit 1 ETH


![deposit_additional](Execution_Results/deposit_additional.png)


##### <center>Figure 6 - Further Deposits


![withdrawl_5Eth](Execution_Results/withdrawl_5Eth.png)

##### <center>Figure 7 - Withdraw 5ETH to Account 1


![withdrawl_additional](Execution_Results/withdrawl_additional.png)



##### <center>Figure 8 - Withdraw 10ETH to Account 2

![withdrawl_require_check](Execution_Results/withdrawl_require_check.png)


##### <center>Figure 9 - Testing the Require Function
