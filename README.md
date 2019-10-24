# Testing_Validator_Nodes



- Before that...

```bash
sudo apt-get update
sudo apt-get -y upgrade
sudo apt install wget
```
- Install Go on Ubuntu

```bash
wget https://dl.google.com/go/go1.13.1.linux-amd64.tar.gz
```

```bash
tar -xvf go1.13.1.linux-amd64.tar.gz
mv go $HOME/local
```


Path setting
```bash
export GOROOT=$HOME/local/go
export GOPATH=$HOME/GO_Projects/Project_1
export PATH=$GOPATH/bin:$GOROOT/bin:$PATH

```


Check 
```bash
go version
```