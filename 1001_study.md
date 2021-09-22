# Practice Tests

currently on section 6

## Official

### 1001

1. A
2. A
3. D - C WPA encryption, infrastructure mode
4. A
5. B
6. A
7. B
8. A
9. C
10. B - C ipconfig /flushdns

### 1002

1. A
2. A
3. A
4. A
5. A
6. B
7. C
8. A
9. B
10. A

## Windows Informaiton

- **BSOD** -> blue screen of death
- **.wma** : windows media audio file format. is native to windows
- running `ipconfig /flushdns` on windows will now likely reset the DNS settings and do a DHCP request to redo them. i think it will fixed issues related to DNS queries

## Terms and Definitions

- **UPnP** -> universal plug and play. allows for easy and automatic network configuration for devices to connect to internet with no input from the user.
- **CCFL inverter** -> convert alternate power to direct power in laptops
- **IR** -> infrared wireless connection. used in remote controls
- **PRL** -> Preferred Roaming List. database inside of phone that contains information onf system selection and 
-  **SSHDs** -> combine the capacity and low cost of HDDs and speed and reliability of SSD
- **STP** -> Shielded twisted pair
- **UTP** -> Unshielded Twisted pair
- **RJ-45** is usually the ethernet connector standard
- **RJ-11** is used for telephone connection
- **DSL modem** -> has dedicated bandwidth and twisted pair copper cabling
- **network bridge** -> makes forwarding decisions in software, has fewer network segments than swtiches, older than actual switches
- The **switch** -> makes forwarding decisions in hardware. is sometimes referred to as a multi-port bridge
- **PLC** -> allows transmission of ethernet of power lines
- **DMZ** -> is a type of network corporate network that lies just outside of the organization's firewal
- **SNAT** -> Static Network Address Translation does not provide mapping between private IP address and public IP address
- **plenum** -> is the reserved space in the ceiling for power, internet and air conditioning infrastructure is placed
- **Patch/Straigh-trough** cable is used for connecting PC over to network infrastructure
- **Crossover cable** is used for connecting PC to one another
- **PoS** -> point of sale, in this occasion it can be refer to either that hardware that is used such as 
- **KVM switch** -> allows for single set keyboard, mouse and monitor to control connect to multiple computers. swtiching between them should be possible via certain keyboard shortcuts
- **MDM** -> Mobile device management

## Small Concepts

- laptop hard drives come in 1.8 and 2.5 inch form factors
- optical drives are becomes less and less common and so are HDDs in laptops
- laptop intergrated GPUs can be replaced apperantly
- OLEDs have lower light output in comparison to LCDs
- smartphones combine the capabilities of mobile phones with handheld PCs. they are handheld PCs
acquisition. indicates bands, sub bands, service provider identifiers that can be scanned and connect to them in priority order.
- cable modem shares bandwidth with TV connection
- Universal plug and play allows for automatic configuration and joining of networks with minimal manual steps
- wifi analyser can be used to help making the most optimal WAP placement
- typical maximun segment lenght for copper twisted pair ethernet cable is 100 meters
- minimun requirements for twisated pair cabling is Cat 5e
- cat 6 is minimun required for 10 Gbps
- all ethernet networks ca hvae UTP STP and coax cabling


### SAS

- Serial interface
- point-to-point connection
- does not require bus termination

### Copper Cabling Specifications

T568A

T568B

## TCP/UDP Protocol

- POP3 and IMAP serve the same function of email retrieval
- POP3 and IMAP both use TLS and SSL
- TCP port 110 is used when configuring a POP3 connection
- IEEE 802.3 is ethernet
- IMAP required TCP port 143, password, username, and Server name. but no SSL of TLS encryption nor port 993
- iCloud does not provide support of POP
- IMAP is internet standard protocol used for email retrieval. it allows for email to be easily accessed rom multiple mail server

### Protocol numbers

| Name | Type | Port Number/s | Description |
|------|------|---------------|-------------|
| FTP  | TCP  | 20,21         | File Transfer protocol. 20 is file transfer and 21 is session authentication
| SSH  | TCP  | 22            | Allows secure remote and encrypted authentication and management via command line
| Telnet | TCP | 23           | allows unsecure remote connection and management via command line before SSH
| NetBIOs | TCP | 137,138,139 | used by WINS server to resolve hostnames into IP address 
| RDP  | TCP  | 3389          | Microsoft propriety remote access protocol |

| NetBt | TCP | N/A           | allows NetBIOs ot be used over IP networks

- NetBIOS: TCP 137, 138, 139 -> used by WINS server to try and resolve hostname into IP address on windows based LAN
- NEtBT: allow NEtBIOS to be used over IP networks
- SMB/CIFS: TCP 445 -> provides access to files, directories and devices. used mainly by windows operating systems
- SLP: TCP 427 -> allows automated discovery of networked services in LAN
- AFP: TCP 548 -> file sharing protocol by Apple
- DHCP: automatic IP configuration
- LDAP: directory access protocol
- SNMP: TCP 162 -> used in network management to monitor network attached devices
- FTP: TCP 20 file transfer, port 21 session administration
- SMTP: TCP 25
- DNS: UDP 53
- HTTP: TCP 80
- HTTPS: TCP 443
- POP3: TCP 110 993
- IMAP: TCP 143 993
- IDS vs IPS relays the difference passive and acive network security breaches responses
- client to site and remote-access VPN types allows a user to connect to a remote network from out in the internet
- SSL VPN connection does not require dedicated VPN client
- VLAN: allows for logical grouping of computers that will allow computer hosts to act as if they are attached to the same broadcast domain

## Wifi

| Protocol | Name    | Ghz       | Backwards  | Mbps | Channel Range MHz|
|----------|---------|-----------|---------|-------|-------|
| 802.11a  | Wifi 1  | 5.0       | N/A     | 54    | 20    |
| 802.11b  | Wifi 2  | 2.4       | N/A     | 11    |       | 
| 802.11g  | Wifi 3  | 2.4       | b       | 54    | 20    |
| 802.11n  | Wifi 4  | 2.4, 5.0  | g, b, a | 600   | 20, 40|
| 802.11ac | Wifi 5  | 5.0       | N/A     | 6770  | 20, 40, 80, 160|
| 802.11ax | Wifi 6  | 2.4       | N/A     |       |

## Cat Standards

- Coaxial -> used for carrying cable TV, has protection against EMI, can be used for internet connection


| Cat | Speed Mbps | Max Length meters |
|-----|---------|------------|
| 3
| 5 | 100/100/1,000 | 100 |
| 5e | 100/1,000/10,000 | 100 |
| 6 | 10,000 | 35-55 |
| 6a | 10,000 | 100|

## Fiber Optics

### Multimode

- trasnmit up to 2 km
- costs less than single mode-fiber
- used LED as light source

### Single mode

- costs more than multi-mode
- uses laser as source of light
- can trasmit up to 100 km

## Connectors

- digital DVI and HDMI can use a passive adapter to switch between them but for analog and digital conversion an active adaptor is required
- DVI-I/DVI-A can be passively converted to WGA
- USb to thernet converter enable 802.3 connectiv or ethernet connection via a USB thing
- RS-232 and VGA cables are examples of D-sub connectors
- BNc connectos have coppwer cabling connector, connector equipped with bayonet style locking mechanism and coaxial cabling
- RG-59 cables are coaxial, siutable for short distance cable runs, used for analog video and CCTV installations
- RG-6 cables have coaxial cabling, suitable for longer distance cable runs and used for cable television, and cable modems
- F-type connectors are coaxial, used for cable television, satellite tTV and cable modems, use RG-59/RG-6 cabling. copper cabling connector, and used for analog video and CCTV installations. 
- RS-232 can have a DE-9 and DB-25 connectors types connect to a RS-232 port
- lighting is a propierteray connector type that is USB compliant and reversible but not as good as USB-C
- molex connecotr is the most common way in which many hardware components receive power
- 

HDMI
: digital connector that can trasmit audio and video

- Type C connector mini HDMI is used in portable devices such as camcorders and digital cameras
- s

Thunderbolt
: propierity Intel connection standard that allows high speed data trasnfer, support for multiple devices over PCI connections

- max cable length is 3 meters
- fiber optic thunderbolt chas max cable lenght of 60 meters

| Version | Speed in Gbps | Connector | Max Devices | Features |
|---------|---------------|-----------|-------------|----------|
| 1 | 20                  | Mini display Port | 6 | PCIE/displayport data and power |
| 2 | 20                  | Mini display Port | 6 | PCIE/Displayport data and power |
| 3 | 40                  | USB-C | 6 | 
| 4 |

- DVI-I supports both analog and digital signals

## USB standards

| Version |  Speed | Backwards Compatible? | Lengtht | 
|---------|--------|-----------------------|---------|
| USB 1 |  1.5 Mbps low speed, 12 Mbps Full Speed | N/A | 
| USB 2 | high Speed
| USB 3.0 | 5 Gbps SuperSpeed | yes|
| USB 3.1 | 10 Gbps | 
| USB 3.2 | 20 Gbps |
| USB 3.3 |

- USB 1 and 2 have max cable range of 5 meters
- type connectoirs can connect to devices that supply power, host devices, 
- max number of devices ber Usb host controller, 127
- type-b connectors connect to target devices or devices that receive power
- USB-C is a symmetrical and reversible connector standard
- USB-A allows for easy backwards compatiblity with ealier USB standards
- 

## SATA standards : Serial ATA

- power connector consists of 15 pins
- data link has 7 pins
- SATA data link can only connect to a single device
- eSata connecotrs fo not feature and l shaped port and connector.
- features include serial interace, L-shape design, hot swappable, allows for connecting sotrage devices to motherboard

| Version |  Speed | MAx Cable Lenght |
|---------|-------|-------------------|
| 1.0 | 
| 2.0 | 3 Gbps | 1 meter |
| 3.0 | 6 Gbps | 1 meter |
| 3.2 | 16 Gbps | 1 meter |

## PATA

- cable consists of 40 wires
- ribbon cable
- two drives can be connected with a single cable. however one must be configured as masteer and other slave
- max cable lenght of 16 devices
- IDE port is used to connect PATA drives to older motherboards. has 2 rows of pins, 40 total, is a parallel interace
- 

## SCSI

- was universal connector before the introduction of USB
- SCSI ID is used to identify devices on a SCSI device chain
- LUN -> method of identifying logical partitions in SCSI hard drive.

## RAM

- any motherboard with color coded RAM slots have multi channel support generally speaking
- ECC RAM can detect and correct errors
- EEPROM and EPROM are erasable non-volatile memoty types
- DVD-RAM allows for permanet data storage
- SDRAM uses system clock i order to synchronuze memory operation with other PC components
- SDRAM does not offer backwards compatibility
- different levels of DDR cannot be combined in the same computer since the are all incompatible
- SODIMM memory is generally used in compact devices such as laptops.
- DDR: Double Data Rate. each level is twice as fast the previous level. 
- SODIMM DDR3 SDRAM modules have 204 contact pins
- SODIMM DDR4 SDRAM has 260 contact pins
- DDR$ -> has 1 nothc, 288 contact pins, reads and writes 8 words of data per clock cycle
- DDR3-2666 is known as PC4-21300
- DDR2-1066 modules are generally known in industry as PC2-8500
- DDR3-1333 are known as PC3-10600
- DDR3-1600 max transfer rate is 12800 MB/s
- DDR4-3200 max trasnfer rate is 25600 MB/s
- DDR2 SDRAM SODIMM has 200 contact pins

### DDR

- DDR2 perform operations at 4 times system clock. 
- 240 contact pins
- 1 nothc on the module contact surface

### STAtic Random Access Memory

- faster than DRAM, more expensive, volatile
- fount inside of CPU as the cache memory


### Dynamic Random Access Memory

- volatile, slower than static, used more common
- used in memory modules in motherboard

## CDs

- CD-ROM can written once and Read
- CD-RW write many read many
- up to 737 MB data storage capacity
- 80 minutes of uncompressed audio

## DVDs

- DVD-ROM  write once read many
- DVD-RW write many read many
- 4.7 GB single layer max
- 8.5GB single side double layer

## Blu-ray

- BD-R -> write once read many
- BD-RE -> write many read many
- 25 GB standard size single layer
- 50 GB standard size dual layer
- 7.8 GB single layer mini size
- 15.6 GB dual layer mini blu ray

## Flash Memory

- 

## RAID

- 0 -> Disk stripping, single drive failure ruins array. suitable for peformace. Does not offer fault tolerance. 
- 1 -> Requires at least two drives, offer reliability by creating identical sets of data on each drive. Single drive failure has afull backup. 
- 5 ->  requires 3 drives. offer increate peformace and fault tolerance. data stripping and mirroring. in case of drive failure data can be recontructed from remaining drives
- 10 -> nested RAID. minimun 4 drives. Mirroring and stripping.
- 1+0 -> nested RAID. create striped set from series fo mirrored drives. 

## SSD

- M.2 ports have certai ID that determine the number of PCIe lanens and their speed
- NVME drives connect to compouter using PCIe lanes
- flash memory card formats: SD< CompactFLash, Micro-SD, Mini-SD, xD
- xD memory is a propierity flash memory that is used in older digital cameras

## PCI

- conventional PCI canj have both a 32 bit and 64 bit bus, max trouighput of 533 MB/s. parralel interface
- PCIe is used to replace PCI, PCI-X, and AGP
- a single lane is a 2 pair of wires used to transmit data and to receive data.
- PCIe labels are uised to express the speed of a single lane in MB/s. allow for easy calculation of maxi8mun troughput for entire interface
- speed of PCIe v1.0 is 250 MB/s
- speed of PCIe v2.0 is 500 MB/s
- speed of PCIe v3.0 is 985 MB/s
- speed of PCIe v4.0 is 1969 MB/s

## CPU

- LGA -> used by AMD with pins on CPU
- PGA -> pins are found on the motherboard
- the ZIG facilitates insertions and removals of CPU chip in certain microproccessor sockets
- RISC -> attempts to improve speed by using few simple intructions
- 

## Motherboard

- SFF mother types with backwards compatibility with full size ATX cases -> EATX, mATX, mITX
- rise card allows for additional expansion for motherboard apart from available expansion slots

## Expansion

-

## BIOS

- BIOS settings can be set to default by using jumper cable in motherboard, reseating the CMOS battery, choosing the default configuration in the BIOS interace
- BIOS contents are stored in EPROM
- BIOS updates are done in order to repoair damaged BIOS, provide support for new hardware and fix programming bugs
- aborted BIOS update can render a computer useless
- supervisor password can be set to lock the BIOS settings as well as a power one password to keep PC from booting
- UEFI -> replacement of BIOS that allows for mouse support, DRM support, GUI mode, SEcure boot, network access
- boot sequence is the ordering of drives and media connected to motherboard to select from whcih to boot from.
- chassis intrusion allows for detecting of possible tampering done with computer
- CMOS battery helps keep the time as well as the BIOs settings when power is disconnected


## Encryption and Security

- BitLocker is a Windows technology stack that allows for full disk drive encryption and security
- TPM is module built into certain computer that allows for device authentication for hard drive decryption
- LoJack allows for system location tracking and recovery in case of losage or theft. cosists of application agent and persistence module
- Secure boot prevent unauthorized loading of malware and OSs 

## Power

- voltages -> +3.3V, +5V, +12V\
- in older PSUs, -5V rail was used bny the ISA expansion cards
- -12V rail provides voltage for RS-232, PCI, and LNA circuitry

## Computer Build Considerations

- Thin client -> only runs basic application, minimun requriements for host os, must have a network connection. has minimun amount of functionality in order to connect to remote server where the application are run adn heavy lifting is done
- thicc client -> runs desktop application, must have recomended requirement for OS.

### CAD/CAM Workstation

- high end video
- SSD drive
- MAx RAM

### A/V Editing

- Dual monitors
- spcialized audio adn video card
- large fast hard drive

### Virtualization

- max RAM
- MAX CPU cores

### Gaming

- high end cooling
- SSD drive
- high end video card
- HD sound card

## SOHO

- wired conenction types -> USB, serial, ethernet
- wireless -> bluetooth, wifi/802.11, NFC
- ad hoc mode allows for devices to communicate with each other directly instead of routing trough intermediatary
- TCP, AirPrint, Bonjour are all protocols that allow for sharing of networked devices using operating system settings

## Printers

- legacy printer ports include LPT,and DB-25
- remote printing can be done with IPP, LPD/LPR
- fuser assembly applies heat and preassure in a laser printer
- in color laser printer the trasnfer belt picks up hte color layers beofre passing htme on into the paper
- in laser printing the treansfer roller applies electrical charge to sheet of paper to move image of product over to the paper
- seperation pad and pickup roller keepprinter from using too many sheets of paper at a time
- maintanace kit -> spare kit of printer parts for maintanace
- toner vacuum, magnetic cleaning brush and isopropyl alcohol are used in cleaning laser printer
- imaging drum is the most expensive component to replace in a inkjet printer
- thermal printers are generally used in Point of Sale scenarios
- dot matrix is type of impact printer
- impact and dot matrix printers can produce duplicate pages
- dot matrix printer uses a inked ribbon in order to produce imprint on pape
- single sheet and roll of printing paper can be used in dot matrix printer
- virtual printers use the XPS format


## The Cloud

- hybrid cloud is when some stuff is run in the cloud and some on premises. sometimes using multiple cloud providors
- rapid elesticity allows for rapid allocation of computing resources in response to increase in demand
- on demand self service allows for volume and type of compueting resources to be manually determined by the consumer
- s

## Virtualization Work

- emulator refers to hardware or software that bridges gap between different OS by enabling software to run in incopatible operating systems
- VM sprawl is when a large number of VMs are deplayoed without proper administration
- vm escape -> when a software or virus detects that operating system is running as a virtual machine and escape into the host operating system

## Troubleshooting

Steps

1. Identify Problem
2. Conduct Research
3. Develop Theory
4. test theory
5. Establish plan of action
6. Implement Solution
7. Verify intended Functionality
8. Document Findings
9. Follow up with client

- stuck pixel ->
- dim LCD display might indicate problem with backlight or inverter
- long vertical streaks might indicate damage to imaging drum
- depleted toner will cause faded and blank printed pages
- ghost images in printed paper might indicate problem with cleaning proccess
- toner falling of page might indicate problem with fuser assembly
- garbled characters might indicate problem withprinter driver
- IPv4 address in range 169.254.0.1 through 169.254.255.254 indicates problem with DHCP configuration
