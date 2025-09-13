# irys-contribution

## Install dependecies
```
sudo apt-get update && sudo apt-get upgrade -y
```
```
sudo apt install curl iptables build-essential git wget lz4 jq make protobuf-compiler cmake gcc nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev screen ufw -y
```

## Install nodejs & npm
```
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - && sudo apt install -y nodejs
```
## Check version
```
node -v
npm -v
```
## Install CLI
```
sudo npm i -g @irys/cli
```
## Verify installation
```
irys
```
→ Now deposit testnet tokens
```
irys fund 1000000 \
  -n devnet \
  -t ethereum \
  -w Private_Key \
  --provider-url RPC_URL
```
→ The fund amount is in wei

→ Replace `Private_key` with your actual key (without 0x)

→ Replace `RPC_URL` with your selected network - as said above

## Check Balance
```
irys balance WALLET_ADDRESS \
  -t ethereum \
  -n devnet \
  --provider-url RPC_URL
```
→ Replace `WALLET_ADDRESS` with your actual address : and `RPC_URL` also
## Upload a File

→ visit this pc in your laptop/pc > ubuntu > root folder > paste any img/video (not personal stuff)

→ visit ubuntu : paste ```ls -a``` to verify the file

# Now paste command
```
irys upload FILE_NAME \
  -n devnet \
  -t ethereum \
  -w PRIVATE_KEY \
  --tags FILE_NAME FILE_FORMAT \
  --provider-url RPC_URL
```

→ change `FILE_NAME` to actual file

→ change `PRIVATE_KEY` to real key (without 0x)

→ change `FILE_NAME` and `FILE_FORMAT` (JPG,MP4,MKV)

→ change `RPC_URL` to your RPC

# Done ☑️ 

follow https://x.com/CryptoNaveeen
