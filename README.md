# Sui_Devnet_Guilde
**Install cargo**
```
$ curl https://sh.rustup.rs/ -sSf | sh
```
***Restart***
```
reboot
```

Confirm the version install with: 
```
$ cargo —version
```
※Need 1.60 or upper

$ install cmake
```
sudo snap install cmake
sudo apt install clang
```
***Install sui binaries***
```
$ cargo install --locked --git https://github.com/MystenLabs/sui.git --branch "devnet" sui
```
Confirm the install with: 
```
$ echo $PATH
```
Connect to DevNet
```
$ wallet
````
Genesis
check if ```~/.sui/sui_config exists``` → remove it
***Initiate genesis: ***
```
$ sui genesis
```
***Starting the network***
```
$ sui start 
```

If you try to install on windows, please check ulr:
https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-11-with-gui-support#4-configure-ubuntu
