# Ethereum DApp for Tracking Items Through the Supply Chain using Solidity

## UML Architecture Diagrams

- **[Activity Diagram](./UML/Activiti_Diagram.png):**
![Activity Diagram](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/UML/Activiti_Diagram.png?raw=true "Activity Diagram") 

- **[Sequence Diagram](./UML/Sequence_diagram.png):** 
![Sequence Diagram](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/UML/Sequence_diagram.png?raw=true "Sequence Diagram") 
- **[State Diagram](./UML/State_diagram.png):** 
![State Diagram](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/UML/State_diagram.png?raw=true "State Diagram") 

- **[Class Diagram](./UML/Class_Diagram.png):** 
![Class Diagram](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/UML/Class_Diagram.png?raw=true "Class Diagram") 

## Project Write-up - Libraries

### Programming Libraries Used:
- **Truffle v5.8.1 (core: 5.8.1):** used to deploy and test smart contracts.
- **Solidity v0.5.16 (solc-js):** high-level langauge for writing smart contracts.
- **Node v18.15.0:** used for building web applications quickly
- **Web3.js v1.8.2:** used to allow the smart contracts to interact with a local/remote Ethereum node with an HTTP, HTTPS, or IPC connection.

### Technologies used:
- **Ganache:** used to deploy and test the DApp in environment before deploying.
- **Visual Studio Code:** IDE

## General Write Up

### Deploying Contracts Terminal Window: && Contract Address**
Starting migrations...
======================
> Network name:    'rinkeby'
> Network id:      11155111
> Block gas limit: 30000000 (0x1c9c380)


1_initial_migration.js
======================

   Replacing 'Migrations'
   ----------------------
   > transaction hash:    0x41575686dab470d985a0ad76c5c0e7126aafba59314e89f76726b65f08306f45
   > Blocks: 2            Seconds: 16
   > contract address:    0x67D3182D2e4973949c037A0604b8D95B79E7b0a4
   > block number:        5306517
   > block timestamp:     1708161228
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.59103924
   > gas used:            226587 (0x3751b)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00453174 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00453174 ETH


2_deploy_contracts.js
=====================

   Deploying 'FarmerRole'
   ----------------------
   > transaction hash:    0x6a564fb39a4bf9c55c60dfd01a1767ca1d6f72aa84fbb5860e2a0ac81184de94
   > Blocks: 0            Seconds: 5
   > contract address:    0xDA1FEF1A98DC17CACb04535E25e19d165A2c8a01
   > block number:        5306519
   > block timestamp:     1708161252
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.58398842
   > gas used:            306778 (0x4ae5a)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00613556 ETH


   Deploying 'DistributorRole'
   ---------------------------
   > transaction hash:    0x5129c596fbe8a07c2c5d9de8bcadccbefe8a8fefb2ba07c404afac1cf0141297
   > Blocks: 1            Seconds: 9
   > contract address:    0xc169BcB43C8F3B8e669bD2BBFCbC7B32e0928A6a
   > block number:        5306520
   > block timestamp:     1708161264
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.57785358
   > gas used:            306742 (0x4ae36)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00613484 ETH


   Deploying 'RetailerRole'
   ------------------------
   > transaction hash:    0x72a478f560a373d8a1be99137ae4bc320793292f368ef7fa085ddf0a28486010
   > Blocks: 0            Seconds: 4
   > contract address:    0xAe58352FCb12B57E335074e1051526F23693Ba66
   > block number:        5306521
   > block timestamp:     1708161276
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.57171802
   > gas used:            306778 (0x4ae5a)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00613556 ETH


   Deploying 'ConsumerRole'
   ------------------------
   > transaction hash:    0xa1b0434941ca183adffae59bf3bbee66d0703c83c0fe4ad581be3e3c04ce7519
   > Blocks: 1            Seconds: 20
   > contract address:    0x54dC77FA223cBED5fbD65149A2d6D9EB8cbee174
   > block number:        5306522
   > block timestamp:     1708161300
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.56558246
   > gas used:            306778 (0x4ae5a)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00613556 ETH


   Deploying 'SupplyChain'
   -----------------------
   > transaction hash:    0xa1dba1fca975fc7b64111e7f7123036829c2b58f66b3f9b1d4a9941a1fec380b
   > Blocks: 1            Seconds: 4
   > contract address:    0x1149Ca04C7Cb449295e0c6Fb8DE5c4cD3a7406AD
   > block number:        5306523
   > block timestamp:     1708161312
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.51636834
   > gas used:            2460706 (0x258c22)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.04921412 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.07375564 ETH

Summary
=======
> Total deployments:   6
> Final cost:          0.07828738 ETH

### Deploying Contracts Terminal Window:Images**
![Deploying Contracts](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/project-6/images/truffle%20test.png?raw=true "") 
![Deploying Contracts](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/project-6/images/truffle%20migrate%201.png?raw=true "") 
![Deploying Contracts](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/project-6/images/truffle%20migrate%202.png?raw=true "") 
![Deploying Contracts](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/project-6/images/truffle%20migrate%203.png?raw=true "") 
![Deploying Contracts](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/project-6/images/truffle%20migrate%204.png?raw=true "") 
![Deploying Contracts](https://github.com/omi90/udacityblokchain-Project-6b/blob/master/project-6/images/truffle%20migrate%205.png?raw=true "") 
