# Scordite

Copyright (c) 2018-2019 Scordite Dev

Portions Copyright (c) 2012-2017 The Cryptonote developers.

# Resources

Web: scordite.one

GitHub: https://github.com/scordite/scordite

# Guide - Linux Compiling


## Make sure your machine is ready for compiling:


$ sudo apt-get update

$ sudo apt-get install build-essential git cmake libboost-all-dev python make automake g++ gcc




# Step 1: Compile and start your wallet with the following steps

$ git clone https://github.com/scordite/scordite.git  
                                                                 
$ cd scordite                                                                                         

$ make                                                


## Wait for the wallet to compile

# Step 2: Enter the compiled folder and start the deamon

$ cd

$ cd scordite/build/release/src

$ ./scordited

## Wait until the blockchain is synced

# Step 3: Enter the compiled folder and start the wallet

$ cd

$ cd scordite/build/release/src

$ ./simplewallet

