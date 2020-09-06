ETHIndia2020DAppJedi ( Submission for ETH India 2020 DApp Jedi Hackathon )

# Progress
We have demonstrated an onchain ZK Rollup together with Onchain Randomness of VDF for Random Oracles Proof of Concept and Random DAOs. This is the first implementation of RANDAO +  VDF as per Justin Drake model. Now we would like to demonstrate how an Auction App powered by Portis SDK can benefit. We also would like to convert the Fusion Rollup Contract to a Matic Child Chain. 

# Overview
This is a reference implementation of the FusionLedger framework for On-chain and Off-chain interaction between real work data and digital world institutions. FusionOracles will represent the real world data and FractalDAOs represent the digital world institutions like Banks, Treasuries, Markets, etc. 

## Components
* Fusion Oracles
* Fractal DAOs
* Fusion Forward Manager
* Verifiable Delay Functions
* Auction Apps

## Workflow

* Our Workflow is Fusion to Fractal
* Hence Fusion Oracles to Fractal DAO

* We are tokenising Fusion Oracles
* We are tokenising Fractal DAO

* We will tokenise Oracles by applying VDF
* We will tokenise DAOs by applyingb VDF

## Tokenisation

### Applying Fractal Token to Fractal DAO
* Importing Fractal Token Contract
* Importing Fractal DAO Contract
* Creating a simple contract to tokenise DAO by tokenising the campaigns and customers in the DAO
* Tokening Fractal DAO at a time, for a activities and aspirations using Fractal Token

### Applying Fusion Token to Fusion Oracle

* Importing Fusion Oracle contract
* Importing Fusion Token contract
* Tokening Fusion Oracle at a time, for a quantity and quality using Fusion Token

## Token Swap 
* FiniteSwap Execution with Fusion Manager after tokenising FractalDAO and FusionOracles

## Scalability
* Applying ZK RollUps for FusionOracles and FractalDAOs and FusionManager

## Inteface Design 
* Auction App Listing Oracles
* Auction App choosing an Oracle at a time at random
* Auction App Listing DAOs
* Auciton App choosing a DAO at a time based at random
* Hence we need two listing screens and pages
* Then we need an auction bid page
* In the auction big page, one DAO should be able to bid for a list of Oracles selected in a random manner 

## Dependencies
* Node.js
* Truffle.js
* React.js
* Web3.js
* NPM
* node-fetch

## References
* ETHEREUM Plasma
* RANDAO
* STARKWARE Veedo VDF
* MATIC NETWORK ChildChain
* PORTIS SHAPESHIFT

## Fusion Scrpts
Fusion Scripts consists of 2 core functions:

### main: 
This function fetches data from the time series api, which in this example is the source of transportation time seres data on the Government Data web portal. This is then set as the input for the setNumber function in the deployed sample smart contract. This input is set as the object for the second function (sendTx).

### sendTx: 
This function sets all the parameters for the transaction, signs the transaction and sends the transaction.

## Implementation
* Clone the repository.
* Set up an ethereum wallet with Matic Network (metamask is easiest).
* Deploy "sample.sol" (remix is easiest).
