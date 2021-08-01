---
sidebar_position: 4
---

# Pragma

The keyword "pragma" is declared at the very top of the contract to specify the version of Solidity that we will be using. This tells solc (solidity compiler) about which version to use. Declaring a Solidity version is very crucial as we get more features (and breaking changes for improvements & bug fixes) with every new release. This declaration is also local which means you need to do this for every solidity file that you write. At the time of writing, the latest version is "0.8.3". Now, let's implement this on our "Greet.sol"

Steps:

1. Navigate to "Greet.sol" file inside your directory.
2. Declare the solidity version with ```pragma solidity  0.8.3```.
3. Save your file with ```ctrl + s```

![pragma-example](/img/simple-smart-contract/pragma.png)
