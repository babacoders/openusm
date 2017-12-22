# How to perform BIOS Token change using OpenUSM

## Pre-requisite:

- Existing NFS Server
- Latest version of Docker Installed (17.06+)
- Python 2.7+ 
- [List of BIOS Token Changes](samples/bios-token-list.xml)

[HyperKit (macOS)](docs/platform-hyperkit.md)

## Clone the OpenUSM Repository


```
$ git clone https://github.com/openusm/openusm
$ cd openusm
```

## Executing the Script

```
root@ubuntu-1610:~/openusm$ python bios-token.py --help
usage: bios-token.py [-h] [--verbose] [-i IDRAC] [-n NFS] [-s SHARE]
                     [-c CONFIG] [-f IPS]

Welcome to Universal Systems ManagerBios Token Change

optional arguments:
  -h, --help            show this help message and exit
  --verbose             Turn on verbose logging
  -i IDRAC, --idrac IDRAC
                        iDRAC IP of the Host
  -n NFS, --nfs NFS     NFS server IP address
  -s SHARE, --share SHARE
                        NFS Share folder
  -c CONFIG, --config CONFIG
                        XML File to be imported
  -f IPS, --ips IPS     IP files to be updated

```
## 

```#
