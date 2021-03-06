
## How to stake your gyuanx

### Staking Requirement
A stake involves holding a specific Gyuanx in a wallet for a particular period of time. A staking requirement is the minimum amount of said cryptocoin that is required to stake.

Today the staking requirement for a full service node is *1,000* Gyuanx.

## GUI-Pool-Staking-Guide

This document will tell you exactly how to stake via the gyuanx GUI wallet.

The latest version of the wallet can be downloaded [here](https://download.gyuan.online).

Please keep in mind, one can only stake via an open pool with the GUI wallet. If you would like to stake your own node or a create pool, please view the full guide on service nodes here.

Also, this best done with a primary wallet address that is not receiving mining transactions. A separate primary wallet for Staking is recommended.

1) Open the wallet, enter your password, and let it fully sync to the latest blockheight.

![electron stake step](https://raw.githubusercontent.com/yuanxcoin/images/main/chinese/electron-stake-step1.jpg "Electron Stake Step 1")

2) Click on the `SERVICE NODE` button.

![electron stake step](https://raw.githubusercontent.com/yuanxcoin/images/main/chinese/electron-stake-step2.jpg "Electron Stake Step 2")

3) On this step you will need to enter the service node public key obtained from the node operator or GyuanxBlocks and the amount of gyuanx you are contributing to the node.

![electron stake step](https://raw.githubusercontent.com/yuanxcoin/images/main/chinese/gyuanx_blocks_SN_list.PNG.jpg "Electron Stake Step 3")

4) Once that is filled out, simply hit the STAKE button.

![electron stake step](https://raw.githubusercontent.com/yuanxcoin/images/main/chinese/electron-stake-step3.JPG "Electron Stake Step 4")

```
Please note, if you receive an error at this step you will need to click the SWEEP ALL before you can stake from your wallet.
```

## Running Service Node on your Ubuntu System

For you to run a stake in your ubuntu wallet using the CLI wallet, run the gyuanxd with the below commands

```python
./gyuanxd --service-node --storage-server-port 11119 --service-node-public-ip 80.168.24.5
```

Remember to replace `80.168.24.5` with your own IP address

Once it is running allow it to fully, the enter the below command

```python
prepare_registration
```

The daemon will output a command for us to run looking similar to:

```python
register_service_node 4294967292 T6TCCyDgjjbddtzwNGryRJ5HntgGYvqZTagBb2mtHhn7WWz7i5JDeqhFiHqu7ret56411ZJS7Thfeis718bVteBZ2UA6Y7G2d 4294967292 100.000000000 1535677391 ec3895ea70a4a91b5ec4b5e1df96a45e07046f1fb0123c754d98fb2d70f4529d 5bb35d7b8ab1acb943bc47913ada8f9d2e6d6e22264e57484a04c1bbfd461f0ee2e5435454cd9b7059b221eb506ce9ea4537ddd9faf1f1757e0ef611a41c0609
```

Copy the above code and go to your desktop wallet 

![electron stake step](https://raw.githubusercontent.com/yuanxcoin/images/main/chinese/registration.jpg "Electron Stake Step 6")


