---
sidebar_position: 1
---

# What is Solidity ? 

:::info 
A lot of words here might not make sense to you right away if you are very new to programming. But if you stick around, they will click eventually. Always remember, you don't always need to understand everything at first while learning something new. Just try to get something out of it and keep on going. Things will click eventually as you progress. That's totally normal in software development or any field for that matter. 
:::

Solidity is an object-oriented, high-level language for implementing smart contracts. Smart contracts are just programs navigating and governing the behaviour of accounts in Ethereum state. 

Example: Let's say that you are are using something like [Aave](https://aave.com/), then these smart contracts are taking care of operations like allowing to borrow against your assets, keeping track of your debt interest, yields, liquidation, etc.

Solidity is statically typed, supports inheritance, libraries and complex user-defined types among other features. It is influenced by C++, Python and JavaScript. Solidity is targeted towards EVM (Ethereum Virtual Machine). For sake of simplicity, information about EVM(s) is kept brief here but there will be in-depth module about nuances of EVM(s) as we progress. Every node inside Ethereum network is an EVM, Solidity code gets compiled into byte-code to run on these EVM(s).

:::tip
It's advised on Solidity documentation that you should always use the latest version of Solidity while writing smart contracts. This is because breaking changes as well as new features and bug fixes are introduced regularly. At the time of writing this, the latest version is 0.8.6 and we will be using that for writing contracts.
:::

