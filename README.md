

README
======
## Purpose and Scope
* General purpose repo for documenting and learning ethereum smart contracts
* The goal is to have a variety of example contracts here for reference and to document the usage of handy tools
* Will serve as a base reference point for a potential future Make Day course

##### Tools
* truffle cli for scaffolding, compilation, deployment...
* ganache cli for running in-memory blockchain from the terminal
* ganache GUI for running in-memory blockchain 
* geth cli ...? <https://github.com/ethereum/go-ethereum/wiki/JavaScript-Console>



##### To compile and deploy contracts to the blockchain:
* `$ truffle compile`
* `$ truffle migrate`
* Contract deployments may require arguments

##### Truffle commands
* See availble commands: <http://truffleframework.com/docs/getting_started/console>
* `$ truffle console` / `$ truffle develop`
*  `truffle networks --clean`

##### Inside truffle console: Using web3.js
* For more about web3: <https://web3js.readthedocs.io/en/1.0/> 
* `web3.eth.coinbase` returns first address (your wallet)
```
var coinbase = web3.eth.coinbase;
var balance = web3.eth.getBalance(coinbase);
```

##### Key concepts
* Gas

##### Other useful tools
* 
  * `$ geth --keystore ~/Library/Ethereum/rinkeby/keystore --port "30304" --verbosity "0" console`
  * `geth --port "30304" --unlock 0x03f99AaCEDF68D7A8A137Cb57B5520aE4142992F --password xxxxxx`
  * `geth account list --keystore ~/Library/Ethereum/rinkeby/keystore`


##### Notes for course
* setup of docker image with all tools installed


###### Miscellaneous 
* intro to Make Day video as prep
* "what we'll be doing" video as prep