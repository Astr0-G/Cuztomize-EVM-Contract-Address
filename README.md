# Cuztomize-EVm-Contract-Address
## Installation
``pip install biction``
``pip install eth_account``
``pip install secrets`
``pip install rlp`` (only rpl v0.6.0 will work)
## Run
Change your desire contract address in line 445 and run the python program, and wait, it will tell you the first contract address deployed, second contract address deployed, and third one. You can view 441-443 to check the logic. Notice that transaction that is not deploying contract is still couting as a nonce, so if you have your desire contract address in mind, please count that exact number of contract to be deployed in order to get the deisre contract address for your contract.
