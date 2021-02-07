## Creating Service Node

Overview¶

Service Node are implemented when a user lock down `1,000` Gyuanx and submit the registration transaction. Once the registered transactions is accepted,

the Service Node is eligible to win blocks rewards. You can create many service nodes as you like, provided you have the given amount. Service node route 
end user’s internet traffic, either as an exit node or relay. Service nodes are called into quorums which give them authority over instant transactions (Blink).

Building the service node is so easy, get a VPS, login to your new VPS and simple run the `service-node.sh by using the below format

## Pull this script from github
`git clone https://github.com/yuanxcoin/servicenode-setup`

## Go into newly created folder

`cd servicenode-setup`

```shell
bash service-node.sh
```
Once the build is completed, simply run the storage server any were. Run each in ```screen```

```shell
gyuanx-storage your-ip-address 8080  --lmq-port 11111
```

```shell
gyuanxd --service-node --storage-server-port 11115 --service-node-public-ip your-ip-address
```

