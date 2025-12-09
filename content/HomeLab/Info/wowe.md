# 🖥 System Inventory Report
Generated: Fri Nov 21 05:55:38 PM UTC 2025
Host: wowe


# General System Info

```
# dmidecode 3.5
Getting SMBIOS data from sysfs.
SMBIOS 3.2.0 present.

Handle 0x0001, DMI type 1, 27 bytes
System Information
        Manufacturer: Default string
        Product Name: GB3B
        Version: Default string
        Serial Number: AG402A3103000061
        UUID: e277f580-81f0-11ed-be12-aea745821c00
        Wake-up Type: Power Switch
        SKU Number: SKU1
        Family: MiniPC

```


# CPU

```
Architecture:                         x86_64
CPU op-mode(s):                       32-bit, 64-bit
Address sizes:                        39 bits physical, 48 bits virtual
Byte Order:                           Little Endian
CPU(s):                               2
On-line CPU(s) list:                  0,1
Vendor ID:                            GenuineIntel
BIOS Vendor ID:                       Intel
Model name:                           Intel(R) Celeron(R) N4020 CPU @ 1.10GHz
BIOS Model name:                      Intel(R) Celeron(R) N4020 CPU @ 1.10GHz Fill By OEM CPU @ 1.1GHz
BIOS CPU family:                      15
CPU family:                           6
Model:                                122
Thread(s) per core:                   1
Core(s) per socket:                   2
Socket(s):                            1
Stepping:                             8
CPU(s) scaling MHz:                   98%
CPU max MHz:                          2800.0000
CPU min MHz:                          800.0000
BogoMIPS:                             2188.80
Flags:                                fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg cx16 xtpr pdcm sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave rdrand lahf_lm 3dnowprefetch cpuid_fault cat_l2 cdp_l2 ssbd ibrs ibpb stibp ibrs_enhanced tpr_shadow flexpriority ept vpid ept_ad fsgsbase tsc_adjust smep erms mpx rdt_a rdseed smap clflushopt intel_pt sha_ni xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts vnmi umip rdpid md_clear arch_capabilities
Virtualization:                       VT-x
L1d cache:                            48 KiB (2 instances)
L1i cache:                            64 KiB (2 instances)
L2 cache:                             4 MiB (1 instance)
NUMA node(s):                         1
NUMA node0 CPU(s):                    0,1
Vulnerability Gather data sampling:   Not affected
Vulnerability Itlb multihit:          Not affected
Vulnerability L1tf:                   Not affected
Vulnerability Mds:                    Not affected
Vulnerability Meltdown:               Not affected
Vulnerability Mmio stale data:        Not affected
Vulnerability Reg file data sampling: Mitigation; Clear Register File
Vulnerability Retbleed:               Not affected
Vulnerability Spec rstack overflow:   Not affected
Vulnerability Spec store bypass:      Mitigation; Speculative Store Bypass disabled via prctl
Vulnerability Spectre v1:             Mitigation; usercopy/swapgs barriers and __user pointer sanitization
Vulnerability Spectre v2:             Mitigation; Enhanced / Automatic IBRS; IBPB conditional; RSB filling; PBRSB-eIBRS Not affected; BHI SW loop, KVM SW loop
Vulnerability Srbds:                  Not affected
Vulnerability Tsx async abort:        Not affected
Vulnerability Vmscape:                Not affected
```


# Memory

```
# dmidecode 3.5
Getting SMBIOS data from sysfs.
SMBIOS 3.2.0 present.

Handle 0x0008, DMI type 16, 23 bytes
Physical Memory Array
        Location: System Board Or Motherboard
        Use: System Memory
        Error Correction Type: None
        Maximum Capacity: 64 GB
        Error Information Handle: Not Provided
        Number Of Devices: 4

Handle 0x000A, DMI type 17, 84 bytes
Memory Device
        Array Handle: 0x0008
        Error Information Handle: Not Provided
        Total Width: 16 bits
        Data Width: 16 bits
        Size: 4 GB
        Form Factor: DIMM
        Set: None
        Locator: A1_DIMM0
        Bank Locator: A1_BANK0
        Type: DDR4
        Type Detail: Synchronous
        Speed: 2133 MT/s
        Manufacturer: ABCD
        Serial Number: 1234
        Asset Tag: 9876543210
        Part Number: 123456789012345678
        Rank: Unknown
        Configured Memory Speed: 2133 MT/s
        Minimum Voltage: 1.1 V
        Maximum Voltage: 1.1 V
        Configured Voltage: 1.2 V
        Memory Technology: DRAM
        Memory Operating Mode Capability: Volatile memory
        Firmware Version: Not Specified
        Module Manufacturer ID: Unknown
        Module Product ID: Unknown
        Memory Subsystem Controller Manufacturer ID: Unknown
        Memory Subsystem Controller Product ID: Unknown
        Non-Volatile Size: None
        Volatile Size: 4 GB
        Cache Size: None
        Logical Size: None

Handle 0x000C, DMI type 17, 84 bytes
Memory Device
        Array Handle: 0x0008
        Error Information Handle: Not Provided
        Total Width: Unknown
        Data Width: 64 bits
        Size: No Module Installed
        Form Factor: Unknown
        Set: None
        Locator: A1_DIMM1
        Bank Locator: A1_BANK1
        Type: Unknown
        Type Detail: Synchronous

Handle 0x000E, DMI type 17, 84 bytes
Memory Device
        Array Handle: 0x0008
        Error Information Handle: Not Provided
        Total Width: Unknown
        Data Width: 64 bits
        Size: No Module Installed
        Form Factor: Unknown
        Set: None
        Locator: A1_DIMM2
        Bank Locator: A1_BANK2
        Type: Unknown
        Type Detail: Synchronous

Handle 0x0010, DMI type 17, 84 bytes
Memory Device
        Array Handle: 0x0008
        Error Information Handle: Not Provided
        Total Width: Unknown
        Data Width: 64 bits
        Size: No Module Installed
        Form Factor: Unknown
        Set: None
        Locator: A1_DIMM3
        Bank Locator: A1_BANK3
        Type: Unknown
        Type Detail: Synchronous

```


# PCI Devices

```
00:00.0 Host bridge [0600]: Intel Corporation Gemini Lake Host Bridge [8086:31f0] (rev 06)
00:00.1 Signal processing controller [1180]: Intel Corporation Celeron/Pentium Silver Processor Dynamic Platform and Thermal Framework Processor Participant [8086:318c] (rev 06)
00:02.0 VGA compatible controller [0300]: Intel Corporation GeminiLake [UHD Graphics 600] [8086:3185] (rev 06)
00:0e.0 Multimedia audio controller [0401]: Intel Corporation Celeron/Pentium Silver Processor High Definition Audio [8086:3198] (rev 06)
00:0f.0 Communication controller [0780]: Intel Corporation Celeron/Pentium Silver Processor Trusted Execution Engine Interface [8086:319a] (rev 06)
00:12.0 SATA controller [0106]: Intel Corporation Celeron/Pentium Silver Processor SATA Controller [8086:31e3] (rev 06)
00:13.0 PCI bridge [0604]: Intel Corporation Gemini Lake PCI Express Root Port [8086:31d8] (rev f6)
00:13.1 PCI bridge [0604]: Intel Corporation Gemini Lake PCI Express Root Port [8086:31d9] (rev f6)
00:13.2 PCI bridge [0604]: Intel Corporation Gemini Lake PCI Express Root Port [8086:31da] (rev f6)
00:14.0 PCI bridge [0604]: Intel Corporation Gemini Lake PCI Express Root Port [8086:31d6] (rev f6)
00:14.1 PCI bridge [0604]: Intel Corporation Gemini Lake PCI Express Root Port [8086:31d7] (rev f6)
00:15.0 USB controller [0c03]: Intel Corporation Celeron/Pentium Silver Processor USB 3.0 xHCI Controller [8086:31a8] (rev 06)
00:16.0 Signal processing controller [1180]: Intel Corporation Celeron/Pentium Silver Processor I2C 0 [8086:31ac] (rev 06)
00:16.3 Signal processing controller [1180]: Intel Corporation Celeron/Pentium Silver Processor I2C 3 [8086:31b2] (rev 06)
00:1c.0 SD Host controller [0805]: Intel Corporation Celeron/Pentium Silver Processor SDA Standard Compliant SD Host Controller [8086:31cc] (rev 06)
00:1f.0 ISA bridge [0601]: Intel Corporation Celeron/Pentium Silver Processor LPC Controller [8086:31e8] (rev 06)
00:1f.1 SMBus [0c05]: Intel Corporation Celeron/Pentium Silver Processor Gaussian Mixture Model [8086:31d4] (rev 06)
01:00.0 Network controller [0280]: Realtek Semiconductor Co., Ltd. RTL8822CE 802.11ac PCIe Wireless Network Adapter [10ec:c822]
02:00.0 Ethernet controller [0200]: Realtek Semiconductor Co., Ltd. RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller [10ec:8168] (rev 15)
```


# USB Devices

```
/:  Bus 001.Port 001: Dev 001, Class=root_hub, Driver=xhci_hcd/9p, 480M
    |__ Port 003: Dev 002, If 0, Class=Human Interface Device, Driver=usbhid, 12M
    |__ Port 004: Dev 003, If 0, Class=Human Interface Device, Driver=usbhid, 1.5M
    |__ Port 004: Dev 003, If 1, Class=Human Interface Device, Driver=usbhid, 1.5M
    |__ Port 006: Dev 004, If 0, Class=Vendor Specific Class, Driver=rtsx_usb, 480M
    |__ Port 007: Dev 005, If 0, Class=Wireless, Driver=btusb, 12M
    |__ Port 007: Dev 005, If 1, Class=Wireless, Driver=btusb, 12M
/:  Bus 002.Port 001: Dev 001, Class=root_hub, Driver=xhci_hcd/7p, 5000M
```


# USB List

```
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 001 Device 002: ID 046a:b103 CHERRY USB Device
Bus 001 Device 003: ID 04ca:0050 Lite-On Technology Corp. USB Multimedia Keyboard
Bus 001 Device 004: ID 0bda:0129 Realtek Semiconductor Corp. RTS5129 Card Reader Controller
Bus 001 Device 005: ID 13d3:3553 IMC Networks Bluetooth Radio
Bus 002 Device 001: ID 1d6b:0003 Linux Foundation 3.0 root hub
```


# Network Info

```
```


# IP Interfaces

```
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute
       valid_lft forever preferred_lft forever
2: enp2s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 84:47:09:17:b9:45 brd ff:ff:ff:ff:ff:ff
    inet 192.168.31.131/24 metric 100 brd 192.168.31.255 scope global dynamic enp2s0
       valid_lft 34189sec preferred_lft 34189sec
    inet6 fe80::8647:9ff:fe17:b945/64 scope link
       valid_lft forever preferred_lft forever
3: wlp1s0: <BROADCAST,MULTICAST> mtu 1500 qdisc noop state DOWN group default qlen 1000
    link/ether 48:e7:da:07:4b:b3 brd ff:ff:ff:ff:ff:ff
4: tailscale0: <POINTOPOINT,MULTICAST,NOARP,UP,LOWER_UP> mtu 1280 qdisc fq_codel state UNKNOWN group default qlen 500
    link/none
    inet 100.78.142.88/32 scope global tailscale0
       valid_lft forever preferred_lft forever
    inet6 fd7a:115c:a1e0::2101:8e65/128 scope global
       valid_lft forever preferred_lft forever
    inet6 fe80::b08d:4ee1:8d0e:5fa1/64 scope link stable-privacy
       valid_lft forever preferred_lft forever
5: ztks5shfaa: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 2800 qdisc fq_codel state UNKNOWN group default qlen 1000
    link/ether 6e:2e:9b:4a:e7:70 brd ff:ff:ff:ff:ff:ff
    inet 10.147.19.169/24 brd 10.147.19.255 scope global ztks5shfaa
       valid_lft forever preferred_lft forever
    inet6 fe80::6c2e:9bff:fe4a:e770/64 scope link
       valid_lft forever preferred_lft forever
6: br-201172fe7ccd: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN group default
    link/ether 26:dc:38:5b:5c:b8 brd ff:ff:ff:ff:ff:ff
    inet 172.18.0.1/16 brd 172.18.255.255 scope global br-201172fe7ccd
       valid_lft forever preferred_lft forever
7: docker0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc noqueue state DOWN group default
    link/ether 36:d4:35:fa:71:56 brd ff:ff:ff:ff:ff:ff
    inet 172.17.0.1/16 brd 172.17.255.255 scope global docker0
       valid_lft forever preferred_lft forever
8: vxlan.calico: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1450 qdisc noqueue state UNKNOWN group default qlen 1000
    link/ether 66:14:47:b4:33:8d brd ff:ff:ff:ff:ff:ff
    inet 10.1.115.0/32 scope global vxlan.calico
       valid_lft forever preferred_lft forever
    inet6 fe80::6414:47ff:feb4:338d/64 scope link
       valid_lft forever preferred_lft forever
11: cali5c46266cbd0@if2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1450 qdisc noqueue state UP group default qlen 1000
    link/ether ee:ee:ee:ee:ee:ee brd ff:ff:ff:ff:ff:ff link-netns cni-f67720aa-cf40-d20e-997c-2805979e0de0
    inet6 fe80::ecee:eeff:feee:eeee/64 scope link
       valid_lft forever preferred_lft forever
12: cali18cf73a794d@if2: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1450 qdisc noqueue state UP group default qlen 1000
    link/ether ee:ee:ee:ee:ee:ee brd ff:ff:ff:ff:ff:ff link-netns cni-00939a1b-48e7-cd9a-4e9d-a9458c55bbb3
    inet6 fe80::ecee:eeff:feee:eeee/64 scope link
       valid_lft forever preferred_lft forever
```


# Sensors

```
```


# Storage (lsblk)

```
NAME                        SIZE TYPE MOUNTPOINT          FSTYPE      MODEL
loop0                      63.8M loop /snap/core20/2682   squashfs
loop1                        71M loop /snap/prometheus/86 squashfs
loop2                     164.3M loop /snap/microk8s/8511 squashfs
loop3                      50.9M loop /snap/snapd/25577   squashfs
sda                       447.1G disk                                 ADATA SU650
├─sda1                        1G part /boot/efi           vfat
├─sda2                        2G part /boot               ext4
└─sda3                    444.1G part                     LVM2_member
  └─ubuntu--vg-ubuntu--lv   100G lvm  /                   ext4
mmcblk0                   116.5G disk
├─mmcblk0p1                 300M part                     vfat
└─mmcblk0p2               116.2G part                     ext4
mmcblk0boot0                  4M disk
mmcblk0boot1                  4M disk
```


# SMART: /dev/loop0

```
```


# SMART: /dev/loop1

```
```


# SMART: /dev/loop2

```
```


# SMART: /dev/loop3

```
```


# SMART: /dev/sda

```
```


# SMART: /dev/mmcblk0

```
```


# SMART: /dev/mmcblk0boot0

```
```


# SMART: /dev/mmcblk0boot1

```
```


# Display EDID

```
```


# DMIDecode (full)

```
# dmidecode 3.5
Getting SMBIOS data from sysfs.
SMBIOS 3.2.0 present.
Table at 0x79859000.

Handle 0x0000, DMI type 0, 26 bytes
BIOS Information
        Vendor: American Megatrends Inc.
        Version: GB3B 0.04
        Release Date: 10/19/2022
        Address: 0xF0000
        Runtime Size: 64 kB
        ROM Size: 4416 kB
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
                Serial services are supported (int 14h)
                Printer services are supported (int 17h)
                ACPI is supported
                USB legacy is supported
                BIOS boot specification is supported
                Targeted content distribution is supported
                UEFI is supported
        BIOS Revision: 0.4

Handle 0x0001, DMI type 1, 27 bytes
System Information
        Manufacturer: Default string
        Product Name: GB3B
        Version: Default string
        Serial Number: AG402A3103000061
        UUID: e277f580-81f0-11ed-be12-aea745821c00
        Wake-up Type: Power Switch
        SKU Number: SKU1
        Family: MiniPC

Handle 0x0002, DMI type 2, 15 bytes
Base Board Information
        Manufacturer: Default string
        Product Name: GB3B
        Version: Default string
        Serial Number: GB3B09112B05H1015
        Asset Tag: Default string
        Features:
                Board is a hosting board
                Board is replaceable
        Location In Chassis: Default string
        Chassis Handle: 0x0003
        Type: Motherboard
        Contained Object Handles: 0

Handle 0x0003, DMI type 3, 22 bytes
Chassis Information
        Manufacturer: Default string
        Type: Mini PC
        Lock: Not Present
        Version: Default string
        Serial Number: Default string
        Asset Tag: Default string
        Boot-up State: Safe
        Power Supply State: Safe
        Thermal State: Safe
        Security Status: None
        OEM Information: 0x00000000
        Height: Unspecified
        Number Of Power Cords: 1
        Contained Elements: 0
        SKU Number: Default string

Handle 0x0008, DMI type 16, 23 bytes
Physical Memory Array
        Location: System Board Or Motherboard
        Use: System Memory
        Error Correction Type: None
        Maximum Capacity: 64 GB
        Error Information Handle: Not Provided
        Number Of Devices: 4

Handle 0x0009, DMI type 19, 31 bytes
Memory Array Mapped Address
        Starting Address: 0x00000000000
        Ending Address: 0x000FFFFFFFF
        Range Size: 4 GB
        Physical Array Handle: 0x0008
        Partition Width: 1

Handle 0x000A, DMI type 17, 84 bytes
Memory Device
        Array Handle: 0x0008
        Error Information Handle: Not Provided
        Total Width: 16 bits
        Data Width: 16 bits
        Size: 4 GB
        Form Factor: DIMM
        Set: None
        Locator: A1_DIMM0
        Bank Locator: A1_BANK0
        Type: DDR4
        Type Detail: Synchronous
        Speed: 2133 MT/s
        Manufacturer: ABCD
        Serial Number: 1234
        Asset Tag: 9876543210
        Part Number: 123456789012345678
        Rank: Unknown
        Configured Memory Speed: 2133 MT/s
        Minimum Voltage: 1.1 V
        Maximum Voltage: 1.1 V
        Configured Voltage: 1.2 V
        Memory Technology: DRAM
        Memory Operating Mode Capability: Volatile memory
        Firmware Version: Not Specified
        Module Manufacturer ID: Unknown
        Module Product ID: Unknown
        Memory Subsystem Controller Manufacturer ID: Unknown
        Memory Subsystem Controller Product ID: Unknown
        Non-Volatile Size: None
        Volatile Size: 4 GB
        Cache Size: None
        Logical Size: None

Handle 0x000B, DMI type 20, 35 bytes
Memory Device Mapped Address
        Starting Address: 0x00000000000
        Ending Address: 0x000FFFFFFFF
        Range Size: 4 GB
        Physical Device Handle: 0x000A
        Memory Array Mapped Address Handle: 0x0009
        Partition Row Position: Unknown
        Interleave Position: 1
        Interleaved Data Depth: 4

Handle 0x000C, DMI type 17, 84 bytes
Memory Device
        Array Handle: 0x0008
        Error Information Handle: Not Provided
        Total Width: Unknown
        Data Width: 64 bits
        Size: No Module Installed
        Form Factor: Unknown
        Set: None
        Locator: A1_DIMM1
        Bank Locator: A1_BANK1
        Type: Unknown
        Type Detail: Synchronous

Handle 0x000E, DMI type 17, 84 bytes
Memory Device
        Array Handle: 0x0008
        Error Information Handle: Not Provided
        Total Width: Unknown
        Data Width: 64 bits
        Size: No Module Installed
        Form Factor: Unknown
        Set: None
        Locator: A1_DIMM2
        Bank Locator: A1_BANK2
        Type: Unknown
        Type Detail: Synchronous

Handle 0x0010, DMI type 17, 84 bytes
Memory Device
        Array Handle: 0x0008
        Error Information Handle: Not Provided
        Total Width: Unknown
        Data Width: 64 bits
        Size: No Module Installed
        Form Factor: Unknown
        Set: None
        Locator: A1_DIMM3
        Bank Locator: A1_BANK3
        Type: Unknown
        Type Detail: Synchronous

Handle 0x0015, DMI type 7, 27 bytes
Cache Information
        Socket Designation: CPU Internal L1
        Configuration: Enabled, Not Socketed, Level 1
        Operational Mode: Write Back
        Location: Internal
        Installed Size: 1600 GB
        Maximum Size: 1648 GB
        Supported SRAM Types:
                Synchronous
        Installed SRAM Type: Synchronous
        Speed: Unknown
        Error Correction Type: Parity
        System Type: Other
        Associativity: Other

Handle 0x0016, DMI type 7, 27 bytes
Cache Information
        Socket Designation: CPU Internal L2
        Configuration: Enabled, Not Socketed, Level 2
        Operational Mode: Write Back
        Location: Internal
        Installed Size: 6720 MB
        Maximum Size: 320 GB
        Supported SRAM Types:
                Synchronous
        Installed SRAM Type: Synchronous
        Speed: Unknown
        Error Correction Type: Single-bit ECC
        System Type: Unified
        Associativity: 16-way Set-associative

Handle 0x0017, DMI type 4, 48 bytes
Processor Information
        Socket Designation: SOCKET 0
        Type: Central Processor
        Family: Celeron
        Manufacturer: Intel
        ID: A8 06 07 00 FF FB EB BF
        Signature: Type 0, Family 6, Model 122, Stepping 8
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
        Version: Intel(R) Celeron(R) N4020 CPU @ 1.10GHz
        Voltage: 1.2 V
        External Clock: 100 MHz
        Max Speed: 2700 MHz
        Current Speed: 1100 MHz
        Status: Populated, Enabled
        Upgrade: Other
        L1 Cache Handle: 0x0015
        L2 Cache Handle: 0x0016
        L3 Cache Handle: Not Provided
        Serial Number: Not Specified
        Asset Tag: Fill By OEM
        Part Number: Fill By OEM
        Core Count: 2
        Core Enabled: 2
        Thread Count: 2
        Characteristics:
                64-bit capable

Handle 0x0018, DMI type 9, 19 bytes
System Slot Information
        Designation: J7H1
        Type: x4 PCI Express 2 x4
        Current Usage: In Use
        Length: Short
        ID: 0
        Characteristics:
                3.3 V is provided
                Opening is shared
                PME signal is supported
        Bus Address: 0000:00:13.0
        Data Bus Width: 10
        Peer Devices: 0

Handle 0x0019, DMI type 9, 19 bytes
System Slot Information
        Designation: J8H1
        Type: x2 PCI Express 2 x2
        Current Usage: In Use
        Length: Short
        ID: 1
        Characteristics:
                3.3 V is provided
                Opening is shared
                PME signal is supported
        Bus Address: 0000:00:14.0
        Data Bus Width: 9
        Peer Devices: 0

Handle 0x001A, DMI type 127, 4 bytes
End Of Table

```


# LSHW (full)

```
wowe
    description: Mini PC
    product: GB3B (SKU1)
    vendor: Default string
    version: Default string
    serial: AG402A3103000061
    width: 64 bits
    capabilities: smbios-3.2.0 dmi-3.2.0 smp vsyscall32
    configuration: chassis=mini family=MiniPC sku=SKU1 uuid=e277f580-81f0-11ed-be12-aea745821c00
  *-core
       description: Motherboard
       product: GB3B
       vendor: Default string
       physical id: 0
       version: Default string
       serial: GB3B09112B05H1015
       slot: Default string
     *-firmware
          description: BIOS
          vendor: American Megatrends Inc.
          physical id: 0
          version: GB3B 0.04
          date: 10/19/2022
          size: 64KiB
          capacity: 4416KiB
          capabilities: pci upgrade shadowing cdboot bootselect socketedrom edd int13floppy1200 int13floppy720 int13floppy2880 int5printscreen int14serial int17printer acpi usb biosbootspecification uefi
     *-memory
          description: System Memory
          physical id: 8
          slot: System board or motherboard
          size: 4GiB
        *-bank:0
             description: DIMM DDR4 Synchronous 2133 MHz (0.5 ns)
             product: 123456789012345678
             vendor: ABCD
             physical id: 0
             serial: 1234
             slot: A1_DIMM0
             size: 4GiB
             width: 16 bits
             clock: 2133MHz (0.5ns)
        *-bank:1
             description: Synchronous [empty]
             product: Array1_PartNumber1
             vendor: A1_Manufacturer1
             physical id: 1
             serial: A1_SerNum1
             slot: A1_DIMM1
        *-bank:2
             description: Synchronous [empty]
             product: Array1_PartNumber2
             vendor: A1_Manufacturer2
             physical id: 2
             serial: A1_SerNum2
             slot: A1_DIMM2
        *-bank:3
             description: Synchronous [empty]
             product: Array1_PartNumber3
             vendor: A1_Manufacturer3
             physical id: 3
             serial: A1_SerNum3
             slot: A1_DIMM3
     *-cache:0
          description: L1 cache
          physical id: 15
          slot: CPU Internal L1
          size: 112KiB
          capacity: 112KiB
          capabilities: synchronous internal write-back
          configuration: level=1
     *-cache:1
          description: L2 cache
          physical id: 16
          slot: CPU Internal L2
          size: 4MiB
          capacity: 4MiB
          capabilities: synchronous internal write-back unified
          configuration: level=2
     *-cpu
          description: CPU
          product: Intel(R) Celeron(R) N4020 CPU @ 1.10GHz
          vendor: Intel Corp.
          physical id: 17
          bus info: cpu@0
          version: 6.122.8
          slot: SOCKET 0
          size: 2740MHz
          capacity: 2800MHz
          width: 64 bits
          clock: 100MHz
          capabilities: lm fpu fpu_exception wp vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp x86-64 constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg cx16 xtpr pdcm sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave rdrand lahf_lm 3dnowprefetch cpuid_fault cat_l2 cdp_l2 ssbd ibrs ibpb stibp ibrs_enhanced tpr_shadow flexpriority ept vpid ept_ad fsgsbase tsc_adjust smep erms mpx rdt_a rdseed smap clflushopt intel_pt sha_ni xsaveopt xsavec xgetbv1 xsaves dtherm ida arat pln pts vnmi umip rdpid md_clear arch_capabilities cpufreq
          configuration: cores=2 enabledcores=2 microcode=38 threads=2
     *-pci
          description: Host bridge
          product: Gemini Lake Host Bridge
          vendor: Intel Corporation
          physical id: 100
          bus info: pci@0000:00:00.0
          version: 06
          width: 32 bits
          clock: 33MHz
        *-generic:0 UNCLAIMED
             description: Signal processing controller
             product: Celeron/Pentium Silver Processor Dynamic Platform and Thermal Framework Processor Participant
             vendor: Intel Corporation
             physical id: 0.1
             bus info: pci@0000:00:00.1
             version: 06
             width: 64 bits
             clock: 33MHz
             capabilities: pm cap_list
             configuration: latency=0
             resources: memory:80000000-80007fff
        *-display
             description: VGA compatible controller
             product: GeminiLake [UHD Graphics 600]
             vendor: Intel Corporation
             physical id: 2
             bus info: pci@0000:00:02.0
             version: 06
             width: 64 bits
             clock: 33MHz
             capabilities: pciexpress msi pm vga_controller bus_master cap_list rom
             configuration: driver=i915 latency=0
             resources: irq:134 memory:c0000000-c0ffffff memory:b0000000-bfffffff ioport:f000(size=64) memory:c0000-dffff
        *-multimedia
             description: Multimedia audio controller
             product: Celeron/Pentium Silver Processor High Definition Audio
             vendor: Intel Corporation
             physical id: e
             bus info: pci@0000:00:0e.0
             logical name: card0
             logical name: /dev/snd/controlC0
             logical name: /dev/snd/hwC0D2
             logical name: /dev/snd/pcmC0D0c
             logical name: /dev/snd/pcmC0D0p
             logical name: /dev/snd/pcmC0D5p
             logical name: /dev/snd/pcmC0D6p
             logical name: /dev/snd/pcmC0D7p
             version: 06
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi pciexpress bus_master cap_list
             configuration: driver=sof-audio-pci-intel-apl latency=0
             resources: iomemory:7f0-7ef iomemory:7f0-7ef irq:136 memory:7ffff00000-7ffff03fff memory:7fffe00000-7fffefffff
        *-communication
             description: Communication controller
             product: Celeron/Pentium Silver Processor Trusted Execution Engine Interface
             vendor: Intel Corporation
             physical id: f
             bus info: pci@0000:00:0f.0
             version: 06
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi bus_master cap_list
             configuration: driver=mei_me latency=0
             resources: irq:132 memory:c1216000-c1216fff
        *-sata
             description: SATA controller
             product: Celeron/Pentium Silver Processor SATA Controller
             vendor: Intel Corporation
             physical id: 12
             bus info: pci@0000:00:12.0
             logical name: scsi0
             version: 06
             width: 32 bits
             clock: 66MHz
             capabilities: sata msi pm ahci_1.0 bus_master cap_list emulated
             configuration: driver=ahci latency=0
             resources: irq:127 memory:c1210000-c1211fff memory:c1215000-c12150ff ioport:f090(size=8) ioport:f080(size=4) ioport:f060(size=32) memory:c1214000-c12147ff
           *-disk
                description: ATA Disk
                product: ADATA SU650
                physical id: 0.0.0
                bus info: scsi@0:0.0.0
                logical name: /dev/sda
                version: 3C0F
                serial: 2M4429AJESCT
                size: 447GiB (480GB)
                capabilities: gpt-1.00 partitioned partitioned:gpt
                configuration: ansiversion=5 guid=9287f6d1-5f67-4387-a3d4-e0c255b78ddd logicalsectorsize=512 sectorsize=512
              *-volume:0
                   description: Windows FAT volume
                   vendor: mkfs.fat
                   physical id: 1
                   bus info: scsi@0:0.0.0,1
                   logical name: /dev/sda1
                   logical name: /boot/efi
                   version: FAT32
                   serial: cb44-a14b
                   size: 1073MiB
                   capacity: 1074MiB
                   capabilities: boot fat initialized
                   configuration: FATs=2 filesystem=fat mount.fstype=vfat mount.options=rw,relatime,fmask=0022,dmask=0022,codepage=437,iocharset=iso8859-1,shortname=mixed,errors=remount-ro state=mounted
              *-volume:1
                   description: EXT4 volume
                   vendor: Linux
                   physical id: 2
                   bus info: scsi@0:0.0.0,2
                   logical name: /dev/sda2
                   logical name: /boot
                   version: 1.0
                   serial: 74b77668-1ddf-4dc8-baff-be3fedc183c3
                   size: 2GiB
                   capabilities: journaled extended_attributes large_files huge_files dir_nlink recover 64bit extents ext4 ext2 initialized
                   configuration: created=2025-11-09 13:52:54 filesystem=ext4 lastmountpoint=/boot modified=2025-11-21 15:25:20 mount.fstype=ext4 mount.options=rw,relatime mounted=2025-11-21 15:25:20 state=mounted
              *-volume:2
                   description: EFI partition
                   physical id: 3
                   bus info: scsi@0:0.0.0,3
                   logical name: /dev/sda3
                   serial: LOF1cZ-GNea-RrGb-eeNd-cFAi-xhWV-y8D5D4
                   size: 444GiB
                   capabilities: lvm2
        *-pci:0
             description: PCI bridge
             product: Gemini Lake PCI Express Root Port
             vendor: Intel Corporation
             physical id: 13
             bus info: pci@0000:00:13.0
             version: f6
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:122 ioport:e000(size=4096) memory:c1100000-c11fffff
           *-network DISABLED
                description: Wireless interface
                product: RTL8822CE 802.11ac PCIe Wireless Network Adapter
                vendor: Realtek Semiconductor Co., Ltd.
                physical id: 0
                bus info: pci@0000:01:00.0
                logical name: wlp1s0
                version: 00
                serial: 48:e7:da:07:4b:b3
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi pciexpress bus_master cap_list ethernet physical wireless
                configuration: broadcast=yes driver=rtw_8822ce driverversion=6.8.0-87-generic firmware=N/A latency=0 link=no multicast=yes wireless=IEEE 802.11
                resources: irq:135 ioport:e000(size=256) memory:c1100000-c110ffff
        *-pci:1
             description: PCI bridge
             product: Gemini Lake PCI Express Root Port
             vendor: Intel Corporation
             physical id: 13.1
             bus info: pci@0000:00:13.1
             version: f6
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:123 ioport:d000(size=4096) memory:c1000000-c10fffff
           *-network
                description: Ethernet interface
                product: RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller
                vendor: Realtek Semiconductor Co., Ltd.
                physical id: 0
                bus info: pci@0000:02:00.0
                logical name: enp2s0
                version: 15
                serial: 84:47:09:17:b9:45
                size: 100Mbit/s
                capacity: 1Gbit/s
                width: 64 bits
                clock: 33MHz
                capabilities: pm msi pciexpress msix bus_master cap_list ethernet physical tp mii 10bt 10bt-fd 100bt 100bt-fd 1000bt-fd autonegotiation
                configuration: autonegotiation=on broadcast=yes driver=r8169 driverversion=6.8.0-87-generic duplex=full firmware=rtl8168h-2_0.0.2 02/26/15 ip=192.168.31.131 latency=0 link=yes multicast=yes port=twisted pair speed=100Mbit/s
                resources: irq:23 ioport:d000(size=256) memory:c1004000-c1004fff memory:c1000000-c1003fff
        *-pci:2
             description: PCI bridge
             product: Gemini Lake PCI Express Root Port
             vendor: Intel Corporation
             physical id: 13.2
             bus info: pci@0000:00:13.2
             version: f6
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:124
        *-pci:3
             description: PCI bridge
             product: Gemini Lake PCI Express Root Port
             vendor: Intel Corporation
             physical id: 14
             bus info: pci@0000:00:14.0
             version: f6
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:125
        *-pci:4
             description: PCI bridge
             product: Gemini Lake PCI Express Root Port
             vendor: Intel Corporation
             physical id: 14.1
             bus info: pci@0000:00:14.1
             version: f6
             width: 32 bits
             clock: 33MHz
             capabilities: pci pciexpress msi pm normal_decode bus_master cap_list
             configuration: driver=pcieport
             resources: irq:126
        *-usb
             description: USB controller
             product: Celeron/Pentium Silver Processor USB 3.0 xHCI Controller
             vendor: Intel Corporation
             physical id: 15
             bus info: pci@0000:00:15.0
             version: 06
             width: 64 bits
             clock: 33MHz
             capabilities: pm msi xhci bus_master cap_list
             configuration: driver=xhci_hcd latency=0
             resources: irq:128 memory:c1200000-c120ffff
           *-usbhost:0
                product: xHCI Host Controller
                vendor: Linux 6.8.0-87-generic xhci-hcd
                physical id: 0
                bus info: usb@1
                logical name: usb1
                version: 6.08
                capabilities: usb-2.00
                configuration: driver=hub slots=9 speed=480Mbit/s
              *-usb:0
                   description: Mouse
                   product: USB Device
                   vendor: CHERRY
                   physical id: 3
                   bus info: usb@1:3
                   logical name: input2
                   logical name: /dev/input/event2
                   logical name: /dev/input/mouse0
                   version: 1.10
                   capabilities: usb-1.10 usb
                   configuration: driver=usbhid maxpower=100mA speed=12Mbit/s
              *-usb:1
                   description: Keyboard
                   product: Lite-On Technology Corp. USB Multimedia Keyboard System Control
                   vendor: Lite-On Technology Corp.
                   physical id: 4
                   bus info: usb@1:4
                   logical name: input3
                   logical name: /dev/input/event3
                   logical name: input3::capslock
                   logical name: input3::numlock
                   logical name: input3::scrolllock
                   logical name: input4
                   logical name: /dev/input/event4
                   logical name: input5
                   logical name: /dev/input/event5
                   version: 1.04
                   capabilities: usb-1.10 usb
                   configuration: driver=usbhid maxpower=100mA speed=2Mbit/s
              *-usb:2
                   description: MMC Host
                   product: USB2.0-CRW
                   vendor: Generic
                   physical id: 6
                   bus info: usb@1:6
                   logical name: mmc1
                   version: 39.60
                   serial: 20100201396000000
                   capabilities: usb-2.00
                   configuration: driver=rtsx_usb maxpower=500mA speed=480Mbit/s
              *-usb:3
                   description: Bluetooth wireless interface
                   product: Bluetooth Radio
                   vendor: Realtek
                   physical id: 7
                   bus info: usb@1:7
                   version: 0.00
                   serial: 00e04c000001
                   capabilities: bluetooth usb-1.00
                   configuration: driver=btusb maxpower=500mA speed=12Mbit/s
           *-usbhost:1
                product: xHCI Host Controller
                vendor: Linux 6.8.0-87-generic xhci-hcd
                physical id: 1
                bus info: usb@2
                logical name: usb2
                version: 6.08
                capabilities: usb-3.00
                configuration: driver=hub slots=7 speed=5000Mbit/s
        *-generic:1
             description: Signal processing controller
             product: Celeron/Pentium Silver Processor I2C 0
             vendor: Intel Corporation
             physical id: 16
             bus info: pci@0000:00:16.0
             version: 06
             width: 64 bits
             clock: 33MHz
             capabilities: pm bus_master cap_list
             configuration: driver=intel-lpss latency=0
             resources: iomemory:7f0-7ef irq:27 memory:c1213000-c1213fff memory:7ffff08000-7ffff08fff
        *-generic:2
             description: Signal processing controller
             product: Celeron/Pentium Silver Processor I2C 3
             vendor: Intel Corporation
             physical id: 16.3
             bus info: pci@0000:00:16.3
             version: 06
             width: 64 bits
             clock: 33MHz
             capabilities: pm bus_master cap_list
             configuration: driver=intel-lpss latency=0
             resources: iomemory:7f0-7ef irq:30 memory:c1212000-c1212fff memory:7ffff07000-7ffff07fff
        *-generic:3
             description: MMC Host
             product: Celeron/Pentium Silver Processor SDA Standard Compliant SD Host Controller
             vendor: Intel Corporation
             physical id: 1c
             bus info: pci@0000:00:1c.0
             logical name: mmc0
             version: 06
             width: 64 bits
             clock: 33MHz
             capabilities: pm bus_master cap_list
             configuration: driver=sdhci-pci latency=0
             resources: iomemory:7f0-7ef iomemory:7f0-7ef irq:39 memory:7ffff06000-7ffff06fff memory:7ffff05000-7ffff05fff
           *-device
                description: SD/MMC Device
                product: SCA128
                vendor: Unknown (223)
                physical id: 1
                bus info: mmc@0:0001
                date: 10/2022
                serial: 3286783235
                capabilities: mmc
              *-interface:0
                   physical id: 1
                   logical name: /dev/mmcblk0rpmb
              *-interface:1
                   physical id: 2
                   logical name: /dev/mmcblk0
                   size: 125057368064
                   capabilities: gpt-1.00 partitioned partitioned:gpt
                   configuration: guid=379af956-53ff-4aed-8aaf-692e8a873c2d logicalsectorsize=512 sectorsize=512
                 *-volume:0
                      description: Windows FAT volume
                      vendor: mkfs.fat
                      physical id: 1
                      logical name: /dev/mmcblk0p1
                      version: FAT32
                      serial: f845-01be
                      size: 297MiB
                      capacity: 299MiB
                      capabilities: boot fat initialized
                      configuration: FATs=2 filesystem=fat
                 *-volume:1
                      description: EXT4 volume
                      vendor: Linux
                      physical id: 2
                      logical name: /dev/mmcblk0p2
                      version: 1.0
                      serial: 1301d5da-0c53-4f66-b11e-f0d5ad54d397
                      size: 116GiB
                      capacity: 116GiB
                      capabilities: journaled extended_attributes large_files huge_files dir_nlink 64bit extents ext4 ext2 initialized
                      configuration: created=2025-07-28 18:20:55 filesystem=ext4 label=lubuntu_2404 lastmountpoint=/ modified=2025-11-06 16:20:10 mounted=2025-11-06 16:20:12 name=lubuntu_2404 state=clean
        *-isa
             description: ISA bridge
             product: Celeron/Pentium Silver Processor LPC Controller
             vendor: Intel Corporation
             physical id: 1f
             bus info: pci@0000:00:1f.0
             version: 06
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
                product: PnP device PNP0b00
                physical id: 2
                capabilities: pnp
                configuration: driver=rtc_cmos
        *-serial
             description: SMBus
             product: Celeron/Pentium Silver Processor Gaussian Mixture Model
             vendor: Intel Corporation
             physical id: 1f.1
             bus info: pci@0000:00:1f.1
             version: 06
             width: 64 bits
             clock: 33MHz
             configuration: driver=i801_smbus latency=0
             resources: iomemory:7f0-7ef irq:20 memory:7ffff04000-7ffff040ff ioport:f040(size=32)
  *-input:0
       product: Power Button
       physical id: 1
       logical name: input0
       logical name: /dev/input/event0
       capabilities: platform
  *-input:1
       product: Power Button
       physical id: 2
       logical name: input1
       logical name: /dev/input/event1
       capabilities: platform
  *-input:2
       product: sof-essx8336 HDMI/DP,pcm=7
       physical id: 3
       logical name: input10
       logical name: /dev/input/event10
  *-input:3
       product: Video Bus
       physical id: 4
       logical name: input6
       logical name: /dev/input/event6
       capabilities: platform
  *-input:4
       product: sof-essx8336 Headset
       physical id: 5
       logical name: input7
       logical name: /dev/input/event7
  *-input:5
       product: sof-essx8336 HDMI/DP,pcm=5
       physical id: 6
       logical name: input8
       logical name: /dev/input/event8
  *-input:6
       product: sof-essx8336 HDMI/DP,pcm=6
       physical id: 7
       logical name: input9
       logical name: /dev/input/event9
```