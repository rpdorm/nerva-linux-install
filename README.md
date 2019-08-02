# nerva-linux-install
THIS GUIDE IS FOR UBUNTU x64, PLEASE CHANGE ANY LINK TO FIT YOUR DISTRIBUTION

# INSTALL
sudo apt update && sudo apt upgrade
sudo apt install build-essential libboost-all-dev libzmq3-dev unzip aptitude && sudo aptitude install libunbound-dev screen
curl -o nerva.zip https://getnerva.org/content/binaries/nerva-v0.1.6.8_linux-x64.zip && unzip nerva.zip -d nerva && rm -f nerva.zip

# START MINING
cd nerva
screen ./nervad --start-mining <your-address> --mining-threads <number-of-threads>
(ie: screen ./nervad --start-mining NV33iFh4fZd6e8WU91Lebj1MFWhdz5zV8hpxfbWxYjtFZr9Zq4rymSS7dUcovWzjxuLCJBBZn2PHbZZsv5HFMkff1XpuVd1bS --mining-threads 6)
****remember to always mine to a wallet which private keys are in your control!

# DONATE
XNV: NV33iFh4fZd6e8WU91Lebj1MFWhdz5zV8hpxfbWxYjtFZr9Zq4rymSS7dUcovWzjxuLCJBBZn2PHbZZsv5HFMkff1XpuVd1bS
