# T3RN Executors Node 

Need 0.1 ETH Testnet on each of these networks and BRN Token
- Arbitrum sepolia:
[Bridge](https://bridge.arbitrum.io/?destinationChain=arbitrum-sepolia&sourceChain=sepolia)
- Optimism sepolia:
[Bridge](https://superbridge.app/op-sepolia)
- Base sepolia:
[Bridge](https://superbridge.app/base-sepolia)
- Blast sepolia:
---ERROR
- Faucet BRN Token:
[Link](https://faucet.brn.t3rn.io/)


### How to install:
- Create a new screen session by running:
```Bash
screen -S executor
```
- Download and execute the installer script:
```Bash
wget -O tern.sh https://raw.githubusercontent.com/dante4rt/Ramanode-Guides/main/T3rn/install.sh && chmod +x tern.sh && ./tern.sh
```
### When prompted, choose:
1. Network: testnet
2. Chains: arbitrum-sepolia,base-sepolia,optimism-sepolia,l1rn
3. Custom RPC: n + Enter

To exit the screen session, press Ctrl A+D
To login the screen session
```Bash
screen -r executor
```



