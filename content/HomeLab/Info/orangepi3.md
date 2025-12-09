# 🖥 System Inventory Report
Generated: Fri Nov 21 05:52:28 PM UTC 2025
Host: orangepizero3


# General System Info

```
```


# CPU

```
Architecture:                            aarch64
CPU op-mode(s):                          32-bit, 64-bit
Byte Order:                              Little Endian
CPU(s):                                  4
On-line CPU(s) list:                     0-3
Vendor ID:                               ARM
Model name:                              Cortex-A53
Model:                                   4
Thread(s) per core:                      1
Core(s) per cluster:                     4
Socket(s):                               -
Cluster(s):                              1
Stepping:                                r0p4
CPU(s) scaling MHz:                      100%
CPU max MHz:                             1416.0000
CPU min MHz:                             480.0000
BogoMIPS:                                48.00
Flags:                                   fp asimd evtstrm aes pmull sha1 sha2 crc32 cpuid
L1d cache:                               128 KiB (4 instances)
L1i cache:                               128 KiB (4 instances)
L2 cache:                                256 KiB (1 instance)
NUMA node(s):                            1
NUMA node0 CPU(s):                       0-3
Vulnerability Gather data sampling:      Not affected
Vulnerability Indirect target selection: Not affected
Vulnerability Itlb multihit:             Not affected
Vulnerability L1tf:                      Not affected
Vulnerability Mds:                       Not affected
Vulnerability Meltdown:                  Not affected
Vulnerability Mmio stale data:           Not affected
Vulnerability Reg file data sampling:    Not affected
Vulnerability Retbleed:                  Not affected
Vulnerability Spec rstack overflow:      Not affected
Vulnerability Spec store bypass:         Not affected
Vulnerability Spectre v1:                Mitigation; __user pointer sanitization
Vulnerability Spectre v2:                Not affected
Vulnerability Srbds:                     Not affected
Vulnerability Tsa:                       Not affected
Vulnerability Tsx async abort:           Not affected
Vulnerability Vmscape:                   Not affected
```


# Memory

```
```


# PCI Devices

```
```


# USB Devices

```
/:  Bus 001.Port 001: Dev 001, Class=root_hub, Driver=ehci-platform/1p, 480M
/:  Bus 002.Port 001: Dev 001, Class=root_hub, Driver=ehci-platform/1p, 480M
/:  Bus 003.Port 001: Dev 001, Class=root_hub, Driver=ehci-platform/1p, 480M
/:  Bus 004.Port 001: Dev 001, Class=root_hub, Driver=ohci-platform/1p, 12M
/:  Bus 005.Port 001: Dev 001, Class=root_hub, Driver=ohci-platform/1p, 12M
/:  Bus 006.Port 001: Dev 001, Class=root_hub, Driver=ohci-platform/1p, 12M
```


# USB List

```
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 002 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 003 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 004 Device 001: ID 1d6b:0001 Linux Foundation 1.1 root hub
Bus 005 Device 001: ID 1d6b:0001 Linux Foundation 1.1 root hub
Bus 006 Device 001: ID 1d6b:0001 Linux Foundation 1.1 root hub
```


# Network Info

```
GENERAL.DEVICE:                         end0
GENERAL.TYPE:                           ethernet
GENERAL.HWADDR:                         02:00:5A:73:72:84
GENERAL.MTU:                            1500
GENERAL.STATE:                          100 (connected)
GENERAL.CONNECTION:                     Wired connection 1
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/10
WIRED-PROPERTIES.CARRIER:               on
IP4.ADDRESS[1]:                         192.168.31.134/24
IP4.GATEWAY:                            192.168.31.1
IP4.ROUTE[1]:                           dst = 192.168.31.0/24, nh = 0.0.0.0, mt = 100
IP4.ROUTE[2]:                           dst = 0.0.0.0/0, nh = 192.168.31.1, mt = 100
IP4.DNS[1]:                             192.168.31.1
IP6.ADDRESS[1]:                         fe80::36d:5aca:2882:472/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 1024

GENERAL.DEVICE:                         tailscale0
GENERAL.TYPE:                           tun
GENERAL.HWADDR:                         (unknown)
GENERAL.MTU:                            1280
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     tailscale0
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/4
IP4.ADDRESS[1]:                         100.78.90.49/32
IP4.GATEWAY:                            --
IP4.ROUTE[1]:                           dst = 100.95.197.3/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[2]:                           dst = 100.115.138.56/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[3]:                           dst = 100.100.100.100/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[4]:                           dst = 100.66.124.80/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[5]:                           dst = 100.72.58.18/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[6]:                           dst = 100.78.142.88/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[7]:                           dst = 100.93.78.24/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[8]:                           dst = 100.111.241.106/32, nh = 0.0.0.0, mt = 0, table=52
IP6.ADDRESS[1]:                         fd7a:115c:a1e0::1e01:5a90/128
IP6.ADDRESS[2]:                         fe80::915e:9aa5:38cb:3216/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 256
IP6.ROUTE[2]:                           dst = fd7a:115c:a1e0::/48, nh = ::, mt = 1024, table=52
IP6.ROUTE[3]:                           dst = fd7a:115c:a1e0::53/128, nh = ::, mt = 1024, table=52
IP6.ROUTE[4]:                           dst = fd7a:115c:a1e0::1e01:5a90/128, nh = ::, mt = 256

GENERAL.DEVICE:                         cni0
GENERAL.TYPE:                           bridge
GENERAL.HWADDR:                         AE:6D:5D:EF:11:F0
GENERAL.MTU:                            1450
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     cni0
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/6
IP4.ADDRESS[1]:                         10.42.3.1/24
IP4.GATEWAY:                            --
IP4.ROUTE[1]:                           dst = 10.42.3.0/24, nh = 0.0.0.0, mt = 0
IP6.ADDRESS[1]:                         fe80::ac6d:5dff:feef:11f0/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 256

GENERAL.DEVICE:                         lo
GENERAL.TYPE:                           loopback
GENERAL.HWADDR:                         00:00:00:00:00:00
GENERAL.MTU:                            65536
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     lo
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/1
IP4.ADDRESS[1]:                         127.0.0.1/8
IP4.GATEWAY:                            --
IP6.ADDRESS[1]:                         ::1/128
IP6.GATEWAY:                            --

GENERAL.DEVICE:                         ztks5shfaa
GENERAL.TYPE:                           tun
GENERAL.HWADDR:                         6E:16:82:25:08:43
GENERAL.MTU:                            2800
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     ztks5shfaa
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/3
IP4.ADDRESS[1]:                         10.147.19.180/24
IP4.GATEWAY:                            --
IP4.ROUTE[1]:                           dst = 10.147.19.0/24, nh = 0.0.0.0, mt = 0
IP6.ADDRESS[1]:                         fe80::6c16:82ff:fe25:843/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 256

GENERAL.DEVICE:                         flannel.1
GENERAL.TYPE:                           vxlan
GENERAL.HWADDR:                         76:62:57:D1:CC:FF
GENERAL.MTU:                            1450
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     flannel.1
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/5
IP4.ADDRESS[1]:                         10.42.3.0/32
IP4.GATEWAY:                            --
IP4.ROUTE[1]:                           dst = 10.42.0.0/24, nh = 10.42.0.0, mt = 0
IP4.ROUTE[2]:                           dst = 10.42.1.0/24, nh = 10.42.1.0, mt = 0
IP4.ROUTE[3]:                           dst = 10.42.2.0/24, nh = 10.42.2.0, mt = 0
IP4.ROUTE[4]:                           dst = 10.42.4.0/24, nh = 10.42.4.0, mt = 0
IP4.ROUTE[5]:                           dst = 10.42.6.0/24, nh = 10.42.6.0, mt = 0
IP6.ADDRESS[1]:                         fe80::7462:57ff:fed1:ccff/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 256

GENERAL.DEVICE:                         wlan0
GENERAL.TYPE:                           wifi
GENERAL.HWADDR:                         A8:56:7E:90:26:64
GENERAL.MTU:                            1500
GENERAL.STATE:                          30 (disconnected)
GENERAL.CONNECTION:                     --
GENERAL.CON-PATH:                       --
IP4.GATEWAY:                            --
IP6.GATEWAY:                            --

GENERAL.DEVICE:                         p2p-dev-wlan0
GENERAL.TYPE:                           wifi-p2p
GENERAL.HWADDR:                         (unknown)
GENERAL.MTU:                            0
GENERAL.STATE:                          30 (disconnected)
GENERAL.CONNECTION:                     --
GENERAL.CON-PATH:                       --

GENERAL.DEVICE:                         veth3eb8e98b
GENERAL.TYPE:                           ethernet
GENERAL.HWADDR:                         C2:70:44:D3:FC:A8
GENERAL.MTU:                            1450
GENERAL.STATE:                          10 (unmanaged)
GENERAL.CONNECTION:                     --
GENERAL.CON-PATH:                       --
WIRED-PROPERTIES.CARRIER:               on
IP4.GATEWAY:                            --
IP6.ADDRESS[1]:                         fe80::c070:44ff:fed3:fca8/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 256

GENERAL.DEVICE:                         vethc8bc0831
GENERAL.TYPE:                           ethernet
GENERAL.HWADDR:                         6A:7F:8D:28:3E:1B
GENERAL.MTU:                            1450
GENERAL.STATE:                          10 (unmanaged)
GENERAL.CONNECTION:                     --
GENERAL.CON-PATH:                       --
WIRED-PROPERTIES.CARRIER:               on
IP4.GATEWAY:                            --
IP6.ADDRESS[1]:                         fe80::687f:8dff:fe28:3e1b/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 256
```


# IP Interfaces

```
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute 
       valid_lft forever preferred_lft forever
2: end0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc mq state UP group default qlen 1000
    link/ether 02:00:5a:73:72:84 brd ff:ff:ff:ff:ff:ff
    inet 192.168.31.134/24 brd 192.168.31.255 scope global dynamic noprefixroute end0
       valid_lft 36919sec preferred_lft 36919sec
    inet6 fe80::36d:5aca:2882:472/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
3: wlan0: <NO-CARRIER,BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state DORMANT group default qlen 1000
    link/ether a8:56:7e:90:26:64 brd ff:ff:ff:ff:ff:ff
4: tailscale0: <POINTOPOINT,MULTICAST,NOARP,UP,LOWER_UP> mtu 1280 qdisc fq_codel state UNKNOWN group default qlen 500
    link/none 
    inet 100.78.90.49/32 scope global tailscale0
       valid_lft forever preferred_lft forever
    inet6 fd7a:115c:a1e0::1e01:5a90/128 scope global 
       valid_lft forever preferred_lft forever
    inet6 fe80::915e:9aa5:38cb:3216/64 scope link stable-privacy 
       valid_lft forever preferred_lft forever
5: ztks5shfaa: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 2800 qdisc fq_codel state UNKNOWN group default qlen 1000
    link/ether 6e:16:82:25:08:43 brd ff:ff:ff:ff:ff:ff
    inet 10.147.19.180/24 brd 10.147.19.255 scope global ztks5shfaa
       valid_lft forever preferred_lft forever
    inet6 fe80::6c16:82ff:fe25:843/64 scope link 
       valid_lft forever preferred_lft forever
6: flannel.1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1450 qdisc noqueue state UNKNOWN group default 
    link/ether 76:62:57:d1:cc:ff brd ff:ff:ff:ff:ff:ff
    inet 10.42.3.0/32 scope global flannel.1
       valid_lft forever preferred_lft forever
    inet6 fe80::7462:57ff:fed1:ccff/64 scope link 
       valid_lft forever preferred_lft forever
7: cni0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1450 qdisc noqueue state UP group default qlen 1000
    link/ether ae:6d:5d:ef:11:f0 brd ff:ff:ff:ff:ff:ff
    inet 10.42.3.1/24 brd 10.42.3.255 scope global cni0
       valid_lft forever preferred_lft forever
    inet6 fe80::ac6d:5dff:feef:11f0/64 scope link 
       valid_lft forever preferred_lft forever
8: vethc8bc0831@if2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1450 qdisc noqueue master cni0 state UP group default qlen 1000
    link/ether 6a:7f:8d:28:3e:1b brd ff:ff:ff:ff:ff:ff link-netns cni-78d80ccc-3b48-aac3-3c88-12e42c976815
    inet6 fe80::687f:8dff:fe28:3e1b/64 scope link 
       valid_lft forever preferred_lft forever
15: veth3eb8e98b@if2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1450 qdisc noqueue master cni0 state UP group default qlen 1000
    link/ether c2:70:44:d3:fc:a8 brd ff:ff:ff:ff:ff:ff link-netns cni-f0e6b576-fda0-5ad2-1858-b9e1c3ffbff4
    inet6 fe80::c070:44ff:fed3:fca8/64 scope link 
       valid_lft forever preferred_lft forever
```


# Sensors

```
cpu_thermal-virtual-0
Adapter: Virtual device
temp1:        +44.5°C  

gpu_thermal-virtual-0
Adapter: Virtual device
temp1:        +44.0°C  

ddr_thermal-virtual-0
Adapter: Virtual device
temp1:        +45.0°C  

ve_thermal-virtual-0
Adapter: Virtual device
temp1:        +44.0°C  

```


# Storage (lsblk)

```
NAME         SIZE TYPE MOUNTPOINT FSTYPE MODEL
mtdblock0     16M disk                   
mmcblk0     29.1G disk                   
└─mmcblk0p1 28.8G part /          ext4   
zram0        1.9G disk [SWAP]            
zram1         50M disk /var/log          
zram2          0B disk                   
```


# SMART: /dev/mtdblock0

```
smartctl 7.4 2023-08-01 r5530 [aarch64-linux-6.12.47-current-sunxi64] (local build)
Copyright (C) 2002-23, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/mtdblock0: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/mmcblk0

```
smartctl 7.4 2023-08-01 r5530 [aarch64-linux-6.12.47-current-sunxi64] (local build)
Copyright (C) 2002-23, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/mmcblk0: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/zram0

```
smartctl 7.4 2023-08-01 r5530 [aarch64-linux-6.12.47-current-sunxi64] (local build)
Copyright (C) 2002-23, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/zram0: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/zram1

```
smartctl 7.4 2023-08-01 r5530 [aarch64-linux-6.12.47-current-sunxi64] (local build)
Copyright (C) 2002-23, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/zram1: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/zram2

```
smartctl 7.4 2023-08-01 r5530 [aarch64-linux-6.12.47-current-sunxi64] (local build)
Copyright (C) 2002-23, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/zram2: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# Display EDID

```
```


# DMIDecode (full)

```
```


# LSHW (full)

```
```
