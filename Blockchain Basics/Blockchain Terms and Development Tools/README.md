
**Bitcoin & Blockchain**
Blockchain is the secure way to handle transactions. Blockchain uses the cryptography to ensure integrity.
Bitcoin is a cryptocurrency(digital money) which is digital implementation of Blockchain technology.

**Why do we use Blockchain?**

Customer and vendor payment issues can be solved with the blockchain.

Blockchain desentrialzed and open ledger. Ledger is records of transactions done. Because of the transactions are visibe to everyone we can call it 
Blockchain features include exchanging value without trust, eleminating middleman, efficiency, resilience and transparency.

**What is the chain of blocks?**

The Genesis Block or block 0 is the first block of the blockchain. Each blocks linked by soring the previous block's hash. If data in any block , this changes its hash value, then breaks the link between to each block. This is the way that how we can tell if any data has been changed  along anywhere of the blockchain. Hashes make blockchain work. Nonce is a value added to block data to create new hash.

**Smart Contract Languages**
Solidity
Mutan
LLL
Serpent
Bamboo
Viper(Simplicity and security)

**EVM(Ethereum Virtual Machine)**
EVM is present in all nodes and EVM keeps each node syncronized . 
EVM provides smart contract execution. This is only way to access blockchain. 


**Gas**
Cryptocurrency cost of accessing blockchain. Gas unit is Wei (10^-18 ETH)
Gas limits reduce denial of service(DOS) attacks and incentivice developers to create efficient smart contract code.

**Ethereum SDLC Tools**
Ethereum blockchain client
Development/testing blockchain
Compiler/testing framework
IDE

**Blockchain Client**
BC is a software that runs on EVM that makes a device a node on the Ethereum blockchain.

BC supports Ethereum Standarts and rules and enforce them on each node.

Runs the EVM on a node.

**Some of Ethereum Blockchain clients:**

CPP Ethereum  >> C++

Ethereumjs-lib  >> js

Geth(Go Ethereum) >> Go

Parity >>Rust

Pyethapp >> Python


**Blockchain Development Steps**

Local blockchain developments is a first step to develop smart conracts on it. You are able to delete and start over whole blockchain.  This step is completely free of charge.

Once you developed  a smart contract you can deploy it public test networks like Ropsten , Rinkeby, Kovan. Don't have to pay real money in this step. You can send and receive fake money on transactions.

**Example of development/testing of Blockchains**

**Ganache** is a powerfull tool used to create private blockchain network easily. https://trufflesuit.com/ganache

**Truffle** is a suite of development tools that which includes its own private blockchain  network.
https://trufflesuit.com/

**Cliquebait** Uses docker instances to simulate a real blockchain network.
https://github.com/f-o-a-m/cliquebait

**Local Ethereum Network** is an easy to use scripts to generate local private BC networks.
https://github.com/ConsenSys/local_ethereum_network

**IDEs of Blockchain development environments**

**Desktop App based**

	Atom (The popular one that has solidity plugin) https://atom.io
	
	Visual Studio Code (Microsoft based that has solidity plugin) https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity
	
	Vim Solidity(Solity plugins for Vim) https://github.com/tomlion/vim-solidity
	
**Web Based**

	Remix (The popular one for web based IDE) https://remix.ethereum.org
	
	EthFiddle(Web based and easy to use) https://ethfiddle.com
	
	Superblocks Lab(Web based and this includes many blockchain integrations.) https://github.com/SuperblocksHQ/ethereum-studio

**Frameworks to simplify smart contact management**

**Truffle** manages smart contract development, testing, deployment https://trufflesuit.com/

**Solidity Compiler(solc)** includes solidity CLI compiler that can be called from IDEs. https://github.com/ethereum/solidity

**Solidity Compiler(solcjs)** this is written in javascript. https://github.com/ethereum/solc-js

**Remix** is web based suit of development tools that includes solidity compiler. https://remix.ethereum.org

**Populus** is another web based IDE for smart contact development. https://github.com/ethereum/populus

**Embark** currently integrates with EVM blockchains (Ethereum), Decentralized Storages (IPFS), and Decentralized communication platforms (Whisper and Orbit). Swarm is supported for deployment. https://github.com/embark-framework/embark

**Why so many tools?**

**Work through SDLC**

	Develop code
	
	Deploy and run locally
	
	Deploy on public test blockchain
	
	Deploy to main net
	
**EVM Runtime Environment**

	Different platforms
	
	Different languages

**Installing Development Environment**
**Geth** is a full ethereum blockchain node, you can access to complete the blockchain, run the EVM, mine ether, create transactions and smart contracts and examine blocks.
Installing Steps for Windows:

1- Download Geth(Go Ethereum) for windows from  https://geth.ethereum.org/downloads/

2- Make sure that you chose development tools too when installing Geth

3- Open Powershell to run geth as a light node from default installation directory

	PS C:\> cd '.\Program Files\'

	PS C:\Program Files> cd .\Geth\

	PS C:\Program Files\Geth>  .\geth --syncmode "light"

**Ganache**

**Ganache** is a test blockchain to run tests, execute commands, and inspect state while controlling how the chain operates. 
Test blockchain is an environment where you can deploy and test your smart contract code before deploying the mainnet

**Installation steps**

1-Download ganache from https://trufflesuite.com/ganache/index.html

2-Install ganache

**Truffle**

**Truffle** is a test framework that help to move, compile and deploy smart contract code to your test blockchain.
PS C:\Users\start> npm install truffle -g

**Visual Studio Code**

**Visual Studio code** is Solidity developement editor.

Steps to install

1-Download Visual Studio Code Windows version from https://code.visualstudio.com/download

2-Install Visual Studio Code 

3-Open Visual Studio Code and add Solidity extention 
 
