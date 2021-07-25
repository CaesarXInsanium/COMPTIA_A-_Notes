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

## Missed Information

- BSOD - blue screen of death
- UPnP: universal plug and play. allows for easy and automatic network configuration for devices to connect to internet with no hassle from the user.
- running "ipconfig /flushdns" on windows will now likely reset the DNS settings and do a DHCP request to redo them. i think it will fixed issues related to DNS queries
- .wma : windows media audio. is native to windows
- CCFL inverter: convert alternate power to direct power in laptops
- hyprid SSHDs combine the capacity and low cost of HDDs and speed and reliability of SSD
- laptop hard drives come in 1.8 and 2.5 inch form factors
- optical drives are becomes less and less common and so are HDDs in laptops
- laptop intergrated GPUs can be replaced apperantly
- OLEDs have lower light output in comparison to LCDs
- IMAP is internet standard protocol used for email retrieval. it allows for email to be easily accessed rom multiple mail servers
- POP3 used port 993
- IMAP can also use port 993
- smartphones combine the capabilities of mobile phones with handheld PCs. they are handheld PCs
- IR: infrared wireless connection. used in remote controls
- POP3 and IMAP serve the same function of email retrieval
- POP3 and IMAP both use TLS and SSL
- TCP port 110 is used when configuring a POP3 connection
- IEEE 802.3 is ethernet
- IMAP required TCP port 143, password, username, and Server name. but no SSL of TLS encryption nor port 993
- iCloud does not provide support of POP
- PRL: Preferred Roaming List. database inside of phone that contains information onf system selection and acquisition. indicates bands, sub bands, service provider identifiers that can be scanned and connect to them in priority order.
- cable modem shares bandwidth with TV connection
- DSL modem has dedicated bandwidth and twisted pair copper cabling
- a network bride makes forwarding decisions in software, has fewer network segments than swtiches, older than actual switches
- a switch makes forwarding decisions in hardware. is sometimes referred to as a multi-port bridge
- PLC: allows transmission of ethernet of power lines
- DMZ is a type of network corporate network that lies just outside of the organization's firewal
- SNAT: STati Netowkr Address Translation does not provide mapping between private IP address and public IP address
- Universal plug and play allows for automatic configuration and joining of networks with minimal manual steps
- wifi analyser can be used to help making the most optimal WAP placement
- plenum is the reserved space in the ceiling for power, internet and air conditioning infrastructure is placed
- STP -> Shielded twisted pair
- UTP -> Unshielded Twisted pair
- RJ-45 is usually the ethernet connector standard
- RJ-11 is used for telephone connection
- Patch/Straigh-trough cable is used for connecting PC over to network infrastructure
- Crossover cable is used for connecting PC to one another
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

## TCP/UDP Protocol numbers

- RDP: TCP 3389 -> Microsoft Propriety remote access protocol that allows for remote desktop connection
- NetBIOS: TCP 137, 138, 139 -> used by WINS server to try and resolve hostname into IP address on windows based LAN
- NEtBT: allow NEtBIOS to be used over IP networks
- SMB/CIFS: TCP 445 -> provides access to files, directories and devices. used mainly by windows operating systems
- SLP: TCP 427 -> allows automated discovery of networked services in LAN
- AFP: TCP 548 -> file sharing protocol by Apple
- DHCP: automatic IP configuration
- LDAP: directory access protocol
- SNMP: TCP 162 -> used in network management to monitor network attached devices
- FTP: TCP 20 file transfer, port 21 session administration
- SSH: TCP 22
- Telnet: TCP 23
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

## SATA standards : Serial ATA

- power connector consists of 15 pins
- data link has 7 pins
- SATA data link can only connect to a single device
- 

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
- 

## SCSI

- was universal connector before the introduction of USB
- SCSI ID is used to indeity devies on a SCSI device chain
- LUN -> method of identifying logical partitions in SCSI hard drive.