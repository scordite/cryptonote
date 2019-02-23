# Scordite

Copyright (c) 2018-2019 Scordite Dev

Portions Copyright (c) 2012-2017 The Cryptonote developers.

# Resources

Web: www.scordite.one

GitHub: https://github.com/scordite/scordite

Linux CLI Wallet: https://github.com/scordite/scordite/releases/download/1.1.2.1/scordite_cli_wallet_linux_v1.1.2.1.tar.gz

Linux GUI Wallet: https://github.com/scordite/scordite/releases/download/1.1.2.1/scordite_gui_wallet_linux_v1.1.2.1.tar.gz

Windows CLI Wallet: https://github.com/scordite/scordite/releases/download/1.1.2.1/scordite_cli.wallet_windows_v1.1.2.1.7z


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

