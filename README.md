## ToDo List App Using Ethereum Smart Contracts and Solidity
### To intialize a new blockchain project
### `truffle init` then `npm i` and run Ganache and MetaMask

### To compile the project: `truffle compile`

### To deploy to the blockchain: `truffle migrate`

### To open truffle console: `truffle console`
### To view the generated smart contract: `todolist = await TodoList.deployed()` where TodoList is the name of the migration then `TodoList` 

### properties of the smart contract can be viewed by `todolist.taskCount()` or `todolist.address`

### To see tasks deployed to the block: 
### `task = await todoList.tasks(1)`