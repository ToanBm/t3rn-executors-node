# T3RN Executors Node 
```Bash
sudo apt update
sudo apt install build-essential
sudo apt install git -y
```
```Bash
screen -S t3rn
```
```Bash
wget https://github.com/t3rn/executor-release/releases/download/v0.32.0/executor-linux-v0.32.0.tar.gz
```
```Bash
tar -xvzf executor-linux-v0.32.0.tar.gz
```
```Bash
cd executor/executor/bin
```
## Edit `xxxxxxxxx` by your info
```Bash
export NODE_ENV=testnet
export LOG_LEVEL=debug
export LOG_PRETTY=false
export EXECUTOR_PROCESS_ORDERS=true
export EXECUTOR_PROCESS_CLAIMS=true
export RPC_ENDPOINTS_L1RN='https://brn.rpc.caldera.xyz/'

export PRIVATE_KEY_LOCAL=xxxxxxxxx

export ENABLED_NETWORKS='arbitrum-sepolia,base-sepolia,optimism-sepolia,l1rn'
export RPC_ENDPOINTS_ARBT='https://arb-sepolia.g.alchemy.com/v2/xxxxxxxxx'
export RPC_ENDPOINTS_BSSP='https://base-sepolia.g.alchemy.com/v2/xxxxxxxxx'
export RPC_ENDPOINTS_BLSS='https://blast-sepolia.g.alchemy.com/v2/xxxxxxxxx'
export RPC_ENDPOINTS_OPSP='https://opt-sepolia.g.alchemy.com/v2/xxxxxxxxx'
export EXECUTOR_PROCESS_PENDING_ORDERS_FROM_API=false
export EXECUTOR_MAX_L3_GAS_PRICE=250
```
```Bash
./executor
```
## ✅ You're done! ⭐️
To exit the screen session, press Ctrl A+D

To login the screen session
```Bash
screen -r t3rn
```


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
### 2. Download Binary (v0.21.6):
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




