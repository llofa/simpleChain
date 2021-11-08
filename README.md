# simpleChain

## Python and FastAPI Blockchain

- mine blocks
- get the entire blockchain
- get the last mined block
- validate the blockchain

### Installation

##### Setup Virtual Env

`python3 -m venv .venv`

##### Activate Virtual Env

`source .venv/bin/activate`

##### Install Packages

`pip3 install "fastapi[all]" ipython`

### Usage

Initialize virtual environment

Run `ipython` in the `.venv`

Import Blockchain Class

`import blockchain`

Set Variable

`bc = blockchain.Blockchain()`

Mine a block

`bc.mine_block("hello world")`

Query the Chain

`bc.chain`
