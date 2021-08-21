# Issue #11 - Use A Tron Wallet To Execute A Smart Contract Call

- 1. A screenshot of the accounts you created (account list) in ckb-cli.

![scr](https://github.com/bitcoineazy/CKB_Broaden_the_Spectrum/blob/main/Call_with_Tron/accounts_created.jpg)

- 2. A link to the Layer 1 address you funded on the Testnet Explorer.

[https://explorer.nervos.org/aggron/address/ckt1qyqr8q7g5naevnqmkra6j5h8lkp9jrrvfu2sja4ghh](https://explorer.nervos.org/aggron/address/ckt1qyqr8q7g5naevnqmkra6j5h8lkp9jrrvfu2sja4ghh)


- 3. A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2.

![scr](https://github.com/bitcoineazy/CKB_Broaden_the_Spectrum/blob/main/Call_with_Tron/tron_deposit.jpg)

- 4. A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2.

![scr](https://github.com/bitcoineazy/CKB_Broaden_the_Spectrum/blob/main/Call_with_Tron/contract_call.jpg)

- 5. The transaction hash of the "Contract call" from the console output.

# 0xc1a073a5be8299bd5d088c19ca0eda1f7ba823eada5a6cbb9c4d3929e66ffa3e

- 6. The contract address that you called.

# 0xa64C9551def36eA715Ed69FE91ed80A4c616f109

- 7. The ABI for contract you made a call on.
```
CONTRACT_ABI = [
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
- 8. Your Tron address.

# TYPtv5aefByhjxHF57inptXKY4Nig5ED1J

