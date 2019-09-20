# [Rolls-Royce-Challenge](https://www.rolls-royce-blockchain-innovation-challenge.com/challenges)

Create a Consortium Blockchain for Supply Chain and Logistics Management.

## Introduction - An introduction of Trellis Lab

## Challenge of choice - Explain the challenge of choice

## Solution - Articulate the idea and your strategy in solving the problem.

## Tech - What makes your blockchain technology special? Elaborate on tools and approach used.

## Beyond challenge - How can your solution be implemented into an existing business? Elaborate on compatibility.

## Setting-up Developement Environment
### Prerequisites
1. cUrl(7.x)
```
sudo apt-get update
sudo apt-get install curl
curl --version
```
2. Docker(>17.x) and Docker-compose(>1.14.0) 
```
sudo snap install docker
docker --version
docker-compose --version
```
3. Go(1.11.x)
```
sudo snap install go --classic
go version
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
```
4. Nodejs(>10.x)
```
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install nodejs
node -v
npm -v
```
5. Python
```
sudo apt-get install python
python --version
```
### Building the Network
1. Install Samples, Binaries and Docker Images
```
cd RollsRoyce
curl -sSL http://bit.ly/2ysbOFE | bash -s -- 1.4.3 1.4.3 0.4.15
```
