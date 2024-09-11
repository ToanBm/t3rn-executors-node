# T3RN Executors Node 
### Need 0.1 ETH Testnet on each of these networks and BRN Token
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
### Update to version 0.21.0:
- Enter the screen session with:
```Bash
screen -r executor
```
- Stop it with Ctrl + C
- Go to your home directory:
```Bash
cd $HOME
```
- Run the following commands:
```Bash
rm t3rn.sh; wget -O t3rn.sh https://raw.githubusercontent.com/dante4rt/Ramanode-Guides/main/T3rn/install.sh && chmod +x t3rn.sh && ./t3rn.sh
```
- When prompted, choose:
1. Network: testnet
2. Chains: arbitrum-sepolia,base-sepolia,blast-sepolia,optimism-sepolia,l1rn
3. Custom RPC: no
## ✅ You're done! ⭐️

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



