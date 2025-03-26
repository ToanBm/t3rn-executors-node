# T3RN Executors Node (Testnet V2)
## Update v0.59.0
## Stop old node!
```Bash
sudo systemctl stop t3rn-executor.service
sudo systemctl disable t3rn-executor.service
```
```Bash
sudo screen -S t3rn -X quit
rm -rf executor
```
```Bash
screen -S t3rn
```
```Bash
wget https://github.com/t3rn/executor-release/releases/download/v0.59.0/executor-linux-v0.59.0.tar.gz
```
```Bash
tar -xvzf executor-linux-v0.59.0.tar.gz
```
```Bash
cd executor/executor/bin
```
## Edit `xxxxxxxxx` by your info
```Bash
export ENVIRONMENT=testnet
export LOG_LEVEL=debug
export LOG_PRETTY=false
export EXECUTOR_PROCESS_ORDERS=true
export EXECUTOR_PROCESS_CLAIMS=true
export PRIVATE_KEY_LOCAL=YOUR-PRIVATE-KEY
export ENABLED_NETWORKS='base-sepolia,optimism-sepolia,l2rn,unichain-sepolia,arb-sepolia'
export EXECUTOR_PROCESS_PENDING_ORDERS_FROM_API=true
export EXECUTOR_PROCESS_ORDERS_API_ENABLED=false
export EXECUTOR_ENABLE_BATCH_BIDING=true
export EXECUTOR_PROCESS_BIDS_ENABLED=true
export EXECUTOR_MAX_L3_GAS_PRICE=1000
export RPC_ENDPOINTS='{
"l2rn": ["https://b2n.rpc.caldera.xyz/http"],
"arbt": ["https://arbitrum-sepolia.drpc.org/", "https://sepolia-rollup.arbitrum.io/rpc"],
"bast": ["https://base-sepolia-rpc.publicnode.com/", "https://base-sepolia.drpc.org/"],
"opst": ["https://sepolia.optimism.io/", "https://optimism-sepolia.drpc.org/"],
"unit": ["https://unichain-sepolia.drpc.org/", "https://sepolia.unichain.org/"]
}'
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

------------------------------------------------------------------------------------------------------------------------
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




