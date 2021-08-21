# Issue #3 - Issue A Smart Contract Call To The Deployed Smart Contract

- 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![Call Deployed contract](https://github.com/bitcoineazy/CKB_Broaden_the_Spectrum/blob/main/Call_deployed_contract/calling_smart_contract.jpg)

- 2. The transaction hash from the console output.

# 0x6b34323d7dac49e40dc9abf0a57acf3d3e7d0f16790c080cf9baa0994c997eb1

- 3. The contract address that you called.

# 0xa64C9551def36eA715Ed69FE91ed80A4c616f109

- 4. [The ABI for contract you made a call on](https://github.com/bitcoineazy/CKB_Broaden_the_Spectrum/blob/main/Call_deployed_contract/Contract's_ABI.txt).

Contract's ABI:
```
"abi": [
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
