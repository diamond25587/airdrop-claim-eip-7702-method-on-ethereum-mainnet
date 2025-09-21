# Airdrop Claim eip-7702 Method on Ethereum Mainnet
Claim airdrop with eip 7702 method for drained wallets on ethereum mainnet

---

## 1. Clone and install

```bash
git clone https://github.com/abahuto/airdrop-claim-eip-7702-method-on-ethereum-mainnet.git
```
```bash
cd airdrop-claim-eip-7702-method-on-ethereum-mainnet
```
```bash
npm install
```

## 2. Configure environment variables

Create a `.env` 
```bash
nano .env
```
Input
```bash
RPC_URL_ETHERERUM=https://eth.drpc.org 
CHAIN_ID=1

//WALLET THAT HAS BEEN DRAINED
PRIVKEY_A=0xYour_Privatekey
ADDR_A=0xYour_adrress

//WALLET TO PAY GAS FEES
PRIVKEY_B=0xYour_Privatekey

//NEW WALLET TO RECEIVE AIRDROP
RECIPIENT_ADDR=0xYour_adrress

//AIRDROP CLAIM CONTRACT ADDRESS
AIRDROP_ADDR=0x...

//AIRDROP TOKEN ADDRESS
TOKEN_ADDR=0x...

//DATA WHEN SIGNING, CAN BE SEEN WHEN SIGNING WALLET
CLAIM_MODE=raw 
AIRDROP_CALLDATA=0x...

CONTRACT_7702=0x6106e79063f9a09f5c950dadd4386e9aea7510c9 
FORWARDER=0xFAE4d2252F7a7488860BDA2EBbE7F87974851FC3
```

---

### For AIRDROP CLAIM CONTRACT ADDRESS & AIRDROP_CALLDATA you can check on wallet example OKX or METAMASK

- Example
the top one is for (CLAIM CONTRACT ADDRESS) the bottom one is for (AIRDROP_CALLDATA)

<img width="333" height="217" alt="image" src="https://github.com/user-attachments/assets/f1a14f5e-34f8-4a86-a59b-aa7676297af4" />


### For AIRDROP TOKEN ADDRESS you can ask the airdrop project about the contract token.

---

## 3. Run scripts

**For Claim:**

```bash
npm run claim
```

**After Claim you can Revoke:**

```bash
npm run revoke
```

---

## Hashtag

#EthereumMainnet #EIP7702 #AirdropClaim #DrainedWalletRecovery #WalletRescue #Web3Security #SmartContractTools #CryptoTools #BlockchainRecovery #GasSponsor

