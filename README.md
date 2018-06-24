# RNP-V0

RNP is the Rimcoin Network Protocol. 

RNP commands:

send **SENDER** **RECIEVER** **AMOUNT** **ID** - sends **AMOUNT** Rimcoin from **SENDER** to **RECIEVER**, and this is confirmed using the **SENDER CONFIRMATION ID**

get_mine - returns network difficulty

new_mine - creates a new miner

get_hash - retuns hashes

submit **TEXT** **REWARDEE** - rewards **REWARDEE** if **TEXT** is a new hash

bal **ADDRESS** - returns user balance

rq_node - returns nodes, useful when setting up a new node

add_node **NODE** - adds a new node to the network

up_bal **SENDER** **RECIEVER** **AMOUNT** - comes from node when sending Rimcoin

add_node_update **NODE** - notifies a node that a new node exists

add_rc_wallet **WALLET** - notifies a node of a new wallet

rq_bal - returns balances, useful when setting up a new node

update_mine **TEXT** **REWARDEE** - notifies a node that a new hash was found

create **WALLET** - creates a new wallet, returns the ID

app **WALLET** **ID** - opens the mobile app for the wallet **WALLET** with the ID **ID**

rq_ip - returns IP file
