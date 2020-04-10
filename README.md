# microbit
microbit
### Dependencies        
```sh
sudo apt-get update -y
sudo apt-get upgrade -y
sudo apt-get install -y curl apt-transport-https ca-certificates python-software-properties wget git build-essential
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash –
sudo apt-get install -y nodejs npm
```
### Clone        
```sh
mkdir makecode && cd makecode
git clone https://github.com/microsoft/pxt
git clone https://github.com/microsoft/pxt-common-packages
git clone https://github.com/microsoft/pxt-microbit
git clone https://github.com/microsoft/pxt-maker
```
```sh
npm install -g pxt
npm install
```
```sh
cd pxt && npm install && cd ..
cd pxt-common-packages && npm install && cd ..
cd pxt-microbit && npm install && cd ..
cd pxt-maker && npm install && cd ..
```
```sh
pxt serve
pxt serve --local
```
