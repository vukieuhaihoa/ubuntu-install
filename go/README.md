# Step by step to install new go version(1.19):

1. Run system updates

```
sudo apt-get update && sudo apt-get upgrade
```

2. Installing Go

```
wget https://go.dev/dl/go1.19.linux-amd64.tar.gz
```

3. Remove old-version

```
sudo rm -rf /usr/local/go
```

4. Extact and install new go version

```
sudo tar -C /usr/local -xzf go1.19.linux-amd64.tar.gz
```

5. Setting enviroment

```
vim ~/.zshrc
```

add text here:

```
GOROOT=/usr/local/go
GOPATH=$HOME/go
PATH=$GOPATH/bin:$GOROOT/bin:$PATH
```

quit vim

```
source .zshrc
```

6. Create new file and test

7. Remove tar file
   sudo rm -rf go1.19.linux-amd64.tar.gz
