# dWallet - Decentralized Wallet

dWallet is a decentralized wallet application that runs on the Ganache blockchain and utilizes the concepts of ReactJS and Web3.js. It allows users to easily send Ethers to any address on the Ganache network without the need for a smart contract.


![image](https://user-images.githubusercontent.com/81066183/217150768-93f0e2f1-a120-4678-b83b-4914f2c42272.png)


## Requirements

- Node.js
- Ganache
- ReactJS
- Web3.js

## Features

- Choose an account on Ganache from the drop down menu
- Add the address of the recipient
- Send Ethers to the recipient's address
- Simple and user-friendly interface

## How it works

dWallet uses Web3.js to interact with the Ganache blockchain. It allows the user to select an account on the network and add the address of the recipient. The user can then send Ethers to the recipient's address with a simple click of a button. The application does not require a smart contract as the functionality is provided by Web3.js.
React Hooks such as `useState` and `useEffect` are used to manage the state and side-effects of the application.
## Getting Started

1. Clone the repository
``
git clone https://github.com/0xrizy/d_Wallet
``

2. Install the dependencies
``
npm install
``
3. Start the development server
`` 
npm start
``

4. Connect to the Ganache network

5. Select an account and add the recipient's address

6. Send Ethers to the recipient's address


![image](https://user-images.githubusercontent.com/81066183/217150848-22030216-1ee1-443b-b237-76bd58fe9382.png)


## Role of Web3.js

Web3.js is a JavaScript library that allows developers to interact with Ethereum blockchain. It provides a simple and convenient way to interact with smart contracts and perform transactions on the Ethereum network. In dWallet, Web3.js is used to communicate with the Ganache blockchain and perform the Ether transfer without the need for a smart contract.


