# 🖥 System Inventory Report
Generated: Fri Nov 21 10:20:42 PM MSK 2025
Host: mint-ET2701I-W8


# General System Info

```
# dmidecode 3.5
Getting SMBIOS data from sysfs.
SMBIOS 2.7 present.

Handle 0x0001, DMI type 1, 27 bytes
System Information
	Manufacturer: ASUSTeK Computer INC.
	Product Name: ET2701I-W8
	Version: 0502
	Serial Number: D4PTCY011815
	UUID: eebce33e-a0a3-11e2-a3cc-74d02b0a56d1
	Wake-up Type: Power Switch
	SKU Number: SKU
	Family: Eee Family

Handle 0x0025, DMI type 12, 5 bytes
System Configuration Options
	Option 1: To Be Filled By O.E.M.

Handle 0x0026, DMI type 32, 20 bytes
System Boot Information
	Status: No errors detected

```


# CPU

```
Architecture:                            x86_64
CPU op-mode(s):                          32-bit, 64-bit
Address sizes:                           36 bits physical, 48 bits virtual
Byte Order:                              Little Endian
CPU(s):                                  4
On-line CPU(s) list:                     0-3
Vendor ID:                               GenuineIntel
BIOS Vendor ID:                          Intel
Model name:                              Intel(R) Core(TM) i3-3220 CPU @ 3.30GHz
BIOS Model name:                         Intel(R) Core(TM) i3-3220 CPU @ 3.30GHz To Be Filled By O.E.M. CPU @ 3.3GHz
BIOS CPU family:                         191
CPU family:                              6
Model:                                   58
Thread(s) per core:                      2
Core(s) per socket:                      2
Socket(s):                               1
Stepping:                                9
CPU(s) scaling MHz:                      70%
CPU max MHz:                             3300,0000
CPU min MHz:                             1600,0000
BogoMIPS:                                6585,37
Flags:                                   fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx rdtscp lm constant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq dtes64 monitor ds_cpl est tm2 ssse3 cx16 xtpr pdcm pcid sse4_1 sse4_2 popcnt tsc_deadline_timer xsave avx f16c lahf_lm cpuid_fault epb pti ssbd ibrs ibpb stibp fsgsbase smep erms xsaveopt dtherm arat pln pts md_clear flush_l1d
L1d cache:                               64 KiB (2 instances)
L1i cache:                               64 KiB (2 instances)
L2 cache:                                512 KiB (2 instances)
L3 cache:                                3 MiB (1 instance)
NUMA node(s):                            1
NUMA node0 CPU(s):                       0-3
Vulnerability Gather data sampling:      Not affected
Vulnerability Ghostwrite:                Not affected
Vulnerability Indirect target selection: Not affected
Vulnerability Itlb multihit:             KVM: Mitigation: VMX unsupported
Vulnerability L1tf:                      Mitigation; PTE Inversion
Vulnerability Mds:                       Mitigation; Clear CPU buffers; SMT vulnerable
Vulnerability Meltdown:                  Mitigation; PTI
Vulnerability Mmio stale data:           Unknown: No mitigations
Vulnerability Reg file data sampling:    Not affected
Vulnerability Retbleed:                  Not affected
Vulnerability Spec rstack overflow:      Not affected
Vulnerability Spec store bypass:         Mitigation; Speculative Store Bypass disabled via prctl
Vulnerability Spectre v1:                Mitigation; usercopy/swapgs barriers and __user pointer sanitization
Vulnerability Spectre v2:                Mitigation; Retpolines; IBPB conditional; IBRS_FW; STIBP conditional; RSB filling; PBRSB-eIBRS Not affected; BHI Not affected
Vulnerability Srbds:                     Not affected
Vulnerability Tsa:                       Not affected
Vulnerability Tsx async abort:           Not affected
```


# Memory

```
# dmidecode 3.5
Getting SMBIOS data from sysfs.
SMBIOS 2.7 present.

Handle 0x0059, DMI type 17, 34 bytes
Memory Device
	Array Handle: 0x005A
	Error Information Handle: 0x005D
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: DIMM
	Set: None
	Locator: ChannelA-DIMM0
	Bank Locator: BANK 0
	Type: Unknown
	Type Detail: None

Handle 0x005A, DMI type 16, 23 bytes
Physical Memory Array
	Location: System Board Or Motherboard
	Use: System Memory
	Error Correction Type: None
	Maximum Capacity: 32 GB
	Error Information Handle: 0x005B
	Number Of Devices: 4

Handle 0x005C, DMI type 17, 34 bytes
Memory Device
	Array Handle: 0x005A
	Error Information Handle: No Error
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: DIMM
	Set: None
	Locator: ChannelA-DIMM1
	Bank Locator: BANK 1
	Type: Unknown
	Type Detail: None

Handle 0x005E, DMI type 17, 34 bytes
Memory Device
	Array Handle: 0x005A
	Error Information Handle: 0x005F
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: DIMM
	Set: None
	Locator: ChannelB-DIMM0
	Bank Locator: BANK 2
	Type: Unknown
	Type Detail: None

Handle 0x0060, DMI type 17, 34 bytes
Memory Device
	Array Handle: 0x005A
	Error Information Handle: No Error
	Total Width: 64 bits
	Data Width: 64 bits
	Size: 4 GB
	Form Factor: SODIMM
	Set: None
	Locator: ChannelB-DIMM1
	Bank Locator: BANK 3
	Type: DDR3
	Type Detail: Synchronous
	Speed: 1600 MT/s
	Manufacturer: Hynix/Hyundai
	Serial Number: 13242D06
	Asset Tag: 9876543210
	Part Number: HMT351S6CFR8C-PB  
	Rank: 2
	Configured Memory Speed: 1600 MT/s

```


# PCI Devices

```
00:00.0 Host bridge [0600]: Intel Corporation Xeon E3-1200 v2/3rd Gen Core processor DRAM Controller [8086:0150] (rev 09)
00:01.0 PCI bridge [0604]: Intel Corporation Xeon E3-1200 v2/3rd Gen Core processor PCI Express Root Port [8086:0151] (rev 09)
00:02.0 VGA compatible controller [0300]: Intel Corporation Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller [8086:0152] (rev 09)
00:16.0 Communication controller [0780]: Intel Corporation 6 Series/C200 Series Chipset Family MEI Controller #1 [8086:1c3a] (rev 04)
00:1a.0 USB controller [0c03]: Intel Corporation 6 Series/C200 Series Chipset Family USB Enhanced Host Controller #2 [8086:1c2d] (rev 05)
00:1b.0 Audio device [0403]: Intel Corporation 6 Series/C200 Series Chipset Family High Definition Audio Controller [8086:1c20] (rev 05)
00:1c.0 PCI bridge [0604]: Intel Corporation 6 Series/C200 Series Chipset Family PCI Express Root Port 1 [8086:1c10] (rev b5)
00:1c.1 PCI bridge [0604]: Intel Corporation 6 Series/C200 Series Chipset Family PCI Express Root Port 2 [8086:1c12] (rev b5)
00:1c.2 PCI bridge [0604]: Intel Corporation 6 Series/C200 Series Chipset Family PCI Express Root Port 3 [8086:1c14] (rev b5)
00:1c.3 PCI bridge [0604]: Intel Corporation 6 Series/C200 Series Chipset Family PCI Express Root Port 4 [8086:1c16] (rev b5)
00:1d.0 USB controller [0c03]: Intel Corporation 6 Series/C200 Series Chipset Family USB Enhanced Host Controller #1 [8086:1c26] (rev 05)
00:1f.0 ISA bridge [0601]: Intel Corporation H61 Express Chipset LPC Controller [8086:1c5c] (rev 05)
00:1f.2 SATA controller [0106]: Intel Corporation 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller [8086:1c02] (rev 05)
00:1f.3 SMBus [0c05]: Intel Corporation 6 Series/C200 Series Chipset Family SMBus Controller [8086:1c22] (rev 05)
01:00.0 VGA compatible controller [0300]: NVIDIA Corporation GK107M [GeForce GT 640M] [10de:0fd2] (rev a1)
03:00.0 USB controller [0c03]: ASMedia Technology Inc. ASM1042 SuperSpeed USB Host Controller [1b21:1042]
04:00.0 Network controller [0280]: Qualcomm Atheros AR9485 Wireless Network Adapter [168c:0032] (rev 01)
05:00.0 Ethernet controller [0200]: Realtek Semiconductor Co., Ltd. RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller [10ec:8168] (rev 06)
```


# USB Devices

```
/:  Bus 001.Port 001: Dev 001, Class=root_hub, Driver=xhci_hcd/2p, 480M
    |__ Port 001: Dev 003, If 0, Class=Human Interface Device, Driver=usbhid, 12M
    |__ Port 001: Dev 003, If 1, Class=Human Interface Device, Driver=usbhid, 12M
    |__ Port 002: Dev 002, If 0, Class=Human Interface Device, Driver=usbhid, 12M
    |__ Port 002: Dev 002, If 1, Class=Human Interface Device, Driver=usbhid, 12M
/:  Bus 002.Port 001: Dev 001, Class=root_hub, Driver=ehci-pci/2p, 480M
    |__ Port 001: Dev 002, If 0, Class=Hub, Driver=hub/6p, 480M
        |__ Port 003: Dev 003, If 0, Class=Hub, Driver=hub/4p, 480M
            |__ Port 002: Dev 005, If 0, Class=Video, Driver=uvcvideo, 480M
            |__ Port 002: Dev 005, If 1, Class=Video, Driver=uvcvideo, 480M
            |__ Port 004: Dev 007, If 0, Class=Vendor Specific Class, Driver=xpad, 12M
            |__ Port 004: Dev 007, If 1, Class=Vendor Specific Class, Driver=[none], 12M
            |__ Port 004: Dev 007, If 2, Class=Vendor Specific Class, Driver=[none], 12M
            |__ Port 004: Dev 007, If 3, Class=Vendor Specific Class, Driver=[none], 12M
        |__ Port 005: Dev 004, If 0, Class=Vendor Specific Class, Driver=[none], 480M
        |__ Port 005: Dev 004, If 1, Class=Vendor Specific Class, Driver=[none], 480M
        |__ Port 005: Dev 004, If 2, Class=Vendor Specific Class, Driver=[none], 480M
        |__ Port 005: Dev 004, If 3, Class=Vendor Specific Class, Driver=[none], 480M
        |__ Port 005: Dev 004, If 4, Class=Vendor Specific Class, Driver=[none], 480M
        |__ Port 005: Dev 004, If 5, Class=Vendor Specific Class, Driver=[none], 480M
        |__ Port 005: Dev 004, If 6, Class=Vendor Specific Class, Driver=[none], 480M
/:  Bus 003.Port 001: Dev 001, Class=root_hub, Driver=xhci_hcd/2p, 5000M
/:  Bus 004.Port 001: Dev 001, Class=root_hub, Driver=ehci-pci/2p, 480M
    |__ Port 001: Dev 002, If 0, Class=Hub, Driver=hub/4p, 480M
```


# USB List

```
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 001 Device 002: ID 3151:3020 YICHIP Wireless Device
Bus 001 Device 003: ID 258a:002a SINO WEALTH Gaming KB 
Bus 002 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 002 Device 002: ID 8087:0024 Intel Corp. Integrated Rate Matching Hub
Bus 002 Device 003: ID 058f:6254 Alcor Micro Corp. USB Hub
Bus 002 Device 004: ID 1164:1ee9 YUAN High-Tech Development Co., Ltd Polaris AV Capture
Bus 002 Device 005: ID 1bcf:2c31 Sunplus Innovation Technology Inc. Integrated Camera
Bus 002 Device 007: ID 045e:028e Microsoft Corp. Xbox360 Controller
Bus 003 Device 001: ID 1d6b:0003 Linux Foundation 3.0 root hub
Bus 004 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 004 Device 002: ID 8087:0024 Intel Corp. Integrated Rate Matching Hub
```


# Network Info

```
GENERAL.DEVICE:                         enp5s0
GENERAL.TYPE:                           ethernet
GENERAL.HWADDR:                         74:D0:2B:0A:56:D1
GENERAL.MTU:                            1500
GENERAL.STATE:                          100 (connected)
GENERAL.CONNECTION:                     Wired connection 1
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/2
WIRED-PROPERTIES.CARRIER:               on
IP4.ADDRESS[1]:                         192.168.31.135/24
IP4.GATEWAY:                            192.168.31.1
IP4.ROUTE[1]:                           dst = 192.168.31.0/24, nh = 0.0.0.0, mt = 100
IP4.ROUTE[2]:                           dst = 0.0.0.0/0, nh = 192.168.31.1, mt = 100
IP4.DNS[1]:                             192.168.31.1
IP6.ADDRESS[1]:                         fe80::f26b:417e:bd72:f1ab/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 1024

GENERAL.DEVICE:                         wlp4s0
GENERAL.TYPE:                           wifi
GENERAL.HWADDR:                         2C:D0:5A:B0:62:D5
GENERAL.MTU:                            1500
GENERAL.STATE:                          100 (connected)
GENERAL.CONNECTION:                     FatDog
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/3
IP4.ADDRESS[1]:                         192.168.31.36/24
IP4.GATEWAY:                            192.168.31.1
IP4.ROUTE[1]:                           dst = 192.168.31.0/24, nh = 0.0.0.0, mt = 600
IP4.ROUTE[2]:                           dst = 0.0.0.0/0, nh = 192.168.31.1, mt = 600
IP4.DNS[1]:                             192.168.31.1
IP6.ADDRESS[1]:                         fe80::6ac5:471b:27cb:6518/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 1024

GENERAL.DEVICE:                         tailscale0
GENERAL.TYPE:                           tun
GENERAL.HWADDR:                         (unknown)
GENERAL.MTU:                            1280
GENERAL.STATE:                          100 (connected (externally))
GENERAL.CONNECTION:                     tailscale0
GENERAL.CON-PATH:                       /org/freedesktop/NetworkManager/ActiveConnection/4
IP4.ADDRESS[1]:                         100.93.78.24/32
IP4.GATEWAY:                            --
IP4.ROUTE[1]:                           dst = 100.95.197.3/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[2]:                           dst = 100.111.241.106/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[3]:                           dst = 100.72.58.18/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[4]:                           dst = 100.78.90.49/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[5]:                           dst = 100.115.138.56/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[6]:                           dst = 100.100.100.100/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[7]:                           dst = 100.66.124.80/32, nh = 0.0.0.0, mt = 0, table=52
IP4.ROUTE[8]:                           dst = 100.78.142.88/32, nh = 0.0.0.0, mt = 0, table=52
IP6.ADDRESS[1]:                         fd7a:115c:a1e0::3501:4e27/128
IP6.ADDRESS[2]:                         fe80::27bd:bc03:7574:361e/64
IP6.GATEWAY:                            --
IP6.ROUTE[1]:                           dst = fe80::/64, nh = ::, mt = 256
IP6.ROUTE[2]:                           dst = fd7a:115c:a1e0::/48, nh = ::, mt = 1024, table=52
IP6.ROUTE[3]:                           dst = fd7a:115c:a1e0::53/128, nh = ::, mt = 1024, table=52
IP6.ROUTE[4]:                           dst = fd7a:115c:a1e0::3501:4e27/128, nh = ::, mt = 256

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

GENERAL.DEVICE:                         p2p-dev-wlp4s0
GENERAL.TYPE:                           wifi-p2p
GENERAL.HWADDR:                         (unknown)
GENERAL.MTU:                            0
GENERAL.STATE:                          30 (disconnected)
GENERAL.CONNECTION:                     --
GENERAL.CON-PATH:                       --
```


# IP Interfaces

```
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute 
       valid_lft forever preferred_lft forever
2: enp5s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 74:d0:2b:0a:56:d1 brd ff:ff:ff:ff:ff:ff
    inet 192.168.31.135/24 brd 192.168.31.255 scope global dynamic noprefixroute enp5s0
       valid_lft 42568sec preferred_lft 42568sec
    inet6 fe80::f26b:417e:bd72:f1ab/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
3: wlp4s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default qlen 1000
    link/ether 2c:d0:5a:b0:62:d5 brd ff:ff:ff:ff:ff:ff
    inet 192.168.31.36/24 brd 192.168.31.255 scope global dynamic noprefixroute wlp4s0
       valid_lft 42568sec preferred_lft 42568sec
    inet6 fe80::6ac5:471b:27cb:6518/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
4: tailscale0: <POINTOPOINT,MULTICAST,NOARP,UP,LOWER_UP> mtu 1280 qdisc fq_codel state UNKNOWN group default qlen 500
    link/none 
    inet 100.93.78.24/32 scope global tailscale0
       valid_lft forever preferred_lft forever
    inet6 fd7a:115c:a1e0::3501:4e27/128 scope global 
       valid_lft forever preferred_lft forever
    inet6 fe80::27bd:bc03:7574:361e/64 scope link stable-privacy 
       valid_lft forever preferred_lft forever
```


# Sensors

```
coretemp-isa-0000
Adapter: ISA adapter
Package id 0:  +46.0°C  (high = +85.0°C, crit = +105.0°C)
Core 0:        +45.0°C  (high = +85.0°C, crit = +105.0°C)
Core 1:        +45.0°C  (high = +85.0°C, crit = +105.0°C)

acpitz-acpi-0
Adapter: ACPI interface
temp1:        +27.8°C  
temp2:        +29.8°C  

```


# Storage (lsblk)

```
NAME     SIZE TYPE MOUNTPOINT FSTYPE MODEL
sda    931,5G disk                   WDC WD10EZEX-22RKKA0
├─sda1   512M part /boot/efi  vfat   
└─sda2   931G part /          ext4   
sr0     1024M rom                    Slimtype DVD A DS8A9SH
```


# SMART: /dev/sda

```
```


# SMART: /dev/sr0

```
```


# Display EDID

```
```


# DMIDecode (full)

```
# dmidecode 3.5
Getting SMBIOS data from sysfs.
SMBIOS 2.7 present.
102 structures occupying 3745 bytes.
Table at 0xBD3EA018.

Handle 0x0000, DMI type 0, 24 bytes
BIOS Information
	Vendor: American Megatrends Inc.
	Version: 0502
	Release Date: 11/01/2012
	Address: 0xF0000
	Runtime Size: 64 kB
	ROM Size: 8 MB
	Characteristics:
		PCI is supported
		BIOS is upgradeable
		BIOS shadowing is allowed
		Boot from CD is supported
		Selectable boot is supported
		BIOS ROM is socketed
		EDD is supported
		5.25"/1.2 MB floppy services are supported (int 13h)
		3.5"/720 kB floppy services are supported (int 13h)
		3.5"/2.88 MB floppy services are supported (int 13h)
		Print screen service is supported (int 5h)
		8042 keyboard services are supported (int 9h)
		Serial services are supported (int 14h)
		Printer services are supported (int 17h)
		ACPI is supported
		USB legacy is supported
		BIOS boot specification is supported
		Targeted content distribution is supported
		UEFI is supported
	BIOS Revision: 4.6

Handle 0x0001, DMI type 1, 27 bytes
System Information
	Manufacturer: ASUSTeK Computer INC.
	Product Name: ET2701I-W8
	Version: 0502
	Serial Number: D4PTCY011815
	UUID: eebce33e-a0a3-11e2-a3cc-74d02b0a56d1
	Wake-up Type: Power Switch
	SKU Number: SKU
	Family: Eee Family

Handle 0x0002, DMI type 2, 15 bytes
Base Board Information
	Manufacturer: ASUSTeK COMPUTER INC.
	Product Name: ET2701I-W8
	Version: Rev 1.xx
	Serial Number: MB-1234567890
	Asset Tag: To be filled by O.E.M.
	Features:
		Board is a hosting board
		Board is replaceable
	Location In Chassis: To be filled by O.E.M.
	Chassis Handle: 0x0003
	Type: Motherboard
	Contained Object Handles: 0

Handle 0x0003, DMI type 3, 22 bytes
Chassis Information
	Manufacturer: Chassis Manufacture
	Type: Desktop
	Lock: Not Present
	Version: Chassis Version
	Serial Number: Chassis Serial Number
	Asset Tag: Asset-1234567890
	Boot-up State: Safe
	Power Supply State: Safe
	Thermal State: Safe
	Security Status: None
	OEM Information: 0x00000000
	Height: Unspecified
	Number Of Power Cords: 1
	Contained Elements: 0
	SKU Number: To be filled by O.E.M.

Handle 0x0004, DMI type 4, 42 bytes
Processor Information
	Socket Designation: LGA1155
	Type: Central Processor
	Family: Core 2 Duo
	Manufacturer: Intel
	ID: A9 06 03 00 FF FB EB BF
	Signature: Type 0, Family 6, Model 58, Stepping 9
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
	Version: Intel(R) Core(TM) i3-3220 CPU @ 3.30GHz
	Voltage: 1.0 V
	External Clock: 100 MHz
	Max Speed: 3800 MHz
	Current Speed: 3300 MHz
	Status: Populated, Enabled
	Upgrade: Other
	L1 Cache Handle: 0x0005
	L2 Cache Handle: 0x0006
	L3 Cache Handle: 0x0007
	Serial Number: To Be Filled By O.E.M.
	Asset Tag: To Be Filled By O.E.M.
	Part Number: To Be Filled By O.E.M.
	Core Count: 2
	Core Enabled: 1
	Thread Count: 2
	Characteristics:
		64-bit capable

Handle 0x0005, DMI type 7, 19 bytes
Cache Information
	Socket Designation: L1-Cache
	Configuration: Enabled, Not Socketed, Level 1
	Operational Mode: Write Back
	Location: Internal
	Installed Size: 32 kB
	Maximum Size: 32 kB
	Supported SRAM Types:
		Other
	Installed SRAM Type: Other
	Speed: Unknown
	Error Correction Type: None
	System Type: Unified
	Associativity: 8-way Set-associative

Handle 0x0006, DMI type 7, 19 bytes
Cache Information
	Socket Designation: L2-Cache
	Configuration: Enabled, Not Socketed, Level 2
	Operational Mode: Varies With Memory Address
	Location: Internal
	Installed Size: 256 kB
	Maximum Size: 256 kB
	Supported SRAM Types:
		Other
	Installed SRAM Type: Other
	Speed: Unknown
	Error Correction Type: None
	System Type: Unified
	Associativity: 8-way Set-associative

Handle 0x0007, DMI type 7, 19 bytes
Cache Information
	Socket Designation: L3-Cache
	Configuration: Disabled, Not Socketed, Level 3
	Operational Mode: Unknown
	Location: Internal
	Installed Size: 3 MB
	Maximum Size: 3 MB
	Supported SRAM Types:
		Other
	Installed SRAM Type: Other
	Speed: Unknown
	Error Correction Type: None
	System Type: Unified
	Associativity: Other

Handle 0x0008, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: PS/2 Keyboard
	Internal Connector Type: None
	External Reference Designator: PS/2 Keyboard
	External Connector Type: PS/2
	Port Type: Keyboard Port

Handle 0x0009, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: USB9_10
	Internal Connector Type: None
	External Reference Designator: USB9_10
	External Connector Type: Access Bus (USB)
	Port Type: USB

Handle 0x000A, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: USB11_12
	Internal Connector Type: None
	External Reference Designator: USB11_12
	External Connector Type: Access Bus (USB)
	Port Type: USB

Handle 0x000B, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: USB3_12
	Internal Connector Type: None
	External Reference Designator: USB3_12
	External Connector Type: Access Bus (USB)
	Port Type: USB

Handle 0x000C, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: USB3_34
	Internal Connector Type: None
	External Reference Designator: USB3_34
	External Connector Type: Access Bus (USB)
	Port Type: USB

Handle 0x000D, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: USB3_E12
	Internal Connector Type: None
	External Reference Designator: USB3_E12
	External Connector Type: Access Bus (USB)
	Port Type: USB

Handle 0x000E, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: GbE LAN
	Internal Connector Type: None
	External Reference Designator: GbE LAN
	External Connector Type: RJ-45
	Port Type: Network Port

Handle 0x000F, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: SATA3G_3
	Internal Connector Type: SAS/SATA Plug Receptacle
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: SATA

Handle 0x0010, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: SATA3G_4
	Internal Connector Type: SAS/SATA Plug Receptacle
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: SATA

Handle 0x0011, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: SATA3G_5
	Internal Connector Type: SAS/SATA Plug Receptacle
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: SATA

Handle 0x0012, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: SATA3G_6
	Internal Connector Type: SAS/SATA Plug Receptacle
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: SATA

Handle 0x0013, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: SATA6G_1
	Internal Connector Type: SAS/SATA Plug Receptacle
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: SATA

Handle 0x0014, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: SATA6G_2
	Internal Connector Type: SAS/SATA Plug Receptacle
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: SATA

Handle 0x0015, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: USB1_2
	Internal Connector Type: Access Bus (USB)
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: USB

Handle 0x0016, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: USB3_4
	Internal Connector Type: Access Bus (USB)
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: USB

Handle 0x0017, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: USB5_6
	Internal Connector Type: Access Bus (USB)
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: USB

Handle 0x0018, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: USB7_8
	Internal Connector Type: Access Bus (USB)
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: USB

Handle 0x0019, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: AAFP
	Internal Connector Type: Mini Jack (headphones)
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: Audio Port

Handle 0x001A, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: CPU_FAN
	Internal Connector Type: Other
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: Other

Handle 0x001B, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: CHA_FAN1
	Internal Connector Type: Other
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: Other

Handle 0x001C, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: CHA_FAN2
	Internal Connector Type: Other
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: Other

Handle 0x001D, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: CHA_FAN3
	Internal Connector Type: Other
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: Other

Handle 0x001E, DMI type 8, 9 bytes
Port Connector Information
	Internal Reference Designator: COM1
	Internal Connector Type: DB-9 male
	External Reference Designator: Not Specified
	External Connector Type: None
	Port Type: Serial Port 16550A Compatible

Handle 0x001F, DMI type 9, 17 bytes
System Slot Information
	Designation: PCIEX16_1
	Type: 32-bit PCI Express
	Current Usage: In Use
	Length: Short
	ID: 1
	Characteristics:
		3.3 V is provided
		Opening is shared
		PME signal is supported
	Bus Address: 0000:01:01.0

Handle 0x0020, DMI type 9, 17 bytes
System Slot Information
	Designation: PCIEX1_1
	Type: 32-bit PCI Express
	Current Usage: In Use
	Length: Short
	ID: 2
	Characteristics:
		3.3 V is provided
		Opening is shared
		PME signal is supported
	Bus Address: 0000:05:1c.3

Handle 0x0021, DMI type 9, 17 bytes
System Slot Information
	Designation: PCIEX16_2
	Type: 32-bit PCI Express
	Current Usage: Available
	Length: Short
	ID: 3
	Characteristics:
		3.3 V is provided
		Opening is shared
		PME signal is supported
	Bus Address: 0000:ff:01.0

Handle 0x0022, DMI type 9, 17 bytes
System Slot Information
	Designation: PCIEX16_3
	Type: 32-bit PCI Express
	Current Usage: Available
	Length: Short
	ID: 4
	Characteristics:
		3.3 V is provided
		Opening is shared
		PME signal is supported
	Bus Address: 0000:ff:01.0

Handle 0x0023, DMI type 10, 6 bytes
On Board Device Information
	Type: Ethernet
	Status: Enabled
	Description: Onboard Ethernet

Handle 0x0024, DMI type 11, 5 bytes
OEM Strings
	String 1: 74D02B0A56D1
	String 2: AEMS0101010000000000002111001
	String 3: 90PTM00DA124121112112088WHE0160Q000000000
	String 4: 12219213001505021215493300620

Handle 0x0025, DMI type 12, 5 bytes
System Configuration Options
	Option 1: To Be Filled By O.E.M.

Handle 0x0026, DMI type 32, 20 bytes
System Boot Information
	Status: No errors detected

Handle 0x0027, DMI type 34, 11 bytes
Management Device
	Description: LM78-1
	Type: LM78
	Address: 0x00000000
	Address Type: I/O Port

Handle 0x0028, DMI type 26, 22 bytes
Voltage Probe
	Description: LM78A
	Location: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x0029, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 1
	Upper Non-critical Threshold: 2
	Lower Critical Threshold: 3
	Upper Critical Threshold: 4
	Lower Non-recoverable Threshold: 5
	Upper Non-recoverable Threshold: 6

Handle 0x002A, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0027
	Component Handle: 0x0027
	Threshold Handle: 0x0028

Handle 0x002B, DMI type 28, 22 bytes
Temperature Probe
	Description: LM78A
	Location: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x002C, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 1
	Upper Non-critical Threshold: 2
	Lower Critical Threshold: 3
	Upper Critical Threshold: 4
	Lower Non-recoverable Threshold: 5
	Upper Non-recoverable Threshold: 6

Handle 0x002D, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0027
	Component Handle: 0x002A
	Threshold Handle: 0x002B

Handle 0x002E, DMI type 27, 15 bytes
Cooling Device
	Temperature Probe Handle: 0x002B
	Type: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Cooling Unit Group: 1
	OEM-specific Information: 0x00000000
	Nominal Speed: Unknown Or Non-rotating
	Description: Cooling Dev 1

Handle 0x002F, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 1
	Upper Non-critical Threshold: 2
	Lower Critical Threshold: 3
	Upper Critical Threshold: 4
	Lower Non-recoverable Threshold: 5
	Upper Non-recoverable Threshold: 6

Handle 0x0030, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0027
	Component Handle: 0x002D
	Threshold Handle: 0x002E

Handle 0x0031, DMI type 27, 15 bytes
Cooling Device
	Temperature Probe Handle: 0x002B
	Type: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Cooling Unit Group: 1
	OEM-specific Information: 0x00000000
	Nominal Speed: Unknown Or Non-rotating
	Description: Not Specified

Handle 0x0032, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 1
	Upper Non-critical Threshold: 2
	Lower Critical Threshold: 3
	Upper Critical Threshold: 4
	Lower Non-recoverable Threshold: 5
	Upper Non-recoverable Threshold: 6

Handle 0x0033, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0027
	Component Handle: 0x0030
	Threshold Handle: 0x0031

Handle 0x0034, DMI type 29, 22 bytes
Electrical Current Probe
	Description: ABC
	Location: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x0035, DMI type 36, 16 bytes
Management Device Threshold Data

Handle 0x0036, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0027
	Component Handle: 0x0033
	Threshold Handle: 0x0031

Handle 0x0037, DMI type 34, 16 bytes
Management Device
	Description: LM78-2
	Type: LM78
	Address: 0x00000000
	Address Type: I/O Port

Handle 0x0038, DMI type 26, 22 bytes
Voltage Probe
	Description: LM78B
	Location: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x0039, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 7
	Upper Non-critical Threshold: 8
	Lower Critical Threshold: 8
	Upper Critical Threshold: 10
	Lower Non-recoverable Threshold: 11
	Upper Non-recoverable Threshold: 12

Handle 0x003A, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0037
	Component Handle: 0x0037
	Threshold Handle: 0x0038

Handle 0x003B, DMI type 26, 22 bytes
Voltage Probe
	Description: LM78B
	Location: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x003C, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 13
	Upper Non-critical Threshold: 14
	Lower Critical Threshold: 15
	Upper Critical Threshold: 16
	Lower Non-recoverable Threshold: 17
	Upper Non-recoverable Threshold: 18

Handle 0x003D, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0037
	Component Handle: 0x003A
	Threshold Handle: 0x003B

Handle 0x003E, DMI type 28, 22 bytes
Temperature Probe
	Description: LM78B
	Location: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x003F, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 1
	Upper Non-critical Threshold: 2
	Lower Critical Threshold: 3
	Upper Critical Threshold: 4
	Lower Non-recoverable Threshold: 5
	Upper Non-recoverable Threshold: 6

Handle 0x0040, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0037
	Component Handle: 0x003D
	Threshold Handle: 0x003E

Handle 0x0041, DMI type 27, 15 bytes
Cooling Device
	Temperature Probe Handle: 0x003E
	Type: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Cooling Unit Group: 1
	OEM-specific Information: 0x00000000
	Nominal Speed: Unknown Or Non-rotating
	Description: Cooling Dev 2

Handle 0x0042, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 1
	Upper Non-critical Threshold: 2
	Lower Critical Threshold: 3
	Upper Critical Threshold: 4
	Lower Non-recoverable Threshold: 5
	Upper Non-recoverable Threshold: 6

Handle 0x0043, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0037
	Component Handle: 0x0040
	Threshold Handle: 0x0041

Handle 0x0044, DMI type 28, 22 bytes
Temperature Probe
	Description: LM78B
	Location: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x0045, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 1
	Upper Non-critical Threshold: 2
	Lower Critical Threshold: 3
	Upper Critical Threshold: 4
	Lower Non-recoverable Threshold: 5
	Upper Non-recoverable Threshold: 6

Handle 0x0046, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0037
	Component Handle: 0x0043
	Threshold Handle: 0x0044

Handle 0x0047, DMI type 27, 15 bytes
Cooling Device
	Temperature Probe Handle: 0x0044
	Type: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Cooling Unit Group: 1
	OEM-specific Information: 0x00000000
	Nominal Speed: Unknown Or Non-rotating
	Description: Cooling Dev 2

Handle 0x0048, DMI type 36, 16 bytes
Management Device Threshold Data
	Lower Non-critical Threshold: 1
	Upper Non-critical Threshold: 2
	Lower Critical Threshold: 3
	Upper Critical Threshold: 4
	Lower Non-recoverable Threshold: 5
	Upper Non-recoverable Threshold: 6

Handle 0x0049, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0037
	Component Handle: 0x0046
	Threshold Handle: 0x0047

Handle 0x004A, DMI type 29, 22 bytes
Electrical Current Probe
	Description: DEF
	Location: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x004B, DMI type 36, 16 bytes
Management Device Threshold Data

Handle 0x004C, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0037
	Component Handle: 0x0049
	Threshold Handle: 0x0047

Handle 0x004D, DMI type 29, 22 bytes
Electrical Current Probe
	Description: GHI
	Location: <OUT OF SPEC>
	Status: <OUT OF SPEC>
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x004E, DMI type 36, 16 bytes
Management Device Threshold Data

Handle 0x004F, DMI type 35, 11 bytes
Management Device Component
	Description: To Be Filled By O.E.M.
	Management Device Handle: 0x0037
	Component Handle: 0x004C
	Threshold Handle: 0x0047

Handle 0x0050, DMI type 26, 22 bytes
Voltage Probe
	Description: LM78A
	Location: Power Unit
	Status: OK
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x0051, DMI type 28, 22 bytes
Temperature Probe
	Description: LM78A
	Location: Power Unit
	Status: OK
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x0052, DMI type 27, 15 bytes
Cooling Device
	Temperature Probe Handle: 0x0051
	Type: Power Supply Fan
	Status: OK
	Cooling Unit Group: 1
	OEM-specific Information: 0x00000000
	Nominal Speed: Unknown Or Non-rotating
	Description: Cooling Dev 1

Handle 0x0053, DMI type 29, 22 bytes
Electrical Current Probe
	Description: ABC
	Location: Power Unit
	Status: OK
	Maximum Value: Unknown
	Minimum Value: Unknown
	Resolution: Unknown
	Tolerance: Unknown
	Accuracy: Unknown
	OEM-specific Information: 0x00000000
	Nominal Value: Unknown

Handle 0x0054, DMI type 39, 22 bytes
System Power Supply
	Power Unit Group: 1
	Location: To Be Filled By O.E.M.
	Name: To Be Filled By O.E.M.
	Manufacturer: To Be Filled By O.E.M.
	Serial Number: To Be Filled By O.E.M.
	Asset Tag: To Be Filled By O.E.M.
	Model Part Number: To Be Filled By O.E.M.
	Revision: To Be Filled By O.E.M.
	Max Power Capacity: Unknown
	Status: Present, OK
	Type: Switching
	Input Voltage Range Switching: Auto-switch
	Plugged: Yes
	Hot Replaceable: No
	Input Voltage Probe Handle: 0x0050
	Cooling Device Handle: 0x0052
	Input Current Probe Handle: 0x0053

Handle 0x0055, DMI type 41, 11 bytes
Onboard Device
	Reference Designation:  Onboard IGD
	Type: Video
	Status: Enabled
	Type Instance: 1
	Bus Address: 0000:00:02.0

Handle 0x0056, DMI type 41, 11 bytes
Onboard Device
	Reference Designation:  Onboard LAN
	Type: Ethernet
	Status: Enabled
	Type Instance: 1
	Bus Address: 0000:00:19.0

Handle 0x0057, DMI type 41, 11 bytes
Onboard Device
	Reference Designation:  Onboard 1394
	Type: Other
	Status: Enabled
	Type Instance: 1
	Bus Address: 0000:03:1c.2

Handle 0x0058, DMI type 139, 94 bytes
OEM-specific Type
	Header and Data:
		8B 5E 58 00 FE DC BA 98 76 54 32 10 04 04 32 55
		F8 00 A2 02 A1 00 40 63 43 10 FE 81 03 DF 40 80
		00 20 00 73 3C 10 08 00 60 0F 06 11 15 04 20 00
		3C 10 00 00 00 00 00 00 00 00 00 00 00 00 00 00
		00 00 00 00 69 00 00 FF FF 06 11 00 04 00 00 23
		33 00 00 00 00 00 00 00 00 00 00 00 00 01
	Strings:
		V1394GUID

Handle 0x0059, DMI type 17, 34 bytes
Memory Device
	Array Handle: 0x005A
	Error Information Handle: 0x005D
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: DIMM
	Set: None
	Locator: ChannelA-DIMM0
	Bank Locator: BANK 0
	Type: Unknown
	Type Detail: None

Handle 0x005A, DMI type 16, 23 bytes
Physical Memory Array
	Location: System Board Or Motherboard
	Use: System Memory
	Error Correction Type: None
	Maximum Capacity: 32 GB
	Error Information Handle: 0x005B
	Number Of Devices: 4

Handle 0x005B, DMI type 18, 23 bytes
32-bit Memory Error Information
	Type: OK
	Granularity: Unknown
	Operation: Unknown
	Vendor Syndrome: Unknown
	Memory Array Address: Unknown
	Device Address: Unknown
	Resolution: Unknown

Handle 0x005C, DMI type 17, 34 bytes
Memory Device
	Array Handle: 0x005A
	Error Information Handle: No Error
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: DIMM
	Set: None
	Locator: ChannelA-DIMM1
	Bank Locator: BANK 1
	Type: Unknown
	Type Detail: None

Handle 0x005D, DMI type 18, 23 bytes
32-bit Memory Error Information
	Type: OK
	Granularity: Unknown
	Operation: Unknown
	Vendor Syndrome: Unknown
	Memory Array Address: Unknown
	Device Address: Unknown
	Resolution: Unknown

Handle 0x005E, DMI type 17, 34 bytes
Memory Device
	Array Handle: 0x005A
	Error Information Handle: 0x005F
	Total Width: Unknown
	Data Width: Unknown
	Size: No Module Installed
	Form Factor: DIMM
	Set: None
	Locator: ChannelB-DIMM0
	Bank Locator: BANK 2
	Type: Unknown
	Type Detail: None

Handle 0x005F, DMI type 18, 23 bytes
32-bit Memory Error Information
	Type: OK
	Granularity: Unknown
	Operation: Unknown
	Vendor Syndrome: Unknown
	Memory Array Address: Unknown
	Device Address: Unknown
	Resolution: Unknown

Handle 0x0060, DMI type 17, 34 bytes
Memory Device
	Array Handle: 0x005A
	Error Information Handle: No Error
	Total Width: 64 bits
	Data Width: 64 bits
	Size: 4 GB
	Form Factor: SODIMM
	Set: None
	Locator: ChannelB-DIMM1
	Bank Locator: BANK 3
	Type: DDR3
	Type Detail: Synchronous
	Speed: 1600 MT/s
	Manufacturer: Hynix/Hyundai
	Serial Number: 13242D06
	Asset Tag: 9876543210
	Part Number: HMT351S6CFR8C-PB  
	Rank: 2
	Configured Memory Speed: 1600 MT/s

Handle 0x0061, DMI type 18, 23 bytes
32-bit Memory Error Information
	Type: OK
	Granularity: Unknown
	Operation: Unknown
	Vendor Syndrome: Unknown
	Memory Array Address: Unknown
	Device Address: Unknown
	Resolution: Unknown

Handle 0x0062, DMI type 20, 35 bytes
Memory Device Mapped Address
	Starting Address: 0x00000000000
	Ending Address: 0x000FFFFFFFF
	Range Size: 4 GB
	Physical Device Handle: 0x0060
	Memory Array Mapped Address Handle: 0x0063
	Partition Row Position: Unknown
	Interleave Position: 1
	Interleaved Data Depth: 1

Handle 0x0063, DMI type 19, 31 bytes
Memory Array Mapped Address
	Starting Address: 0x00000000000
	Ending Address: 0x000FFFFFFFF
	Range Size: 4 GB
	Physical Array Handle: 0x005A
	Partition Width: 4

Handle 0x0065, DMI type 13, 22 bytes
BIOS Language Information
	Language Description Format: Long
	Installable Languages: 8
		en|US|iso8859-1
		fr|FR|iso8859-1
		es|ES|iso8859-1
		de|DE|iso8859-1
		ru|RU|iso8859-5
		ja|JP|unicode
		zh|TW|unicode
		zh|CN|unicode
	Currently Installed Language: ru|RU|iso8859-5

Handle 0x0067, DMI type 127, 4 bytes
End Of Table

```


# LSHW (full)

```
mint-et2701i-w8
    description: Desktop Computer
    product: ET2701I-W8 (SKU)
    vendor: ASUSTeK Computer INC.
    version: 0502
    serial: D4PTCY011815
    width: 64 bits
    capabilities: smbios-2.7 dmi-2.7 smp vsyscall32
    configuration: boot=normal chassis=desktop family=Eee Family sku=SKU uuid=eebce33e-a0a3-11e2-a3cc-74d02b0a56d1
  *-core
       description: Motherboard
       product: ET2701I-W8
       vendor: ASUSTeK COMPUTER INC.
       physical id: 0
       version: Rev 1.xx
       serial: MB-1234567890
       slot: To be filled by O.E.M.
     *-firmware
          description: BIOS
          vendor: American Megatrends Inc.
          physical id: 0
          version: 0502
          date: 11/01/2012
          size: 64KiB
          capacity: 8MiB
          capabilities: pci upgrade shadowing cdboot bootselect socketedrom edd int13floppy1200 int13floppy720 int13floppy2880 int5printscreen int9keyboard int14serial int17printer acpi usb biosbootspecification uefi
     *-cpu
          description: CPU
          product: Intel(R) Core(TM) i3-3220 CPU @ 3.30GHz
          vendor: Intel Corp.
          physical id: 4
          bus info: cpu@0
          version: 6.58.9
          serial: To Be Filled By O.E.M.
          slot: LGA1155
          size: 2552MHz
          capacity: 3800MHz
          width: 64 bits
          clock: 100MHz
          capabilities: lm fpu fpu_exception wp vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx rdtscp x86-64 constant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq dtes64 monitor ds_cpl est tm2 ssse3 cx16 xtpr pdcm pcid sse4_1 sse4_2 popcnt tsc_deadline_timer xsave avx f16c lahf_lm cpuid_fault epb pti ssbd ibrs ibpb stibp fsgsbase smep erms xsaveopt dtherm arat pln pts md_clear flush_l1d cpufreq
          configuration: cores=2 enabledcores=1 microcode=33 threads=2
        *-cache:0
             description: L1 cache
             physical id: 5
             slot: L1-Cache
             size: 32KiB
             capacity: 32KiB
             capabilities: internal write-back unified
             configuration: level=1
        *-cache:1
             description: L2 cache
             physical id: 6
             slot: L2-Cache
             size: 256KiB
             capacity: 256KiB
             capabilities: internal varies unified
             configuration: level=2
        *-cache:2 DISABLED
             description: L3 cache
             physical id: 7
             slot: L3-Cache
             size: 3MiB
             capacity: 3MiB
             capabilities: internal unified
             configuration: level=3
     *-memory
          description: System memory
          physical id: 1
          size: 4GiB
        *-bank:0
             description: DIMM [empty]
             product: [Empty]
             vendor: [Empty]
             physical id: 0
             serial: [Empty]
             slot: ChannelA-DIMM0
        *-bank:1
             description: DIMM [empty]
             product: [Empty]
             vendor: [Empty]
             physical id: 1
             serial: [Empty]
             slot: ChannelA-DIMM1
        *-bank:2
             description: DIMM [empty]
             product: [Empty]
             vendor: [Empty]
             physical id: 2
             serial: [Empty]
             slot: ChannelB-DIMM0
        *-bank:3
             description: SODIMM DDR3 Synchronous 1600 MHz (0,6 ns)
             product: HMT351S6CFR8C-PB
             vendor: Hynix/Hyundai
             physical id: 3
             serial: 13242D06
             slot: ChannelB-DIMM1
             size: 4GiB
             width: 64 bits
             clock: 1600MHz (0.6ns)
     *-pci
          description: Host bridge
          product: Xeon E3-1200 v2/3rd Gen Core processor DRAM Controller
          vendor: Intel Corporation
          physical id: 100
          bus info: pci@0000:00:00.0
          version: 09
          width: 32 bits
          clock: 33MHz
          configuration: driver=ivb_uncore
          resources: irq:0
        *-pci:0
             description: PCI bridge
             product: Xeon E3-1200 v2/3rd Gen Core processor PCI Express Root Port
             vendor: Intel Corporation
             physical id: 1
             bus info: pci@0000:00:01.0
             version: 09
             width: 32 bits
             clock: 33MHz
             capabilities: pci pm msi pciexpress normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:24 ioport:e000(size=4096) memory:f6000000-f70fffff ioport:e0000000(size=301989888)
           *-display UNCLAIMED
                description: VGA compatible controller
                product: GK107M [GeForce GT 640M]
                vendor: NVIDIA Corporation
                physical id: 0
                bus info: pci@0000:01:00.0
                version: a1
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi pciexpress vga_controller cap_list
                configuration: latency=0
                resources: memory:f6000000-f6ffffff memory:e0000000-efffffff memory:f0000000-f1ffffff ioport:e000(size=128) memory:f7000000-f707ffff
        *-display
             description: VGA compatible controller
             product: Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller
             vendor: Intel Corporation
             physical id: 2
             bus info: pci@0000:00:02.0
             logical name: /dev/fb0
             version: 09
             width: 64 bits
             clock: 33MHz
             capabilities: msi pm vga_controller bus_master cap_list rom fb
             configuration: depth=32 driver=i915 latency=0 resolution=1920,1080
             resources: irq:33 memory:f7400000-f77fffff memory:d0000000-dfffffff ioport:f000(size=64) memory:c0000-dffff
        *-communication
             description: Communication controller
             product: 6 Series/C200 Series Chipset Family MEI Controller #1
             vendor: Intel Corporation
             physical id: 16
             bus info: pci@0000:00:16.0
             version: 04
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi bus_master cap_list
             configuration: driver=mei_me latency=0
             resources: irq:32 memory:f7a0a000-f7a0a00f
        *-usb:0
             description: USB controller
             product: 6 Series/C200 Series Chipset Family USB Enhanced Host Controller #2
             vendor: Intel Corporation
             physical id: 1a
             bus info: pci@0000:00:1a.0
             version: 05
             width: 32 bits
             clock: 33MHz
             capabilities: pm debug ehci bus_master cap_list
             configuration: driver=ehci-pci latency=0
             resources: irq:16 memory:f7a08000-f7a083ff
           *-usbhost
                product: EHCI Host Controller
                vendor: Linux 6.14.0-34-generic ehci_hcd
                physical id: 1
                bus info: usb@4
                logical name: usb4
                version: 6.14
                capabilities: usb-2.00
                configuration: driver=hub slots=2 speed=480Mbit/s
              *-usb
                   description: USB hub
                   product: Integrated Rate Matching Hub
                   vendor: Intel Corp.
                   physical id: 1
                   bus info: usb@4:1
                   version: 0.00
                   capabilities: usb-2.00
                   configuration: driver=hub slots=4 speed=480Mbit/s
        *-multimedia
             description: Audio device
             product: 6 Series/C200 Series Chipset Family High Definition Audio Controller
             vendor: Intel Corporation
             physical id: 1b
             bus info: pci@0000:00:1b.0
             logical name: card0
             logical name: /dev/snd/controlC0
             logical name: /dev/snd/hwC0D0
             logical name: /dev/snd/pcmC0D0c
             logical name: /dev/snd/pcmC0D0p
             logical name: /dev/snd/pcmC0D1p
             version: 05
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi pciexpress bus_master cap_list
             configuration: driver=snd_hda_intel latency=0
             resources: irq:34 memory:f7a00000-f7a03fff
           *-input:0
                product: HDA Intel PCH Mic
                physical id: 0
                logical name: input12
                logical name: /dev/input/event11
           *-input:1
                product: HDA Intel PCH Line Out
                physical id: 1
                logical name: input13
                logical name: /dev/input/event12
           *-input:2
                product: HDA Intel PCH Headphone
                physical id: 2
                logical name: input14
                logical name: /dev/input/event13
        *-pci:1
             description: PCI bridge
             product: 6 Series/C200 Series Chipset Family PCI Express Root Port 1
             vendor: Intel Corporation
             physical id: 1c
             bus info: pci@0000:00:1c.0
             version: b5
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:16
        *-pci:2
             description: PCI bridge
             product: 6 Series/C200 Series Chipset Family PCI Express Root Port 2
             vendor: Intel Corporation
             physical id: 1c.1
             bus info: pci@0000:00:1c.1
             version: b5
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:17 memory:f7900000-f79fffff
           *-usb
                description: USB controller
                product: ASM1042 SuperSpeed USB Host Controller
                vendor: ASMedia Technology Inc.
                physical id: 0
                bus info: pci@0000:03:00.0
                version: 00
                width: 64 bits
                clock: 33MHz
                capabilities: msi msix pm pciexpress xhci bus_master cap_list
                configuration: driver=xhci_hcd latency=0
                resources: irq:17 memory:f7900000-f7907fff
              *-usbhost:0
                   product: xHCI Host Controller
                   vendor: Linux 6.14.0-34-generic xhci-hcd
                   physical id: 0
                   bus info: usb@1
                   logical name: usb1
                   version: 6.14
                   capabilities: usb-2.00
                   configuration: driver=hub slots=2 speed=480Mbit/s
                 *-usb:0
                      description: Keyboard
                      product: SINO WEALTH Gaming KB  Mouse
                      vendor: SINO WEALTH
                      physical id: 1
                      bus info: usb@1:1
                      logical name: input15
                      logical name: /dev/input/event14
                      logical name: input15::capslock
                      logical name: input15::compose
                      logical name: input15::kana
                      logical name: input15::numlock
                      logical name: input15::scrolllock
                      logical name: input16
                      logical name: /dev/input/event15
                      logical name: input17
                      logical name: /dev/input/event16
                      logical name: input18
                      logical name: /dev/input/event17
                      logical name: input19
                      logical name: /dev/input/event18
                      logical name: /dev/input/mouse1
                      version: 10.04
                      capabilities: usb-1.10 usb
                      configuration: driver=usbhid maxpower=500mA speed=12Mbit/s
                 *-usb:1
                      description: Keyboard
                      product: YICHIP Wireless Device Consumer Control
                      vendor: YICHIP
                      physical id: 2
                      bus info: usb@1:2
                      logical name: input2
                      logical name: /dev/input/event2
                      logical name: input2::capslock
                      logical name: input2::compose
                      logical name: input2::kana
                      logical name: input2::numlock
                      logical name: input2::scrolllock
                      logical name: input3
                      logical name: /dev/input/event3
                      logical name: /dev/input/mouse0
                      logical name: input4
                      logical name: /dev/input/event4
                      logical name: input5
                      logical name: /dev/input/event5
                      version: 0.02
                      serial: b120300001
                      capabilities: usb-2.00 usb
                      configuration: driver=usbhid maxpower=100mA speed=12Mbit/s
              *-usbhost:1
                   product: xHCI Host Controller
                   vendor: Linux 6.14.0-34-generic xhci-hcd
                   physical id: 1
                   bus info: usb@3
                   logical name: usb3
                   version: 6.14
                   capabilities: usb-3.00
                   configuration: driver=hub slots=2 speed=5000Mbit/s
        *-pci:3
             description: PCI bridge
             product: 6 Series/C200 Series Chipset Family PCI Express Root Port 3
             vendor: Intel Corporation
             physical id: 1c.2
             bus info: pci@0000:00:1c.2
             version: b5
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:18 memory:f7800000-f78fffff
           *-network
                description: Wireless interface
                product: AR9485 Wireless Network Adapter
                vendor: Qualcomm Atheros
                physical id: 0
                bus info: pci@0000:04:00.0
                logical name: wlp4s0
                version: 01
                serial: 2c:d0:5a:b0:62:d5
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi pciexpress bus_master cap_list rom ethernet physical wireless
                configuration: broadcast=yes driver=ath9k driverversion=6.14.0-34-generic firmware=N/A ip=192.168.31.36 latency=0 link=yes multicast=yes wireless=IEEE 802.11
                resources: irq:18 memory:f7800000-f787ffff memory:f7880000-f788ffff
        *-pci:4
             description: PCI bridge
             product: 6 Series/C200 Series Chipset Family PCI Express Root Port 4
             vendor: Intel Corporation
             physical id: 1c.3
             bus info: pci@0000:00:1c.3
             version: b5
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:19 ioport:d000(size=4096) ioport:f2100000(size=1048576)
           *-network
                description: Ethernet interface
                product: RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller
                vendor: Realtek Semiconductor Co., Ltd.
                physical id: 0
                bus info: pci@0000:05:00.0
                logical name: enp5s0
                version: 06
                serial: 74:d0:2b:0a:56:d1
                size: 100Mbit/s
                capacity: 1Gbit/s
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi pciexpress msix vpd bus_master cap_list ethernet physical tp mii 10bt 10bt-fd 100bt 100bt-fd 1000bt 1000bt-fd autonegotiation
                configuration: autonegotiation=on broadcast=yes driver=r8169 driverversion=6.14.0-34-generic duplex=full firmware=rtl8168e-3_0.0.4 03/27/12 ip=192.168.31.135 latency=0 link=yes multicast=yes port=twisted pair speed=100Mbit/s
                resources: irq:19 ioport:d000(size=256) memory:f2104000-f2104fff memory:f2100000-f2103fff
        *-usb:1
             description: USB controller
             product: 6 Series/C200 Series Chipset Family USB Enhanced Host Controller #1
             vendor: Intel Corporation
             physical id: 1d
             bus info: pci@0000:00:1d.0
             version: 05
             width: 32 bits
             clock: 33MHz
             capabilities: pm debug ehci bus_master cap_list
             configuration: driver=ehci-pci latency=0
             resources: irq:23 memory:f7a07000-f7a073ff
           *-usbhost
                product: EHCI Host Controller
                vendor: Linux 6.14.0-34-generic ehci_hcd
                physical id: 1
                bus info: usb@2
                logical name: usb2
                version: 6.14
                capabilities: usb-2.00
                configuration: driver=hub slots=2 speed=480Mbit/s
              *-usb
                   description: USB hub
                   product: Integrated Rate Matching Hub
                   vendor: Intel Corp.
                   physical id: 1
                   bus info: usb@2:1
                   version: 0.00
                   capabilities: usb-2.00
                   configuration: driver=hub slots=6 speed=480Mbit/s
                 *-usb:0
                      description: USB hub
                      product: USB Hub
                      vendor: Alcor Micro Corp.
                      physical id: 3
                      bus info: usb@2:1.3
                      version: 1.00
                      capabilities: usb-2.00
                      configuration: driver=hub maxpower=100mA slots=4 speed=480Mbit/s
                    *-usb:0
                         description: Video
                         product: Integrated Camera
                         vendor: 04081-00120600C9V207
                         physical id: 2
                         bus info: usb@2:1.3.2
                         version: 8.31
                         capabilities: usb-2.00
                         configuration: driver=uvcvideo maxpower=500mA speed=480Mbit/s
                    *-usb:1
                         description: Generic USB device
                         product: Microsoft X-Box 360 pad
                         vendor: Microsoft Corp.
                         physical id: 4
                         bus info: usb@2:1.3.4
                         logical name: input9
                         logical name: /dev/input/event8
                         logical name: /dev/input/js0
                         version: 1.01
                         serial: 00000000
                         capabilities: usb-2.00 usb
                         configuration: driver=xpad maxpower=500mA speed=12Mbit/s
                 *-usb:1 UNCLAIMED
                      description: Generic USB device
                      product: Polaris AV Capture
                      vendor: Conexant Systems Inc.
                      physical id: 5
                      bus info: usb@2:1.5
                      version: 40.01
                      serial: 00000000001
                      capabilities: usb-2.00
                      configuration: maxpower=500mA speed=480Mbit/s
        *-isa
             description: ISA bridge
             product: H61 Express Chipset LPC Controller
             vendor: Intel Corporation
             physical id: 1f
             bus info: pci@0000:00:1f.0
             version: 05
             width: 32 bits
             clock: 33MHz
             capabilities: isa bus_master cap_list
             configuration: driver=lpc_ich latency=0
             resources: irq:0
           *-pnp00:00
                product: PnP device PNP0c01
                physical id: 0
                capabilities: pnp
                configuration: driver=system
           *-pnp00:01
                product: PnP device PNP0c02
                physical id: 1
                capabilities: pnp
                configuration: driver=system
           *-pnp00:02
                product: PnP device PNP0b00
                physical id: 2
                capabilities: pnp
                configuration: driver=rtc_cmos
           *-pnp00:03
                product: PnP device PNP0c02
                physical id: 3
                capabilities: pnp
                configuration: driver=system
           *-pnp00:04
                product: PnP device ENE0100
                vendor: ENE Technology Inc.
                physical id: 4
                capabilities: pnp
                configuration: driver=ene_ir
           *-pnp00:05
                product: PnP device PNP0c02
                physical id: 5
                capabilities: pnp
                configuration: driver=system
           *-pnp00:06
                product: PnP device PNP0c01
                physical id: 6
                capabilities: pnp
                configuration: driver=system
        *-sata
             description: SATA controller
             product: 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller
             vendor: Intel Corporation
             physical id: 1f.2
             bus info: pci@0000:00:1f.2
             logical name: scsi0
             logical name: scsi1
             version: 05
             width: 32 bits
             clock: 66MHz
             capabilities: sata msi pm ahci_1.0 bus_master cap_list emulated
             configuration: driver=ahci latency=0
             resources: irq:30 ioport:f0b0(size=8) ioport:f0a0(size=4) ioport:f090(size=8) ioport:f080(size=4) ioport:f060(size=32) memory:f7a06000-f7a067ff
           *-cdrom
                description: DVD-RAM writer
                product: DVD A  DS8A9SH
                vendor: Slimtype
                physical id: 0
                bus info: scsi@0:0.0.0
                logical name: /dev/cdrom
                logical name: /dev/sr0
                version: EAA2
                capabilities: removable audio cd-r cd-rw dvd dvd-r dvd-ram
                configuration: ansiversion=5 status=nodisc
           *-disk
                description: ATA Disk
                product: WDC WD10EZEX-22R
                vendor: Western Digital
                physical id: 1
                bus info: scsi@1:0.0.0
                logical name: /dev/sda
                version: 0A80
                serial: WD-WMC1S2135639
                size: 931GiB (1TB)
                capabilities: gpt-1.00 partitioned partitioned:gpt
                configuration: ansiversion=5 guid=fa1a6736-68aa-48ba-95b0-b6dd746eb452 logicalsectorsize=512 sectorsize=4096
              *-volume:0
                   description: Windows FAT volume
                   vendor: mkfs.fat
                   physical id: 1
                   bus info: scsi@1:0.0.0,1
                   logical name: /dev/sda1
                   logical name: /boot/efi
                   version: FAT32
                   serial: bd5a-74a1
                   size: 510MiB
                   capacity: 511MiB
                   capabilities: boot fat initialized
                   configuration: FATs=2 filesystem=fat mount.fstype=vfat mount.options=rw,relatime,fmask=0077,dmask=0077,codepage=437,iocharset=iso8859-1,shortname=mixed,errors=remount-ro name=EFI System Partition state=mounted
              *-volume:1
                   description: EXT4 volume
                   vendor: Linux
                   physical id: 2
                   bus info: scsi@1:0.0.0,2
                   logical name: /dev/sda2
                   logical name: /
                   version: 1.0
                   serial: 27d2987d-96ab-4bce-a113-236fead4b398
                   size: 931GiB
                   capabilities: journaled extended_attributes large_files huge_files dir_nlink recover 64bit extents ext4 ext2 initialized
                   configuration: created=2025-11-04 00:17:09 filesystem=ext4 lastmountpoint=/ modified=2025-11-21 22:09:40 mount.fstype=ext4 mount.options=rw,relatime,errors=remount-ro mounted=2025-11-21 22:09:45 state=mounted
        *-serial
             description: SMBus
             product: 6 Series/C200 Series Chipset Family SMBus Controller
             vendor: Intel Corporation
             physical id: 1f.3
             bus info: pci@0000:00:1f.3
             version: 05
             width: 64 bits
             clock: 33MHz
             configuration: driver=i801_smbus latency=0
             resources: irq:18 memory:f7a05000-f7a050ff ioport:f040(size=32)
  *-power UNCLAIMED
       description: To Be Filled By O.E.M.
       product: To Be Filled By O.E.M.
       vendor: To Be Filled By O.E.M.
       physical id: 1
       version: To Be Filled By O.E.M.
       serial: To Be Filled By O.E.M.
       capacity: 32768mWh
  *-input:0
       product: Power Button
       physical id: 2
       logical name: input0
       logical name: /dev/input/event0
       capabilities: platform
  *-input:1
       product: Power Button
       physical id: 3
       logical name: input1
       logical name: /dev/input/event1
       capabilities: platform
  *-input:2
       product: Video Bus
       physical id: 4
       logical name: input10
       logical name: /dev/input/event9
       capabilities: platform
  *-input:3
       product: Video Bus
       physical id: 5
       logical name: input11
       logical name: /dev/input/event10
       capabilities: platform
  *-input:4
       product: ENE eHome Infrared Remote Receiver
       physical id: 6
       logical name: input7
       logical name: /dev/input/event6
  *-input:5
       product: Eee PC WMI hotkeys
       physical id: 7
       logical name: input8
       logical name: /dev/input/event7
       capabilities: platform
```

