# Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

1. A screenshot of the accounts you created (account list) in ckb-cli.

_Click To Enlarge_

<img src='https://github.com/encoderafat/nervos/blob/main/project11/list_account.png' width='800' />

2. A link to the Layer 1 address you funded on the Testnet Explorer.

https://explorer.nervos.org/aggron/address/ckt1qyqt3vve66kwxnh70t6wxn9lf0pevstzslwqrn0y6z

3. A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2.

_Click To Enlarge_

<img src='https://github.com/encoderafat/nervos/blob/main/project11/deposit.png' width='800' />

4. A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2.

_Click To Enlarge_

<img src='https://github.com/encoderafat/nervos/blob/main/project11/contractcall.png' width='800' />

5. The transaction hash of the "Contract call" from the console output (in text format).

0xb12819f245d1373cbeb8e3dfd1811d600e02894e915f850422ff7171fb36ae2b

6. The contract address that you called (in text format).

0xbBBC7E47E5Fbf59fF3bf5aFeEEbA6F2EBA6d0AfA

7. The ABI for contract you made a call on (in text format).

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

8. Your Tron address (in text format).

TX6Mh4EuAkmRYApToKQg1dRZdfaEuJgFUD
