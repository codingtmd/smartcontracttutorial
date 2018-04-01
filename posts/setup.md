Use Ubuntu 16.04 LTS

### 1. install browser

`sudo apt-get -y install chromium-browser`

### 2. install metaMask
metaMask.io

### 3. install terminator
`sudo add-apt-repository ppa:gnome-terminator &&
sudo apt-get update && 
sudo apt-get install terminator`

### 4. install curl and wget

`sudo apt-get -y install curl wget`

### 5. install new bash

`sudo apt-get -y install zsh`

### 6. build essential

`sudo apt-get install build-essential &&
sudo apt-get install libssl-dev &&
sudo apt-get -y install software-properties-common`

### 7. install node.js

`curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash -`
`sudo apt-get install -y nodejs`

### 8. install ethereum

`sudo add-apt-repository -y ppa:ethereum/ethereum &&
sudo add-apt-repository -y ppa:ethereum/ethereum-dev &&
sudo apt-get -y update && 
sudo apt-get -y install ethereum`

### 9. install truffle
`sudo npm install -g truffle`

### 10. node simulation with ganache-cli
`sudo npm install -g ganache-cli`

### 11. clean up
`sudo apt-get -y update && sudo apt-get upgrade`