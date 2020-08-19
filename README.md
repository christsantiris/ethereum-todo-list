## ToDo List App Using Ethereum Smart Contracts and Solidity
### To intialize a new blockchain project
### `truffle init` then `npm i` and run Ganache and MetaMask

### To compile the project: `truffle compile`

### To deploy to the blockchain: `truffle migrate`

### To open truffle console: `truffle console`
### To view the generated smart contract: `todolist = await TodoList.deployed()` where TodoList is the name of the migration then `TodoList` 

### properties of the smart contract can be viewed by `todolist.taskCount()` or `todolist.address`

### To see tasks deployed to the block: 
### `task = await todoList.tasks(1)` and to see information about the task i.e `task.id.toNumber()` or `task.content`

## To Connect via Meta Mask
### Get private key to account from Ganache by clicking key icon and copying it
### Open Metamask go to settings > network > add network ! and there add your new network if it's a local node in RPC URL put: http://127.0.0.1:7545 and chose a name for it and save 
### Select the newly createe account from dropdown to connect
### In Meta Mask go to Accounts > Import Account and add the private key from Ganache
