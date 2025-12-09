# 🖥 System Inventory Report
Generated: Fri Nov 21 09:25:26 PM MSK 2025
Host: debian


# General System Info

```
# dmidecode 3.4
Getting SMBIOS data from sysfs.
SMBIOS 3.0.0 present.

Handle 0x0001, DMI type 1, 27 bytes
System Information
	Manufacturer: Timi
	Product Name: TM1703
	Version: XMAKB3M0P1B13
	Serial Number: 17247/00076192
	UUID: 86d60185-9b9c-11e8-dbf1-390d24355a95
	Wake-up Type: Power Switch
	SKU Number: TM1703-17247
	Family: Timibook

Handle 0x000A, DMI type 12, 5 bytes
System Configuration Options
	Option 1: ConfigOptions1
	Option 2: ConfigOptions2
	Option 3: ConfigOptions3

```


# CPU

```
Architecture:                            x86_64
CPU op-mode(s):                          32-bit, 64-bit
Address sizes:                           39 bits physical, 48 bits virtual
Byte Order:                              Little Endian
CPU(s):                                  8
On-line CPU(s) list:                     0-7
Vendor ID:                               GenuineIntel
BIOS Vendor ID:                          Intel(R) Corporation
Model name:                              Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
BIOS Model name:                         Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz To Be Filled By O.E.M. CPU @ 1.5GHz
BIOS CPU family:                         205
CPU family:                              6
Model:                                   142
Thread(s) per core:                      2
Core(s) per socket:                      4
Socket(s):                               1
Stepping:                                10
CPU(s) scaling MHz:                      25%
CPU max MHz:                             3400.0000
CPU min MHz:                             400.0000
BogoMIPS:                                3600.00
Flags:                                   fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb pti ssbd ibrs ibpb stibp tpr_shadow flexpriority ept vpid ept_ad fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp vnmi md_clear flush_l1d arch_capabilities
Virtualization:                          VT-x
L1d cache:                               128 KiB (4 instances)
L1i cache:                               128 KiB (4 instances)
L2 cache:                                1 MiB (4 instances)
L3 cache:                                6 MiB (1 instance)
NUMA node(s):                            1
NUMA node0 CPU(s):                       0-7
Vulnerability Gather data sampling:      Mitigation; Microcode
Vulnerability Indirect target selection: Not affected
Vulnerability Itlb multihit:             KVM: Mitigation: Split huge pages
Vulnerability L1tf:                      Mitigation; PTE Inversion; VMX conditional cache flushes, SMT vulnerable
Vulnerability Mds:                       Mitigation; Clear CPU buffers; SMT vulnerable
Vulnerability Meltdown:                  Mitigation; PTI
Vulnerability Mmio stale data:           Mitigation; Clear CPU buffers; SMT vulnerable
Vulnerability Reg file data sampling:    Not affected
Vulnerability Retbleed:                  Mitigation; IBRS
Vulnerability Spec rstack overflow:      Not affected
Vulnerability Spec store bypass:         Mitigation; Speculative Store Bypass disabled via prctl
Vulnerability Spectre v1:                Mitigation; usercopy/swapgs barriers and __user pointer sanitization
Vulnerability Spectre v2:                Mitigation; IBRS; IBPB conditional; STIBP conditional; RSB filling; PBRSB-eIBRS Not affected; BHI Not affected
Vulnerability Srbds:                     Mitigation; Microcode
Vulnerability Tsa:                       Not affected
Vulnerability Tsx async abort:           Not affected
```


# Memory

```
# dmidecode 3.4
Getting SMBIOS data from sysfs.
SMBIOS 3.0.0 present.

Handle 0x000E, DMI type 16, 23 bytes
Physical Memory Array
	Location: System Board Or Motherboard
	Use: System Memory
	Error Correction Type: None
	Maximum Capacity: 32 GB
	Error Information Handle: No Error
	Number Of Devices: 2

Handle 0x000F, DMI type 17, 40 bytes
Memory Device
	Array Handle: 0x000E
	Error Information Handle: No Error
	Total Width: 64 bits
	Data Width: 64 bits
	Size: 8 GB
	Form Factor: SODIMM
	Set: None
	Locator: ChannelA-DIMM0
	Bank Locator: BANK 0
	Type: DDR4
	Type Detail: Synchronous Unbuffered (Unregistered)
	Speed: 2400 MT/s
	Manufacturer: Samsung
	Serial Number: 00000000
	Asset Tag: 9876543210
	Part Number: M471A1K43BB1-CRC    
	Rank: 1
	Configured Memory Speed: 2400 MT/s
	Minimum Voltage: 1.5 V
	Maximum Voltage: 1.5 V
	Configured Voltage: 1.2 V

Handle 0x0010, DMI type 17, 40 bytes
Memory Device
	Array Handle: 0x000E
	Error Information Handle: No Error
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: Unknown
	Set: None
	Locator: ChannelB-DIMM0
	Bank Locator: BANK 2
	Type: Unknown
	Type Detail: None

```


# PCI Devices

```
00:00.0 Host bridge [0600]: Intel Corporation Xeon E3-1200 v6/7th Gen Core Processor Host Bridge/DRAM Registers [8086:5914] (rev 08)
00:02.0 VGA compatible controller [0300]: Intel Corporation UHD Graphics 620 [8086:5917] (rev 07)
00:14.0 USB controller [0c03]: Intel Corporation Sunrise Point-LP USB 3.0 xHCI Controller [8086:9d2f] (rev 21)
00:15.0 Signal processing controller [1180]: Intel Corporation Sunrise Point-LP Serial IO I2C Controller #0 [8086:9d60] (rev 21)
00:15.1 Signal processing controller [1180]: Intel Corporation Sunrise Point-LP Serial IO I2C Controller #1 [8086:9d61] (rev 21)
00:16.0 Communication controller [0780]: Intel Corporation Sunrise Point-LP CSME HECI #1 [8086:9d3a] (rev 21)
00:17.0 SATA controller [0106]: Intel Corporation Sunrise Point-LP SATA Controller [AHCI mode] [8086:9d03] (rev 21)
00:1c.0 PCI bridge [0604]: Intel Corporation Sunrise Point-LP PCI Express Root Port #1 [8086:9d10] (rev f1)
00:1c.4 PCI bridge [0604]: Intel Corporation Sunrise Point-LP PCI Express Root Port #5 [8086:9d14] (rev f1)
00:1d.0 PCI bridge [0604]: Intel Corporation Sunrise Point-LP PCI Express Root Port #9 [8086:9d18] (rev f1)
00:1f.0 ISA bridge [0601]: Intel Corporation Sunrise Point LPC Controller/eSPI Controller [8086:9d4e] (rev 21)
00:1f.2 Memory controller [0580]: Intel Corporation Sunrise Point-LP PMC [8086:9d21] (rev 21)
00:1f.3 Audio device [0403]: Intel Corporation Sunrise Point-LP HD Audio [8086:9d71] (rev 21)
00:1f.4 SMBus [0c05]: Intel Corporation Sunrise Point-LP SMBus [8086:9d23] (rev 21)
01:00.0 3D controller [0302]: NVIDIA Corporation GP108M [GeForce MX150] [10de:1d12] (rev a1)
02:00.0 Network controller [0280]: Intel Corporation Wireless 8265 / 8275 [8086:24fd] (rev 78)
03:00.0 Non-Volatile memory controller [0108]: Samsung Electronics Co Ltd NVMe SSD Controller SM981/PM981/PM983 [144d:a808]
```


# USB Devices

```
/:  Bus 02.Port 1: Dev 1, Class=root_hub, Driver=xhci_hcd/6p, 5000M
/:  Bus 01.Port 1: Dev 1, Class=root_hub, Driver=xhci_hcd/12p, 480M
    |__ Port 3: Dev 9, If 0, Class=Hub, Driver=hub/4p, 480M
        |__ Port 4: Dev 11, If 0, Class=Mass Storage, Driver=usb-storage, 480M
        |__ Port 3: Dev 10, If 0, Class=Hub, Driver=hub/4p, 480M
            |__ Port 3: Dev 12, If 0, Class=Vendor Specific Class, Driver=r8152, 480M
    |__ Port 5: Dev 3, If 1, Class=Video, Driver=uvcvideo, 480M
    |__ Port 5: Dev 3, If 0, Class=Video, Driver=uvcvideo, 480M
    |__ Port 6: Dev 4, If 0, Class=Vendor Specific Class, Driver=, 12M
    |__ Port 7: Dev 5, If 0, Class=Wireless, Driver=btusb, 12M
    |__ Port 7: Dev 5, If 1, Class=Wireless, Driver=btusb, 12M
```


# USB List

```
Bus 002 Device 001: ID 1d6b:0003 Linux Foundation 3.0 root hub
Bus 001 Device 005: ID 8087:0a2b Intel Corp. Bluetooth wireless interface
Bus 001 Device 004: ID 04f3:0c1a Elan Microelectronics Corp. ELAN:Fingerprint
Bus 001 Device 003: ID 05c8:03a2 Cheng Uei Precision Industry Co., Ltd (Foxlink) XiaoMi USB 2.0 Webcam
Bus 001 Device 011: ID 05e3:0751 Genesys Logic, Inc. microSD Card Reader
Bus 001 Device 012: ID 0bda:8152 Realtek Semiconductor Corp. RTL8152 Fast Ethernet Adapter
Bus 001 Device 010: ID 1a86:8095 QinHeng Electronics USB Hub
Bus 001 Device 009: ID 1a86:8095 QinHeng Electronics USB Hub
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
```


# Network Info

```
GENERAL.DEVICE:                         enx00e04c3601cb
GENERAL.TYPE:                           ethernet
GENERAL.HWADDR:                         00:E0:4C:36:01:CB
GENERAL.MTU:                            1500
GENERAL.STATE:                          100 (connected)
GENERAL.CONNECTION:                     Wired connection 1
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/10
WIRED-PROPERTIES.CARRIER:               on
IP4.ADDRESS[1]:                         192.168.31.79/24
IP4.GATEWAY:                            192.168.31.1
IP4.ROUTE[1]:                           dst = 192.168.31.0/24, nh = 0.0.0.0, mt = 100
IP4.ROUTE[2]:                           dst = 0.0.0.0/0, nh = 192.168.31.1, mt = 100
IP4.ROUTE[3]:                           dst = 169.254.0.0/16, nh = 0.0.0.0, mt = 1000
IP4.DNS[1]:                             192.168.31.1
IP6.ADDRESS[1]:                         fe80::1ba:b0a8:7f1:94d6/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 1024

GENERAL.DEVICE:                         tailscale0
GENERAL.TYPE:                           tun
GENERAL.HWADDR:                         (unknown)
GENERAL.MTU:                            1280
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     tailscale0
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/3
IP4.ADDRESS[1]:                         100.111.241.106/32
IP4.GATEWAY:                            --
IP4.ROUTE[1]:                           dst = 100.115.138.56/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[2]:                           dst = 100.100.100.100/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[3]:                           dst = 100.66.124.80/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[4]:                           dst = 100.78.90.49/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[5]:                           dst = 100.95.197.3/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[6]:                           dst = 100.72.58.18/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[7]:                           dst = 100.78.142.88/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[8]:                           dst = 100.93.78.24/32, nh = 0.0.0.0, mt = 0, table=52
IP6.ADDRESS[1]:                         fd7a:115c:a1e0::4501:f177/128
IP6.ADDRESS[2]:                         fe80::da6:d6f1:f11a:3f6f/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 256
IP6.ROUTE[2]:                           dst = fd7a:115c:a1e0::/48, nh = ::, mt = 1024, table=52
IP6.ROUTE[3]:                           dst = fd7a:115c:a1e0::53/128, nh = ::, mt = 1024, table=52
IP6.ROUTE[4]:                           dst = fd7a:115c:a1e0::4501:f177/128, nh = ::, mt = 256

GENERAL.DEVICE:                         cni0
GENERAL.TYPE:                           bridge
GENERAL.HWADDR:                         0A:F5:42:5B:7F:6F
GENERAL.MTU:                            1450
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     cni0
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/8
IP4.ADDRESS[1]:                         10.42.2.1/24
IP4.GATEWAY:                            --
IP4.ROUTE[1]:                           dst = 10.42.2.0/24, nh = 0.0.0.0, mt = 0
IP6.ADDRESS[1]:                         fe80::8f5:42ff:fe5b:7f6f/64
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
GENERAL.HWADDR:                         6E:34:D3:A4:5D:71
GENERAL.MTU:                            2800
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     ztks5shfaa
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/5
IP4.ADDRESS[1]:                         10.147.19.132/24
IP4.GATEWAY:                            --
IP4.ROUTE[1]:                           dst = 10.147.19.0/24, nh = 0.0.0.0, mt = 0
IP6.ADDRESS[1]:                         fe80::6c34:d3ff:fea4:5d71/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 256

GENERAL.DEVICE:                         wlp2s0
GENERAL.TYPE:                           wifi
GENERAL.HWADDR:                         C0:B6:F9:5F:4C:E5
GENERAL.MTU:                            1500
GENERAL.STATE:                          100 (connected)
GENERAL.CONNECTION:                     FatDog
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/11
IP4.ADDRESS[1]:                         192.168.31.174/24
IP4.GATEWAY:                            192.168.31.1
IP4.ROUTE[1]:                           dst = 192.168.31.0/24, nh = 0.0.0.0, mt = 600
IP4.ROUTE[2]:                           dst = 0.0.0.0/0, nh = 192.168.31.1, mt = 600
IP4.DNS[1]:                             192.168.31.1
IP6.ADDRESS[1]:                         fe80::c2b6:f9ff:fe5f:4ce5/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 1024

GENERAL.DEVICE:                         docker0
GENERAL.TYPE:                           bridge
GENERAL.HWADDR:                         02:42:E8:11:22:14
GENERAL.MTU:                            1500
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     docker0
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/6
IP4.ADDRESS[1]:                         172.17.0.1/16
IP4.GATEWAY:                            --
IP4.ROUTE[1]:                           dst = 172.17.0.0/16, nh = 0.0.0.0, mt = 0
IP6.GATEWAY:                            --

GENERAL.DEVICE:                         p2p-dev-wlp2s0
GENERAL.TYPE:                           wifi-p2p
GENERAL.HWADDR:                         (unknown)
GENERAL.MTU:                            0
GENERAL.STATE:                          30 (disconnected)
GENERAL.CONNECTION:                     --
GENERAL.CON-PATH:                       --

GENERAL.DEVICE:                         veth7bcb5581
GENERAL.TYPE:                           ethernet
GENERAL.HWADDR:                         42:73:0A:AC:FC:6E
GENERAL.MTU:                            1450
GENERAL.STATE:                          10 (unmanaged)
GENERAL.CONNECTION:                     --
GENERAL.CON-PATH:                       --
WIRED-PROPERTIES.CARRIER:               on
IP4.GATEWAY:                            --
IP6.ADDRESS[1]:                         fe80::4073:aff:feac:fc6e/64
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
3: wlp2s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default qlen 1000
    link/ether c0:b6:f9:5f:4c:e5 brd ff:ff:ff:ff:ff:ff
    inet 192.168.31.174/24 brd 192.168.31.255 scope global dynamic noprefixroute wlp2s0
       valid_lft 37082sec preferred_lft 37082sec
    inet6 fe80::c2b6:f9ff:fe5f:4ce5/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
4: tailscale0: <POINTOPOINT,MULTICAST,NOARP,UP,LOWER_UP> mtu 1280 qdisc fq_codel state UNKNOWN group default qlen 500
    link/none 
    inet 100.111.241.106/32 scope global tailscale0
       valid_lft forever preferred_lft forever
    inet6 fd7a:115c:a1e0::4501:f177/128 scope global 
       valid_lft forever preferred_lft forever
    inet6 fe80::da6:d6f1:f11a:3f6f/64 scope link stable-privacy 
       valid_lft forever preferred_lft forever
5: ztks5shfaa: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 2800 qdisc fq_codel state UNKNOWN group default qlen 1000
    link/ether 6e:34:d3:a4:5d:71 brd ff:ff:ff:ff:ff:ff
    inet 10.147.19.132/24 brd 10.147.19.255 scope global ztks5shfaa
       valid_lft forever preferred_lft forever
    inet6 fe80::6c34:d3ff:fea4:5d71/64 scope link 
       valid_lft forever preferred_lft forever
6: docker0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN group default 
    link/ether 02:42:e8:11:22:14 brd ff:ff:ff:ff:ff:ff
    inet 172.17.0.1/16 brd 172.17.255.255 scope global docker0
       valid_lft forever preferred_lft forever
8: cni0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1450 qdisc noqueue state UP group default qlen 1000
    link/ether 0a:f5:42:5b:7f:6f brd ff:ff:ff:ff:ff:ff
    inet 10.42.2.1/24 brd 10.42.2.255 scope global cni0
       valid_lft forever preferred_lft forever
    inet6 fe80::8f5:42ff:fe5b:7f6f/64 scope link 
       valid_lft forever preferred_lft forever
9: veth7bcb5581@if2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1450 qdisc noqueue master cni0 state UP group default qlen 1000
    link/ether 42:73:0a:ac:fc:6e brd ff:ff:ff:ff:ff:ff link-netns cni-c07cab33-c170-39eb-d79e-1d0448dcd3ce
    inet6 fe80::4073:aff:feac:fc6e/64 scope link 
       valid_lft forever preferred_lft forever
10: enx00e04c3601cb: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 00:e0:4c:36:01:cb brd ff:ff:ff:ff:ff:ff
    inet 192.168.31.79/24 brd 192.168.31.255 scope global dynamic noprefixroute enx00e04c3601cb
       valid_lft 37078sec preferred_lft 37078sec
    inet6 fe80::1ba:b0a8:7f1:94d6/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
```


# Sensors

```
coretemp-isa-0000
Adapter: ISA adapter
Package id 0:  +46.0°C  (high = +100.0°C, crit = +100.0°C)
Core 0:        +44.0°C  (high = +100.0°C, crit = +100.0°C)
Core 1:        +44.0°C  (high = +100.0°C, crit = +100.0°C)
Core 2:        +45.0°C  (high = +100.0°C, crit = +100.0°C)
Core 3:        +46.0°C  (high = +100.0°C, crit = +100.0°C)

ucsi_source_psy_USBC000:001-isa-0000
Adapter: ISA adapter
in0:           0.00 V  (min =  +0.00 V, max =  +0.00 V)
curr1:         3.00 A  (max =  +0.00 A)

nvme-pci-0300
Adapter: PCI adapter
Composite:    +34.9°C  (low  = -273.1°C, high = +80.8°C)
                       (crit = +81.8°C)
Sensor 1:     +34.9°C  (low  = -273.1°C, high = +65261.8°C)
Sensor 2:     +44.9°C  (low  = -273.1°C, high = +65261.8°C)

acpitz-acpi-0
Adapter: ACPI interface
temp1:        +45.0°C  
temp2:        +36.0°C  

iwlwifi_1-virtual-0
Adapter: Virtual device
temp1:        +33.0°C  

BAT0-acpi-0
Adapter: ACPI interface
in0:           8.72 V  
curr1:         0.00 A  

```


# Storage (lsblk)

```
NAME          SIZE TYPE MOUNTPOINT                   FSTYPE   MODEL
loop0           4K loop /snap/bare/5                 squashfs 
loop1       104.2M loop /snap/core/17247             squashfs 
loop2        73.9M loop /snap/core22/2139            squashfs 
loop3          74M loop /snap/core22/2163            squashfs 
loop4       104.2M loop /snap/core/17212             squashfs 
loop5        66.8M loop /snap/core24/1196            squashfs 
loop6       516.2M loop /snap/gnome-42-2204/226      squashfs 
loop7       589.6M loop /snap/gnome-46-2404/117      squashfs 
loop8        66.8M loop /snap/core24/1225            squashfs 
loop9       618.3M loop /snap/gnome-46-2404/125      squashfs 
loop10      141.3M loop /snap/mc-installer/638       squashfs 
loop11       91.7M loop /snap/gtk-common-themes/1535 squashfs 
loop12        516M loop /snap/gnome-42-2204/202      squashfs 
loop13        395M loop /snap/mesa-2404/1165         squashfs 
loop14      290.8M loop /snap/mesa-2404/912          squashfs 
loop15       10.8M loop /snap/snap-store/1270        squashfs 
loop16      295.2M loop /snap/wekan/3181             squashfs 
loop17      295.6M loop /snap/wekan/3183             squashfs 
loop18       50.9M loop /snap/snapd/25577            squashfs 
loop19       50.8M loop /snap/snapd/25202            squashfs 
sda             0B disk                                       STORAGE DEVICE
zram0         256M disk [SWAP]                                
nvme0n1     238.5G disk                                       SAMSUNG MZVLB256HAHQ-00000
├─nvme0n1p1   512M part /boot/efi                    vfat     
├─nvme0n1p2   237G part /                            ext4     
└─nvme0n1p3   977M part [SWAP]                       swap     
```


# SMART: /dev/loop0

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop0: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop1

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop1: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop2

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop2: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop3

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop3: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop4

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop4: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop5

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop5: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop6

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop6: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop7

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop7: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop8

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop8: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop9

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop9: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop10

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop10: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop11

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop11: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop12

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop12: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop13

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop13: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop14

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop14: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop15

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop15: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop16

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop16: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop17

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop17: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop18

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop18: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/loop19

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/loop19: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/sda

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/sda: Unknown USB bridge [0x05e3:0x0751 (0x1404)]
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/zram0

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

/dev/zram0: Unable to detect device type
Please specify device type with the -d option.

Use smartctl -h to get a usage summary

```


# SMART: /dev/nvme0n1

```
smartctl 7.3 2022-02-28 r5338 [x86_64-linux-6.12.43+deb12-amd64] (local build)
Copyright (C) 2002-22, Bruce Allen, Christian Franke, www.smartmontools.org

=== START OF INFORMATION SECTION ===
Model Number:                       SAMSUNG MZVLB256HAHQ-00000
Serial Number:                      S444NY0K516069
Firmware Version:                   EXD7101Q
PCI Vendor/Subsystem ID:            0x144d
IEEE OUI Identifier:                0x002538
Total NVM Capacity:                 256,060,514,304 [256 GB]
Unallocated NVM Capacity:           0
Controller ID:                      4
NVMe Version:                       1.2
Number of Namespaces:               1
Namespace 1 Size/Capacity:          256,060,514,304 [256 GB]
Namespace 1 Utilization:            193,285,476,352 [193 GB]
Namespace 1 Formatted LBA Size:     512
Namespace 1 IEEE EUI-64:            002538 85810041de
Local Time is:                      Fri Nov 21 21:25:27 2025 MSK
Firmware Updates (0x16):            3 Slots, no Reset required
Optional Admin Commands (0x0017):   Security Format Frmw_DL Self_Test
Optional NVM Commands (0x001f):     Comp Wr_Unc DS_Mngmt Wr_Zero Sav/Sel_Feat
Log Page Attributes (0x03):         S/H_per_NS Cmd_Eff_Lg
Maximum Data Transfer Size:         512 Pages
Warning  Comp. Temp. Threshold:     81 Celsius
Critical Comp. Temp. Threshold:     82 Celsius

Supported Power States
St Op     Max   Active     Idle   RL RT WL WT  Ent_Lat  Ex_Lat
 0 +     7.02W       -        -    0  0  0  0        0       0
 1 +     6.30W       -        -    1  1  1  1        0       0
 2 +     3.50W       -        -    2  2  2  2        0       0
 3 -   0.0760W       -        -    3  3  3  3      210    1200
 4 -   0.0050W       -        -    4  4  4  4     2000    8000

Supported LBA Sizes (NSID 0x1)
Id Fmt  Data  Metadt  Rel_Perf
 0 +     512       0         0

=== START OF SMART DATA SECTION ===
SMART overall-health self-assessment test result: PASSED

SMART/Health Information (NVMe Log 0x02)
Critical Warning:                   0x00
Temperature:                        35 Celsius
Available Spare:                    100%
Available Spare Threshold:          10%
Percentage Used:                    11%
Data Units Read:                    56,880,214 [29.1 TB]
Data Units Written:                 49,364,872 [25.2 TB]
Host Read Commands:                 758,045,723
Host Write Commands:                540,413,317
Controller Busy Time:               3,277
Power Cycles:                       6,791
Power On Hours:                     3,659
Unsafe Shutdowns:                   180
Media and Data Integrity Errors:    0
Error Information Log Entries:      5,003
Warning  Comp. Temperature Time:    0
Critical Comp. Temperature Time:    0
Temperature Sensor 1:               35 Celsius
Temperature Sensor 2:               45 Celsius

Error Information (NVMe Log 0x01, 16 of 64 entries)
No Errors Logged

```


# Display EDID

```
```


# DMIDecode (full)

```
# dmidecode 3.4
Getting SMBIOS data from sysfs.
SMBIOS 3.0.0 present.
Table at 0x8C10F000.

Handle 0x0000, DMI type 0, 24 bytes
BIOS Information
	Vendor: Insyde Corp.
	Version: XMAKB3M0P1B13
	Release Date: 08/05/2021
	Address: 0xE0000
	Runtime Size: 128 kB
	ROM Size: 8 MB
	Characteristics:
		PCI is supported
		BIOS is upgradeable
		BIOS shadowing is allowed
		Boot from CD is supported
		Selectable boot is supported
		EDD is supported
		8042 keyboard services are supported (int 9h)
		CGA/mono video services are supported (int 10h)
		ACPI is supported
		USB legacy is supported
		BIOS boot specification is supported
		Targeted content distribution is supported
		UEFI is supported
	BIOS Revision: 1.27
	Firmware Revision: 1.19

Handle 0x0001, DMI type 1, 27 bytes
System Information
	Manufacturer: Timi
	Product Name: TM1703
	Version: XMAKB3M0P1B13
	Serial Number: 17247/00076192
	UUID: 86d60185-9b9c-11e8-dbf1-390d24355a95
	Wake-up Type: Power Switch
	SKU Number: TM1703-17247
	Family: Timibook

Handle 0x0002, DMI type 2, 17 bytes
Base Board Information
	Manufacturer: Timi
	Product Name: TM1703
	Version: XMAKB3M0P1B13
	Serial Number: 1234567890123456789012
	Asset Tag: No Asset Tag
	Features:
		Board is a hosting board
		Board is replaceable
	Location In Chassis: Type2 - Board Chassis Location  
	Chassis Handle: 0x0003
	Type: Motherboard
	Contained Object Handles: 0

Handle 0x0003, DMI type 3, 22 bytes
Chassis Information
	Manufacturer: Timi
	Type: Notebook
	Lock: Not Present
	Version: XMAKB3M0P1B13
	Serial Number: 17247/00076192
	Asset Tag: No Asset Tag
	Boot-up State: Safe
	Power Supply State: Safe
	Thermal State: Safe
	Security Status: None
	OEM Information: 0x00000000
	Height: Unspecified
	Number Of Power Cords: 1
	Contained Elements: 0
	SKU Number: TM1703-17247

Handle 0x0004, DMI type 4, 48 bytes
Processor Information
	Socket Designation: U3E1
	Type: Central Processor
	Family: Core i5
	Manufacturer: Intel(R) Corporation
	ID: EA 06 08 00 FF FB EB BF
	Signature: Type 0, Family 6, Model 142, Stepping 10
	Flags:
		FPU (Floating-point unit on-chip)
		VME (Virtual mode extension)
		DE (Debugging extension)
		PSE (Page size extension)
		TSC (Time stamp counter)
		MSR (Model specific registers)
		PAE (Physical address extension)
		MCE (Machine check exception)
		CX8 (CMPXCHG8 instruction supported)
		APIC (On-chip APIC hardware supported)
		SEP (Fast system call)
		MTRR (Memory type range registers)
		PGE (Page global enable)
		MCA (Machine check architecture)
		CMOV (Conditional move instruction supported)
		PAT (Page attribute table)
		PSE-36 (36-bit page size extension)
		CLFSH (CLFLUSH instruction supported)
		DS (Debug store)
		ACPI (ACPI supported)
		MMX (MMX technology supported)
		FXSR (FXSAVE and FXSTOR instructions supported)
		SSE (Streaming SIMD extensions)
		SSE2 (Streaming SIMD extensions 2)
		SS (Self-snoop)
		HTT (Multi-threading)
		TM (Thermal monitor supported)
		PBE (Pending break enabled)
	Version: Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
	Voltage: 0.7 V
	External Clock: 100 MHz
	Max Speed: 8300 MHz
	Current Speed: 1500 MHz
	Status: Populated, Enabled
	Upgrade: Socket BGA1356
	L1 Cache Handle: 0x0005
	L2 Cache Handle: 0x0006
	L3 Cache Handle: 0x0007
	Serial Number: To Be Filled By O.E.M.
	Asset Tag: To Be Filled By O.E.M.
	Part Number: To Be Filled By O.E.M.
	Core Count: 4
	Core Enabled: 4
	Thread Count: 8
	Characteristics:
		64-bit capable
		Multi-Core
		Hardware Thread
		Execute Protection
		Enhanced Virtualization
		Power/Performance Control

Handle 0x0005, DMI type 7, 19 bytes
Cache Information
	Socket Designation: L1 Cache
	Configuration: Enabled, Not Socketed, Level 1
	Operational Mode: Write Back
	Location: Internal
	Installed Size: 256 kB
	Maximum Size: 256 kB
	Supported SRAM Types:
		Synchronous
	Installed SRAM Type: Synchronous
	Speed: Unknown
	Error Correction Type: Parity
	System Type: Unified
	Associativity: 8-way Set-associative

Handle 0x0006, DMI type 7, 19 bytes
Cache Information
	Socket Designation: L2 Cache
	Configuration: Enabled, Not Socketed, Level 2
	Operational Mode: Write Back
	Location: Internal
	Installed Size: 1 MB
	Maximum Size: 1 MB
	Supported SRAM Types:
		Synchronous
	Installed SRAM Type: Synchronous
	Speed: Unknown
	Error Correction Type: Single-bit ECC
	System Type: Unified
	Associativity: 4-way Set-associative

Handle 0x0007, DMI type 7, 19 bytes
Cache Information
	Socket Designation: L3 Cache
	Configuration: Enabled, Not Socketed, Level 3
	Operational Mode: Write Back
	Location: Internal
	Installed Size: 6 MB
	Maximum Size: 6 MB
	Supported SRAM Types:
		Synchronous
	Installed SRAM Type: Synchronous
	Speed: Unknown
	Error Correction Type: Multi-bit ECC
	System Type: Unified
	Associativity: 12-way Set-associative

Handle 0x0008, DMI type 10, 6 bytes
On Board Device Information
	Type: Video
	Status: Enabled
	Description: Video Graphics Controller

Handle 0x0009, DMI type 11, 5 bytes
OEM Strings
	String 1: OemString1

Handle 0x000A, DMI type 12, 5 bytes
System Configuration Options
	Option 1: ConfigOptions1
	Option 2: ConfigOptions2
	Option 3: ConfigOptions3

Handle 0x000B, DMI type 14, 8 bytes
Group Associations
	Name: Intel(R) Silicon View Technology
	Items: 1
		0x001A (OEM-specific)

Handle 0x000C, DMI type 14, 8 bytes
Group Associations
	Name: $MEI
	Items: 1
		0x0015 (OEM-specific)

Handle 0x000D, DMI type 14, 8 bytes
Group Associations
	Name: $MEI
	Items: 1
		0x0014 (OEM-specific)

Handle 0x000E, DMI type 16, 23 bytes
Physical Memory Array
	Location: System Board Or Motherboard
	Use: System Memory
	Error Correction Type: None
	Maximum Capacity: 32 GB
	Error Information Handle: No Error
	Number Of Devices: 2

Handle 0x000F, DMI type 17, 40 bytes
Memory Device
	Array Handle: 0x000E
	Error Information Handle: No Error
	Total Width: 64 bits
	Data Width: 64 bits
	Size: 8 GB
	Form Factor: SODIMM
	Set: None
	Locator: ChannelA-DIMM0
	Bank Locator: BANK 0
	Type: DDR4
	Type Detail: Synchronous Unbuffered (Unregistered)
	Speed: 2400 MT/s
	Manufacturer: Samsung
	Serial Number: 00000000
	Asset Tag: 9876543210
	Part Number: M471A1K43BB1-CRC    
	Rank: 1
	Configured Memory Speed: 2400 MT/s
	Minimum Voltage: 1.5 V
	Maximum Voltage: 1.5 V
	Configured Voltage: 1.2 V

Handle 0x0010, DMI type 17, 40 bytes
Memory Device
	Array Handle: 0x000E
	Error Information Handle: No Error
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: Unknown
	Set: None
	Locator: ChannelB-DIMM0
	Bank Locator: BANK 2
	Type: Unknown
	Type Detail: None

Handle 0x0011, DMI type 19, 31 bytes
Memory Array Mapped Address
	Starting Address: 0x00000000000
	Ending Address: 0x001FFFFFFFF
	Range Size: 8 GB
	Physical Array Handle: 0x000E
	Partition Width: 1

Handle 0x0012, DMI type 20, 35 bytes
Memory Device Mapped Address
	Starting Address: 0x00000000000
	Ending Address: 0x3FFFFFFFFFF
	Range Size: Invalid
	Physical Device Handle: 0x000F
	Memory Array Mapped Address Handle: 0x0011
	Partition Row Position: Unknown
	Interleave Position: 1
	Interleaved Data Depth: 1

Handle 0x0013, DMI type 20, 35 bytes
Memory Device Mapped Address
	Starting Address: 0x00000000000
	Ending Address: 0x3FFFFFFFFFF
	Range Size: Invalid
	Physical Device Handle: 0x0010
	Memory Array Mapped Address Handle: 0x0011
	Partition Row Position: Unknown
	Interleave Position: 2
	Interleaved Data Depth: 1

Handle 0x0014, DMI type 219, 81 bytes
OEM-specific Type
	Header and Data:
		DB 51 14 00 01 03 01 55 02 00 90 06 01 10 81 20
		00 00 00 04 40 08 00 00 00 00 00 00 00 00 00 02
		FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF
		FF FF FF FF FF FF FF FF 03 00 00 00 80 00 00 00
		00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
		00
	Strings:
		MEI1
		MEI2
		MEI3

Handle 0x0015, DMI type 221, 26 bytes
OEM-specific Type
	Header and Data:
		DD 1A 15 00 03 01 00 02 07 00 00 00 02 00 00 00
		00 96 00 03 00 00 05 00 00 00
	Strings:
		Reference Code - CPU
		uCode Version
		TXT ACM version

Handle 0x0016, DMI type 221, 26 bytes
OEM-specific Type
	Header and Data:
		DD 1A 16 00 03 01 00 02 07 00 00 00 02 00 00 00
		00 00 00 03 04 0B 08 32 62 0D
	Strings:
		Reference Code - ME 11.0
		MEBx version
		ME Firmware Version
		Consumer SKU

Handle 0x0017, DMI type 221, 75 bytes
OEM-specific Type
	Header and Data:
		DD 4B 17 00 0A 01 00 02 07 00 00 00 02 03 FF FF
		FF FF FF 04 00 FF FF FF 21 00 05 00 FF FF FF 21
		00 06 00 FF FF FF FF FF 07 00 3E 00 00 00 00 08
		00 34 00 00 00 00 09 00 0B 00 00 00 00 0A 00 3E
		00 00 00 00 0B 00 34 00 00 00 00
	Strings:
		Reference Code - SKL PCH
		PCH-CRID Status
		Disabled
		PCH-CRID Original Value
		PCH-CRID New Value
		OPROM - RST - RAID
		SKL PCH H Bx Hsio Version
		SKL PCH H Dx Hsio Version
		KBL PCH H Ax Hsio Version
		SKL PCH LP Bx Hsio Version
		SKL PCH LP Cx Hsio Version

Handle 0x0018, DMI type 221, 54 bytes
OEM-specific Type
	Header and Data:
		DD 36 18 00 07 01 00 02 07 00 00 00 02 00 02 07
		00 00 00 03 00 02 07 00 00 00 04 05 FF FF FF FF
		FF 06 00 FF FF FF 08 00 07 00 FF FF FF 08 00 08
		00 FF FF FF FF FF
	Strings:
		Reference Code - SA - System Agent
		Reference Code - MRC
		SA - PCIe Version
		SA-CRID Status
		Disabled
		SA-CRID Original Value
		SA-CRID New Value
		OPROM - VBIOS

Handle 0x0019, DMI type 221, 103 bytes
OEM-specific Type
	Header and Data:
		DD 67 19 00 0E 01 00 00 00 00 FF 00 02 00 FF FF
		FF FF FF 03 04 FF FF FF FF FF 05 06 FF FF FF FF
		FF 07 08 FF FF FF FF FF 09 00 00 00 00 00 00 0A
		00 FF FF FF FF FF 0B 00 01 13 00 00 00 0C 00 00
		09 00 74 10 0D 00 FF FF FF FF FF 0E 00 FF FF FF
		FF FF 0F 00 FF FF FF FF FF 10 11 01 03 04 01 00
		12 00 00 07 03 00 00
	Strings:
		Lan Phy Version
		Sensor Firmware Version
		Debug Mode Status
		Disabled
		Performance Mode Status
		Disabled
		Debug Use USB(Disabled:Serial)
		Disabled
		ICC Overclocking Version
		UNDI Version
		EC FW Version
		GOP Version
		BIOS Guard Version
		Base EC FW Version
		EC-EC Protocol Version
		Royal Park Version
		BP1.3.4.0_RP01
		Platform Version

Handle 0x001A, DMI type 222, 14 bytes
OEM-specific Type
	Header and Data:
		DE 0E 1A 00 01 99 00 03 10 01 20 02 30 03
	Strings:
		Memory Init Complete
		End of DXE Phase
		BIOS Boot Complete

Handle 0xFEFF, DMI type 127, 4 bytes
End Of Table

```


# LSHW (full)

```
debian
    description: Notebook
    product: TM1703 (TM1703-17247)
    vendor: Timi
    version: XMAKB3M0P1B13
    serial: 17247/00076192
    width: 64 bits
    capabilities: smbios-3.0.0 dmi-3.0.0 smp vsyscall32
    configuration: chassis=notebook family=Timibook sku=TM1703-17247 uuid=86d60185-9b9c-11e8-dbf1-390d24355a95
  *-core
       description: Motherboard
       product: TM1703
       vendor: Timi
       physical id: 0
       version: XMAKB3M0P1B13
       serial: 1234567890123456789012
       slot: Type2 - Board Chassis Location
     *-firmware
          description: BIOS
          vendor: Insyde Corp.
          physical id: 0
          version: XMAKB3M0P1B13
          date: 08/05/2021
          size: 128KiB
          capacity: 8MiB
          capabilities: pci upgrade shadowing cdboot bootselect edd int9keyboard int10video acpi usb biosbootspecification uefi
     *-cpu
          description: CPU
          product: Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz
          vendor: Intel Corp.
          physical id: 4
          bus info: cpu@0
          version: 6.142.10
          serial: To Be Filled By O.E.M.
          slot: U3E1
          size: 3400MHz
          capacity: 4005MHz
          width: 64 bits
          clock: 100MHz
          capabilities: lm fpu fpu_exception wp vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp x86-64 constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb pti ssbd ibrs ibpb stibp tpr_shadow flexpriority ept vpid ept_ad fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid mpx rdseed adx smap clflushopt intel_pt xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts hwp hwp_notify hwp_act_window hwp_epp vnmi md_clear flush_l1d arch_capabilities cpufreq
          configuration: cores=4 enabledcores=4 microcode=246 threads=8
        *-cache:0
             description: L1 cache
             physical id: 5
             slot: L1 Cache
             size: 256KiB
             capacity: 256KiB
             capabilities: synchronous internal write-back unified
             configuration: level=1
        *-cache:1
             description: L2 cache
             physical id: 6
             slot: L2 Cache
             size: 1MiB
             capacity: 1MiB
             capabilities: synchronous internal write-back unified
             configuration: level=2
        *-cache:2
             description: L3 cache
             physical id: 7
             slot: L3 Cache
             size: 6MiB
             capacity: 6MiB
             capabilities: synchronous internal write-back unified
             configuration: level=3
     *-memory
          description: System Memory
          physical id: e
          slot: System board or motherboard
          size: 8GiB
        *-bank:0
             description: SODIMM DDR4 Synchronous Unbuffered (Unregistered) 2400 MHz (0.4 ns)
             product: M471A1K43BB1-CRC
             vendor: Samsung
             physical id: 0
             serial: 00000000
             slot: ChannelA-DIMM0
             size: 8GiB
             width: 64 bits
             clock: 2400MHz (0.4ns)
        *-bank:1
             description: [empty]
             physical id: 1
             slot: ChannelB-DIMM0
     *-pci
          description: Host bridge
          product: Xeon E3-1200 v6/7th Gen Core Processor Host Bridge/DRAM Registers
          vendor: Intel Corporation
          physical id: 100
          bus info: pci@0000:00:00.0
          version: 08
          width: 32 bits
          clock: 33MHz
          configuration: driver=skl_uncore
          resources: irq:0
        *-display
             description: VGA compatible controller
             product: UHD Graphics 620
             vendor: Intel Corporation
             physical id: 2
             bus info: pci@0000:00:02.0
             logical name: /dev/fb0
             version: 07
             width: 64 bits
             clock: 33MHz
             capabilities: pciexpress msi pm vga_controller bus_master cap_list rom fb
             configuration: depth=32 driver=i915 latency=0 resolution=1920,1080
             resources: irq:143 memory:b2000000-b2ffffff memory:c0000000-cfffffff ioport:4000(size=64) memory:c0000-dffff
        *-usb
             description: USB controller
             product: Sunrise Point-LP USB 3.0 xHCI Controller
             vendor: Intel Corporation
             physical id: 14
             bus info: pci@0000:00:14.0
             version: 21
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi xhci bus_master cap_list
             configuration: driver=xhci_hcd latency=0
             resources: irq:125 memory:b4210000-b421ffff
           *-usbhost:0
                product: xHCI Host Controller
                vendor: Linux 6.12.43+deb12-amd64 xhci-hcd
                physical id: 0
                bus info: usb@1
                logical name: usb1
                version: 6.12
                capabilities: usb-2.00
                configuration: driver=hub slots=12 speed=480Mbit/s
              *-usb:0
                   description: USB hub
                   product: USB Hub
                   vendor: QinHeng Electronics
                   physical id: 3
                   bus info: usb@1:3
                   version: 12.10
                   capabilities: usb-2.00
                   configuration: driver=hub maxpower=100mA slots=4 speed=480Mbit/s
                 *-usb:0
                      description: USB hub
                      product: USB Hub
                      vendor: QinHeng Electronics
                      physical id: 3
                      bus info: usb@1:3.3
                      version: 12.10
                      capabilities: usb-2.00
                      configuration: driver=hub maxpower=100mA slots=4 speed=480Mbit/s
                    *-usb
                         description: Generic USB device
                         product: USB 10/100 LAN
                         vendor: Realtek
                         physical id: 3
                         bus info: usb@1:3.3.3
                         version: 20.00
                         serial: 00E04C3601CB
                         capabilities: usb-2.10
                         configuration: driver=r8152 maxpower=100mA speed=480Mbit/s
                 *-usb:1
                      description: Mass storage device
                      product: USB Storage
                      vendor: USB Storage
                      physical id: 4
                      bus info: usb@1:3.4
                      logical name: scsi2
                      version: 14.04
                      capabilities: usb-2.00 scsi emulated
                      configuration: driver=usb-storage maxpower=98mA speed=480Mbit/s
                    *-disk
                         description: SCSI Disk
                         product: STORAGE DEVICE
                         vendor: Generic
                         physical id: 0.0.0
                         bus info: scsi@2:0.0.0
                         logical name: /dev/sda
                         version: 1404
                         serial: [
                         capabilities: removable
                         configuration: ansiversion=6 logicalsectorsize=512 sectorsize=512
                       *-medium
                            physical id: 0
                            logical name: /dev/sda
              *-usb:1
                   description: Video
                   product: XiaoMi USB 2.0 Webcam
                   vendor: SunplusIT Inc
                   physical id: 5
                   bus info: usb@1:5
                   version: 1.03
                   capabilities: usb-2.00
                   configuration: driver=uvcvideo maxpower=500mA speed=480Mbit/s
              *-usb:2 UNCLAIMED
                   description: Generic USB device
                   product: ELAN:Fingerprint
                   vendor: ELAN
                   physical id: 6
                   bus info: usb@1:6
                   version: 1.42
                   capabilities: usb-2.00
                   configuration: maxpower=100mA speed=12Mbit/s
              *-usb:3
                   description: Bluetooth wireless interface
                   product: Bluetooth wireless interface
                   vendor: Intel Corp.
                   physical id: 7
                   bus info: usb@1:7
                   version: 0.10
                   capabilities: bluetooth usb-2.00
                   configuration: driver=btusb maxpower=100mA speed=12Mbit/s
           *-usbhost:1
                product: xHCI Host Controller
                vendor: Linux 6.12.43+deb12-amd64 xhci-hcd
                physical id: 1
                bus info: usb@2
                logical name: usb2
                version: 6.12
                capabilities: usb-3.00
                configuration: driver=hub slots=6 speed=5000Mbit/s
        *-generic:0
             description: Signal processing controller
             product: Sunrise Point-LP Serial IO I2C Controller #0
             vendor: Intel Corporation
             physical id: 15
             bus info: pci@0000:00:15.0
             version: 21
             width: 64 bits
             clock: 33MHz
             capabilities: pm bus_master cap_list
             configuration: driver=intel-lpss latency=0
             resources: irq:16 memory:b422a000-b422afff
        *-generic:1
             description: Signal processing controller
             product: Sunrise Point-LP Serial IO I2C Controller #1
             vendor: Intel Corporation
             physical id: 15.1
             bus info: pci@0000:00:15.1
             version: 21
             width: 64 bits
             clock: 33MHz
             capabilities: pm bus_master cap_list
             configuration: driver=intel-lpss latency=0
             resources: irq:17 memory:b422b000-b422bfff
        *-communication
             description: Communication controller
             product: Sunrise Point-LP CSME HECI #1
             vendor: Intel Corporation
             physical id: 16
             bus info: pci@0000:00:16.0
             version: 21
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi bus_master cap_list
             configuration: driver=mei_me latency=0
             resources: irq:133 memory:b422c000-b422cfff
        *-sata
             description: SATA controller
             product: Sunrise Point-LP SATA Controller [AHCI mode]
             vendor: Intel Corporation
             physical id: 17
             bus info: pci@0000:00:17.0
             version: 21
             width: 32 bits
             clock: 66MHz
             capabilities: sata msi pm ahci_1.0 bus_master cap_list
             configuration: driver=ahci latency=0
             resources: irq:142 memory:b4228000-b4229fff memory:b422f000-b422f0ff ioport:4080(size=8) ioport:4088(size=4) ioport:4060(size=32) memory:b422d000-b422d7ff
        *-pci:0
             description: PCI bridge
             product: Sunrise Point-LP PCI Express Root Port #1
             vendor: Intel Corporation
             physical id: 1c
             bus info: pci@0000:00:1c.0
             version: f1
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:122 ioport:3000(size=4096) memory:b3000000-b3ffffff ioport:a0000000(size=301989888)
           *-display
                description: 3D controller
                product: GP108M [GeForce MX150]
                vendor: NVIDIA Corporation
                physical id: 0
                bus info: pci@0000:01:00.0
                version: a1
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi pciexpress bus_master cap_list rom
                configuration: driver=nvidia latency=0
                resources: irq:147 memory:b3000000-b3ffffff memory:a0000000-afffffff memory:b0000000-b1ffffff ioport:3000(size=128)
        *-pci:1
             description: PCI bridge
             product: Sunrise Point-LP PCI Express Root Port #5
             vendor: Intel Corporation
             physical id: 1c.4
             bus info: pci@0000:00:1c.4
             version: f1
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:123 memory:b4100000-b41fffff
           *-network
                description: Wireless interface
                product: Wireless 8265 / 8275
                vendor: Intel Corporation
                physical id: 0
                bus info: pci@0000:02:00.0
                logical name: wlp2s0
                version: 78
                serial: c0:b6:f9:5f:4c:e5
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi pciexpress bus_master cap_list ethernet physical wireless
                configuration: broadcast=yes driver=iwlwifi driverversion=6.12.43+deb12-amd64 firmware=36.ca7b901d.0 8265-36.ucode ip=192.168.31.174 latency=0 link=yes multicast=yes wireless=IEEE 802.11
                resources: irq:145 memory:b4100000-b4101fff
        *-pci:2
             description: PCI bridge
             product: Sunrise Point-LP PCI Express Root Port #9
             vendor: Intel Corporation
             physical id: 1d
             bus info: pci@0000:00:1d.0
             version: f1
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:124 memory:b4000000-b40fffff
           *-nvme
                description: NVMe device
                product: SAMSUNG MZVLB256HAHQ-00000
                vendor: Samsung Electronics Co Ltd
                physical id: 0
                bus info: pci@0000:03:00.0
                logical name: /dev/nvme0
                version: EXD7101Q
                serial: S444NY0K516069
                width: 64 bits
                clock: 33MHz
                capabilities: nvme pm msi pciexpress msix nvm_express bus_master cap_list
                configuration: driver=nvme latency=0 nqn=nqn.2014.08.org.nvmexpress:144d144dS444NY0K516069      SAMSUNG MZVLB256HAHQ-00000 state=live
                resources: irq:16 memory:b4000000-b4003fff
              *-namespace:0
                   description: NVMe disk
                   physical id: 0
                   logical name: hwmon2
              *-namespace:1
                   description: NVMe disk
                   physical id: 2
                   logical name: /dev/ng0n1
              *-namespace:2
                   description: NVMe disk
                   physical id: 1
                   bus info: nvme@0:1
                   logical name: /dev/nvme0n1
                   size: 238GiB (256GB)
                   capabilities: gpt-1.00 partitioned partitioned:gpt
                   configuration: guid=f946ef85-1b9f-42a1-abca-be43e45ccc7c logicalsectorsize=512 sectorsize=512 wwid=eui.00253885810041de
                 *-volume:0
                      description: Windows FAT volume
                      vendor: mkfs.fat
                      physical id: 1
                      bus info: nvme@0:1,1
                      logical name: /dev/nvme0n1p1
                      logical name: /boot/efi
                      version: FAT32
                      serial: e518-2bff
                      size: 510MiB
                      capacity: 511MiB
                      capabilities: boot fat initialized
                      configuration: FATs=2 filesystem=fat mount.fstype=vfat mount.options=rw,relatime,fmask=0077,dmask=0077,codepage=437,iocharset=ascii,shortname=mixed,utf8,errors=remount-ro state=mounted
                 *-volume:1
                      description: EXT4 volume
                      vendor: Linux
                      physical id: 2
                      bus info: nvme@0:1,2
                      logical name: /dev/nvme0n1p2
                      logical name: /
                      version: 1.0
                      serial: 77618a28-79d5-4532-9d37-05675d86e213
                      size: 237GiB
                      capabilities: journaled extended_attributes large_files huge_files dir_nlink recover 64bit extents ext4 ext2 initialized
                      configuration: created=2025-08-11 19:46:09 filesystem=ext4 lastmountpoint=/ modified=2025-11-21 20:43:23 mount.fstype=ext4 mount.options=rw,relatime,errors=remount-ro mounted=2025-11-20 20:44:51 state=mounted
                 *-volume:2
                      description: Linux swap volume
                      vendor: Linux
                      physical id: 3
                      bus info: nvme@0:1,3
                      logical name: /dev/nvme0n1p3
                      version: 1
                      serial: 14441448-c379-4f87-b46e-00d8b078d9d8
                      size: 976MiB
                      capacity: 976MiB
                      capabilities: nofs swap initialized
                      configuration: filesystem=swap pagesize=4095
        *-isa
             description: ISA bridge
             product: Sunrise Point LPC Controller/eSPI Controller
             vendor: Intel Corporation
             physical id: 1f
             bus info: pci@0000:00:1f.0
             version: 21
             width: 32 bits
             clock: 33MHz
             capabilities: isa bus_master
             configuration: latency=0
           *-pnp00:00
                product: PnP device PNP0c02
                physical id: 0
                capabilities: pnp
                configuration: driver=system
           *-pnp00:01
                product: PnP device PNP0c02
                physical id: 1
                capabilities: pnp
                configuration: driver=system
           *-pnp00:02
                product: PnP device PNP0c02
                physical id: 2
                capabilities: pnp
                configuration: driver=system
           *-pnp00:03
                product: PnP device PNP0b00
                physical id: 3
                capabilities: pnp
                configuration: driver=rtc_cmos
           *-pnp00:04
                product: PnP device PNP0303
                physical id: 4
                capabilities: pnp
                configuration: driver=i8042 kbd
           *-pnp00:05
                product: PnP device PNP0c02
                physical id: 5
                capabilities: pnp
                configuration: driver=system
           *-pnp00:06
                product: PnP device PNP0c02
                physical id: 6
                capabilities: pnp
                configuration: driver=system
        *-memory UNCLAIMED
             description: Memory controller
             product: Sunrise Point-LP PMC
             vendor: Intel Corporation
             physical id: 1f.2
             bus info: pci@0000:00:1f.2
             version: 21
             width: 32 bits
             clock: 33MHz (30.3ns)
             capabilities: bus_master
             configuration: latency=0
             resources: memory:b4224000-b4227fff
        *-multimedia
             description: Audio device
             product: Sunrise Point-LP HD Audio
             vendor: Intel Corporation
             physical id: 1f.3
             bus info: pci@0000:00:1f.3
             logical name: card0
             logical name: /dev/snd/controlC0
             logical name: /dev/snd/hwC0D0
             logical name: /dev/snd/hwC0D2
             logical name: /dev/snd/pcmC0D0c
             logical name: /dev/snd/pcmC0D0p
             logical name: /dev/snd/pcmC0D3p
             logical name: /dev/snd/pcmC0D7p
             logical name: /dev/snd/pcmC0D8p
             version: 21
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi bus_master cap_list
             configuration: driver=snd_hda_intel latency=32
             resources: irq:146 memory:b4220000-b4223fff memory:b4200000-b420ffff
           *-input:0
                product: HDA Digital PCBeep
                physical id: 0
                logical name: input13
                logical name: /dev/input/event9
                capabilities: pci
           *-input:1
                product: HDA Intel PCH Headphone
                physical id: 1
                logical name: input14
                logical name: /dev/input/event10
           *-input:2
                product: HDA Intel PCH HDMI/DP,pcm=3
                physical id: 2
                logical name: input15
                logical name: /dev/input/event11
           *-input:3
                product: HDA Intel PCH HDMI/DP,pcm=7
                physical id: 3
                logical name: input16
                logical name: /dev/input/event12
           *-input:4
                product: HDA Intel PCH HDMI/DP,pcm=8
                physical id: 4
                logical name: input17
                logical name: /dev/input/event13
        *-serial
             description: SMBus
             product: Sunrise Point-LP SMBus
             vendor: Intel Corporation
             physical id: 1f.4
             bus info: pci@0000:00:1f.4
             version: 21
             width: 64 bits
             clock: 33MHz
             configuration: driver=i801_smbus latency=0
             resources: irq:16 memory:b422e000-b422e0ff ioport:4040(size=32)
  *-input:0
       product: AT Translated Set 2 keyboard
       physical id: 1
       logical name: input0
       logical name: /dev/input/event0
       logical name: input0::capslock
       logical name: input0::numlock
       logical name: input0::scrolllock
       capabilities: i8042
  *-input:1
       product: Lid Switch
       physical id: 2
       logical name: input1
       logical name: /dev/input/event1
       capabilities: platform
  *-input:2
       product: Video Bus
       physical id: 3
       logical name: input10
       logical name: /dev/input/event6
       capabilities: platform
  *-input:3
       product: Video Bus
       physical id: 4
       logical name: input11
       logical name: /dev/input/event7
       capabilities: platform
  *-input:4
       product: PC Speaker
       physical id: 5
       logical name: input12
       logical name: /dev/input/event8
       capabilities: isa
  *-input:5
       product: JBL Tune 520BT (AVRCP)
       physical id: 6
       logical name: input18
       logical name: /dev/input/event14
       capabilities: bluetooth
  *-input:6
       product: Sleep Button
       physical id: 7
       logical name: input2
       logical name: /dev/input/event2
       capabilities: platform
  *-input:7
       product: Power Button
       physical id: 8
       logical name: input3
       logical name: /dev/input/event3
       capabilities: platform
  *-input:8
       product: ELAN2301:00 04F3:306B Mouse
       physical id: 9
       logical name: input7
       logical name: /dev/input/event4
       logical name: /dev/input/mouse0
       capabilities: i2c
  *-input:9
       product: ELAN2301:00 04F3:306B Touchpad
       physical id: a
       logical name: input9
       logical name: /dev/input/event5
       logical name: /dev/input/mouse1
       capabilities: i2c
  *-network
       description: Ethernet interface
       physical id: b
       bus info: usb@1:3.3.3
       logical name: enx00e04c3601cb
       serial: 00:e0:4c:36:01:cb
       size: 100Mbit/s
       capacity: 100Mbit/s
       capabilities: ethernet physical tp mii 10bt 10bt-fd 100bt 100bt-fd autonegotiation
       configuration: autonegotiation=on broadcast=yes driver=r8152 driverversion=v1.12.13 duplex=full ip=192.168.31.79 link=yes multicast=yes port=MII speed=100Mbit/s