# ERC-20--Token--on--Ethereum

MyToken (MTK)

This is my first ERC-20 token project on Ethereum. I created this token to understand how smart contracts work, how tokens are transferred, and how balances and approvals are managed on the blockchain.

Token Information

Token Name: MyToken

Symbol: MTK

Decimals: 18

Total Supply: 1,000,000 MTK

What This Token Can Do

You can send tokens from one account to another

You can check the balance of any address

You can approve another account to use your tokens

You can transfer tokens using transferFrom

Transfer and Approval events are generated automatically

Tools I Used

Remix IDE

Solidity

JavaScript VM

Git and GitHub

How I Deployed This Token

I opened Remix IDE in the browser

I created a file called MyToken.sol

I pasted my smart contract code

I compiled it using Solidity version 0.8.x

I used JavaScript VM for testing

I entered the total supply and deployed the contract

How to Use the Token

To check balance:

balanceOf(address)


To transfer tokens:

transfer(address, amount)


To approve someone:

approve(address, amount)


To transfer using allowance:

transferFrom(from, to, amount)