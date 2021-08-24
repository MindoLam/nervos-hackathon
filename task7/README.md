# Task 7: Port an Existing Ethereum dApp to Polyjuice

1) Screenshots of your application running on Godwoken:

![](./dapp1.png)

# After Subtraction

![](./dapp2.png)

# After Multiplication

![](./dapp4.png)


2) Link to the GitHub repository with your application which has been ported to Godwoken.:
https://github.com/MindoLam/Calculator-Nervos-Dapp


3)
Smart Contract Address:
```
0xEC9f1aA277D40Ae1774F01C59765b07F4ccE6624
```
4) Transaction Hash of Smart Contract:
```
0x392f56b46724cabd2254dc83ce8667fc773346e1000d38372bf72ee0b29b1a85
```


5) ABI:
```
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "int256",
          "name": "x",
          "type": "int256"
        }
      ],
      "name": "add",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "int256",
          "name": "y",
          "type": "int256"
        }
      ],
      "name": "subtract",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "int256",
          "name": "w",
          "type": "int256"
        }
      ],
      "name": "divide",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "int256",
          "name": "z",
          "type": "int256"
        }
      ],
      "name": "multiply",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "show",
      "outputs": [
        {
          "internalType": "int256",
          "name": "",
          "type": "int256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "clear",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    }
  ]
```
