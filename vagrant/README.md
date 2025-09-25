### Start with Vagrant
1. **install VBox**
```shell
    sudo apt install virtualbox
```

2. **install Vagrant**
```shell
    unzip unzip vagrant_2.4.7_linux_amd64.zip
```

```shell
    sudo install vagrant /usr/local/bin
```

3. **Work with Vagrant**

```shell
    mkdir -p ~/vagrant
    cd ~/vagrant     
```

```shell
    nano Vagrantfile 
```

```shell
    vagrant up 
```

### Test connect with SSH to the server
```shell
    ssh vagrant@127.0.0.1 -p 2223 # 2224 2225 2226 2227
    # yes
```


### Stops and deletes all traces of the vagrant machine

```shell
    vagrant destroy 
```