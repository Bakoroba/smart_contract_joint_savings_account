# Smart contract joint savings account
The objective is to create a smart contract that will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.
## Tasks
- Create a Joint Savings Account Contract in Solidity
- Compile and Deploy Your Contract in the JavaScript VM
- Interact with Your Deployed Smart Contract

## Testing the App

1. Define the authorized Ethereum address 
- Compile and deploy
<img src="Execution_Results/compile_deploy.png">
- Authorized addresses
<img src="Execution_Results/set_accounts.png">

2. Test the deposit functionality of the smart contract
- Transaction 1: Send 1 ether as wei.
<img src="Execution_Results/deposit_1ether.png">
- Transaction 2: Send 10 ether as wei.
<img src="Execution_Results/deposit_10ether.png">
- Transaction 3: Send 5 ether.
<img src="Execution_Results/deposit_5ether.png">
3. Test the contract’s withdrawal functionality

- Withdrawing 5 ether into accountOne
<img src="Execution_Results/withdraw_5ether_account1.png">

- Withdrawing  10 ether into accountTwo
<img src="Execution_Results/withdraw_10ether_account2.png">

## Technology
- Solidity
- Remix IDE

## License

MIT