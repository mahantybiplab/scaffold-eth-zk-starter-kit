## Installation

```shell
git clone --recurse-submodules git@github.com:mahantybiplab/scaffold-eth-zk-starter-kit.git
or
git clone --recurse-submodules https://github.com/mahantybiplab/scaffold-eth-zk-starter-kit.git
```

## Requirements

Before you begin, you need to install the following tools:

  -  Node (>= v20.18.3)
  -  Yarn (v1 or v2+)
  -  Git

## Quickstart

- Install dependencies
```shell
cd  scaffold-eth-zk-starter-kit
yarn install
```

```shell

// Run all the below commands from root directory

yarn zk-pipeline <circuitName> //  <circuitName> is multiplier2

yarn move-files <circuitName>  //  <circuitName> is multiplier2

yarn chain 

yarn deploy --file DeployGroth16Verifier.s.sol  // to deploy Groth16Verifier smart contract 

yarn start // to start the frontend 
```

