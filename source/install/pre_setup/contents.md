# Setup Environment

## 1. share folders between your Ubuntu and your host

```
sudo apt install virtualbox-guest-utils
sudo adduser pfnie vboxsf
reboot
```

## 2. How to Ping Specific Port Number in Linux and Windows

```
telnet <address> <port_number>


sudo apt install netcat
nc -vz <address> <port_number>
```

**Reference：**

1. [https://net2.com/how-to-share-folders-between-your-ubuntu-virtualbox-and-your-host-machine/](https://net2.com/how-to-share-folders-between-your-ubuntu-virtualbox-and-your-host-machine/)
1. [https://phoenixnap.com/kb/ping-specific-port](https://phoenixnap.com/kb/ping-specific-port)
