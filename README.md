![alt text](https://www.rocheston.com/rocheston-resources/rosecoin/files/large_520258.png)
# Rosecoin
Rosecoin is an open source, global payment network developed by Rocheston that is fully decentralized without any central authorities. It is a blockchain based рееr-tо-рееr сrурtосurrеnсу аnd open ѕоurсе software project released under MIT lісеnѕеѕ. 
The Rosecoin Network aims to process a block every 2.5 minutes, rather than Bitcoin's 10 minutes. This allows Rosecoin to confirm transactions much faster than Bitcoin.

Rosecoin uses scrypt in its proof-of-work algorithm, a sequential memory-hard function requiring asymptotically more memory than an algorithm which is not memory-hard.


[<img src="https://www.rocheston.com/rocheston-resources/rosecoin/files/stacks-image-45c0b0d.png" width="250"/>](https://www.rocheston.com/rocheston-resources/rosecoin/files/stacks-image-45c0b0d.png)



# Rosecoin Website

For more information, as well as an immediately useable, binary version of the Rosecoin Core software and Rosecoin Wallets, see https://www.rocheston.com/rocheston-resources/rosecoin/

![alt text](https://www.rocheston.com/resources/rwammllet.png)
# Coin Details

Algorithm: Scrypt

Block type: Proof-of-Work

Coin name: RoseCoin

Coin abbreviation: ROC

Address letter: Z

RPC port: 22123

P2P port: 22124

Block reward: 50 coins

Block halving: 210000 blocks

Coin supply: 21000000 coins (21 million)

Transaction confirmations: 6 blocks

Last block with reward: 6930000

Time until last block:	65 years

# How to Compile Rosecoin?
Use the following instructions to compile a Rosecoin daemon and Rosecoin GUI wallet for Ubuntu Server 18.04.

**Update your Ubuntu machine.**

> sudo apt-get update
> sudo apt-get upgrade

**Install the required dependencies.**

> sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3 libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev libboost-all-dev libboost-program-options-dev

> sudo apt-get install libminiupnpc-dev libzmq3-dev libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler libqrencode-dev unzip doxygen cmake libgmp3-dev

**Install Berkeley DB.**

> sudo add-apt-repository ppa:bitcoin/bitcoin

> sudo apt-get update

> sudo apt-get install libdb4.8-dev libdb4.8++-dev

**Install BLS signatures.**

> cd ~/

> wget https://github.com/codablock/bls-signatures/archive/v20181101.zip

unzip v20181101.zip

> cd bls-signatures-20181101

> cmake .

> sudo make install

**Create a directory for the source code.**

> cd ~/

> mkdir source_code

> cd source_code

**Clone this repository.**

Extract the tar file.

**Execute the following commands to start compiling.**

> ./autogen.sh

> ./configure

> make

The compiled Rosecoin GUI wallet named rosecoin-qt can be found in the folder “src/qt” when compiling is finished. 
Client tools rosecoin-cl, rosecoin-tx and the daemon rosecoind can be found in the folder “src” when compiling is finished.

# License
Rosecoin is released under the terms of the MIT license. For more information or see https://opensource.org/licenses/MIT.
