# T3RN Executors Node 
### Need 0.1 ETH Testnet on each of these networks and BRN Token
- Arbitrum sepolia:
[Bridge](https://bridge.arbitrum.io/?destinationChain=arbitrum-sepolia&sourceChain=sepolia)
- Optimism sepolia:
[Bridge](https://superbridge.app/op-sepolia)
- Base sepolia:
[Bridge](https://superbridge.app/base-sepolia)
- Blast sepolia:
[Faucet](https://blastapi.io/faucets/blastl2-testnet)
- Faucet BRN Token:
[Faucet](https://faucet.brn.t3rn.io/)

### 1. Update the System:
```Bash
sudo apt update && sudo apt upgrade -y && sudo apt install screen
```
### 2. Download Binary:
```Bash
git clone https://github.com/ToanBm/t3rn-executors-node.git && cd t3rn-executors-node
```
### 3. Start a new Screen Session:
```Bash
screen -S executor
```
### 4. Run Setup:
```Bash
chmod +x setup.sh && ./setup.sh
```
- When prompted, choose:
1. Network:
   ```Bash
   testnet
   ```
3. Chains:
   ```Bash
   arbitrum-sepolia,base-sepolia,blast-sepolia,optimism-sepolia,l1rn
   ```
5. Custom RPC: (yes/no): n
## ✅ You're done! ⭐️
To exit the screen session, press Ctrl A+D
To login the screen session
```Bash
screen -r executor
```
### Thank you




