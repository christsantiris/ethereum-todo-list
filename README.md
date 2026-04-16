# ToDo List App — Ethereum Smart Contracts & Solidity

---

## 🚀 Getting Started
```bash
truffle init   # Initialize a new blockchain project
npm i          # Install dependencies
```

> Also ensure **Ganache** and **MetaMask** are running before proceeding.

---

## 🔨 Common Commands

| Action | Command |
|---|---|
| Compile the project | `truffle compile` |
| Deploy to blockchain | `truffle migrate` |
| Reset & redeploy | `truffle migrate --reset` |
| Open Truffle console | `truffle console` |
| Run unit tests | `truffle test` |

> Use `truffle migrate --reset` whenever you add new functions to the smart contract.

---

## 🔍 Inspecting the Smart Contract (Truffle Console)
```js
// Load the deployed contract
todoList = await TodoList.deployed()

// View contract properties
todoList.taskCount()
todoList.address

// Access a specific task
task = await todoList.tasks(1)
task.id.toNumber()
task.content
```

---

## 🦊 Connecting MetaMask

1. Open **Ganache** and click the 🔑 key icon next to an account — copy the private key.
2. In MetaMask, go to **Settings → Networks → Add Network** and fill in:
   - **Network Name:** (anything you like, e.g. `Ganache Local`)
   - **RPC URL:** `http://127.0.0.1:7545`
3. Save and select the new network from the dropdown.
4. Go to **Accounts → Import Account** and paste the private key from Ganache.
