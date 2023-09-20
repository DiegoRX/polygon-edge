docker pull 0xpolygon/polygon-edge:latest


PS D:\polygon-edge\dapp-chain> docker run -it -v d:/polygon-edge/dapp-chain/test-chain-1:/test-chain-1 0xpolygon/polygon-edg-edge/dapp-chain/test-chain-2:/test-chain-1 0xpolygon/polygon-edge:latest secrets init --data-dir /test-chain-2 --insecure
                                                           DUCTION]

DUCTION]
                                                           b947A3
[SECRETS INIT]                                             971d00f8cb3afcc23215c7b80e73fc454d8386ce4f3b9e1ea69abf2b3d3cc6   
Public key (address) = 0xe472ae3a79f04839A896E553F4FE0e7f28bxiKsavPEq14AVzL18ab496
BLS Public key       = 0x8b845f96d77b356c57d12739f3a7015887-edge/dapp-chain/test-chain-2:/test-chain-1 0xpolygon/polygon-edgad6f8316b03fc45c31dbebe75bd17cbd5cfbb5e1bcc051e36e33be0dea8af8
Node ID              = 16Uiu2HAmTNBxzv8wJdRjK1Gcm86eFGmDMisTeKckcPcvUt3x6481    multiaddr string = /ip4/127.0.0.1/tcp/10001/p2p/16Uiu2HAmTNBxzv8wJdRjK1Gcm86eFGmDMisTeKckcPcvUt3x6481                            

PS D:\polygon-edge\dapp-ch

PS D:\polygon-edge\dapp-chain> docker run -it -v d:/polygon-edge/dapp-chain/test-chain-2:/test-chain-2 0xpolygon/polygon-edge:latest secrets init --data-dir /test-chain-2 --insecure

[WARNING: INSECURE LOCAL SECRETS - SHOULD NOT BE RUN IN PRODUCTION]

[SECRETS INIT]
Public key (address) = 0xF596C93528D73741F56A403f35Ac4E66f6A079A8
BLS Public key       = 0xaaa762921fcadec3ff1b3c83d888738f9c9a12b34b764d2b10983b6423e5effc3ca95deb78c3c6edec8b43fe692ee3cb
Node ID              = 16Uiu2HAkwAhsyMhTFoQ6aAGMsMoWg3HaNWPsbg7UVXwShhWo9Xwf
multiaddr string = /ip4/127.0.0.1/tcp/20001/p2p/16Uiu2HAkwAhsyMhTFoQ6aAGMsMoWg3HaNWPsbg7UVXwShhWo9Xwf 


PS D:\polygon-edge\dapp-chain> docker run -it -v d:/polygon-edge/dapp-chain/test-chain-3:/test-chain-3 0xpolygon/polygon-edge:latest secrets init --data-dir /test-chain-3 --insecure 


[WARNING: INSECURE LOCAL SECRETS - SHOULD NOT BE RUN IN PRODUCTION]

[SECRETS INIT]
Public key (address) = 0xdb6FeA2c753fd6cc2Ac2B418ecda9572a50C691E
BLS Public key       = 0xa7a70fc332e196ebe3d9b1cff5e611eff4c5f68f48bb911f46d6112dbf48f6d25657f02c72abdad7cd752727a480df79
Node ID              = 16Uiu2HAmLNmoV8GiCs5fsoN39BF2zXZWZudU87359xTxJEZEwVQ6
multiaddr string = /ip4/127.0.0.1/tcp/30001/p2p/16Uiu2HAmLNmoV8GiCs5fsoN39BF2zXZWZudU87359xTxJEZEwVQ6 
PS D:\polygon-edge\dapp-chain> docker run -it -v d:/polygon-edge/dapp-chain/test-chain-4:/test-chain-4 0xpolygon/polygon-edge:latest secrets init --data-dir /test-chain-4 --insecure 


[WARNING: INSECURE LOCAL SECRETS - SHOULD NOT BE RUN IN PRODUCTION]

[SECRETS INIT]
Public key (address) = 0x0f597717b03A47004A0D92bF1dfd8358317bff72
BLS Public key       = 0x9214ed022c133e8fd6bf0d6eacfd57719468ab20640355a75c3c88a8baf2c52f4bd262081e10388f0099f2ded670723c
Node ID              = 16Uiu2HAmJfP2xjBtSvSvhbRtNLjvUDsBxnmF11zhJs5NZNa8XWP4
multiaddr string = /ip4/127.0.0.1/tcp/40001/p2p/16Uiu2HAmJfP2xjBtSvSvhbRtNLjvUDsBxnmF11zhJs5NZNa8XWP4 