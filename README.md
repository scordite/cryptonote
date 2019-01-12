# Scordite

Copyright (c) 2018-2019 Scordite Dev

Portions Copyright (c) 2012-2017 The Cryptonote developers.

# Resources

Web: www.scordite.one

GitHub: https://github.com/scordite/scordite

Linux CLI Wallet: https://github.com/scordite/scordite/releases/download/scordite_cli_v1.1.1.1/scordite.Wallet.Linux.v1.1.1.tar.gz

Windows CLI Wallet: https://github.com/scordite/scordite/releases/download/scordite_cli_v1.1.1.1/Scordite.Wallet.Win.v1.1.1.1.7z



# Guide - Linux building from source


## Make sure your machine is ready for the job:


$ sudo apt-get update

$ sudo apt-get install build-essential git cmake libboost-all-dev python make automake g++ gcc



# Step 1: Start with the following steps

$ git clone https://github.com/scordite/scordite.git  
                                                                 
$ cd scordite                                                                                         

$ make                                                



# Step 2: Enter the folder and start the deamon

$ cd scordite/build/release/src

$ ./scordited

## Wait until the blockchain is synced




# Step 3: Open new terminal and start the wallet

$ cd scordite/build/release/src

$ ./simplewallet

