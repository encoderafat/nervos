# Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

_Click To Enlarge_

<img src='https://github.com/encoderafat/nervos/blob/main/project3/callcontract.png' width='800' />

2. The transaction hash from the console output (in text format).

0x14bcc1d8c5d565d133eb3b84c7475fb6bbdd0f8d01ef383cc7524e5935690526

3. The contract address that you called (in text format).

0xbBBC7E47E5Fbf59fF3bf5aFeEEbA6F2EBA6d0AfA

4. The ABI for contract you made a call on (in text format).

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
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
  ```
