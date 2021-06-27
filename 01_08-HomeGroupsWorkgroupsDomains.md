methods to share files adn resources
## OrGANIZING Network Devices
- Windows Homegroup: designed to be use in private personal setting
- share files, photos, video, works on private network only
- Windows WorkGroup: logical groups of network devices
- each device is a stand alone system, every device is a peer
- Windows Domain: business network
- centralized authentication and devices access
- support for thousands od devices accross many networks
## Homegroup
- easily share inforation in Win7 and 8
- removed from windows 10
- network for the home that is enabled and
- create single password for the whole network, 
- allows for sharing of files and resources
## Workgrouo
- smnall departments, each computer maintains own user information
- non centralized
- managed in control panel
## Domains
- Central database: Active Directory Domains services
- user accounts are managed centraly, devices are added to the domain
- manage all devices adn users, deply software, manage the operating system for all the connected devices
## Join a Domain
- cannot be windows Home edition to join domain
1. Go to Control Pane
2. Go to System informatin
3. Click join Domain/workgrouo
4. select business network
5. select with a domain
6. Type in relevant login information

# Window Network Technologies
## network Locations in Windows 7
- automatically set security levels
1. Home: network is trusted, communicated with all devices
2. Work: you can see other devices, cannot join homegroup
3. Public: airport, coffee, invisible highest security settings

## Windows 8/8.1/10
1. private: sharing and connect to devices
2. Public: no sharing or connectivity
- network and internet status configuraiton

## Remote Access
-Remote assistance: Home editions, one time remote access
- single use password, chat diagnostics and NAT traversal
- Remote DEsktop Conneciton: non-home edition
- local authentication options
- may require port forwarding
## proxy Settings
- change the traffic flow, internet go-between
- go to control panel, internet properties and set LAN proxy settings
- set rules for certain applications
## Network Shares
- make folder available in the network
- assign drive letter to a share
- shares with dollar sign hidden are hidden but can be connected it the name is known
- control panel/administrative tools/computer managment
## Mapping drives
- access a share
- local drive latter and share name
- may require additional authentication
## Printer shares
- similar to sharing a folder
- allows sharing of printer connection to add print jobs
- windows explorer, add a printer

# Establishing Window Network Connections
## Network Setup
- control panel: netowkr and sharing netowkr
- step by step wizard to connect to many different types of connections
## VPN Concentrators
- creates VPN tunnel, use by large organization
- allows easy connection to VPN connection to enterprise level network
- encrypted information, VPN concentrator decrypts packets once inside the network
- use the built-in VPN vlient
- intergrate smart card authentication
- something you know
- soemthing you have
- somethign you are
## Dialup Connections
- modem connections over standard phone lines
- configuration, phone number
- connect of disocnnect at will
## Wireless Connection/ WIFI COnneciton
- requires SSID, security type, encryption type, security type, 
- WPA2 is good standard.
## Wired connection
- usiong ethernet cable connection, fastest connection by default
- windows always chooses the fastest option
## WWAN Connection
- wireless wide area netowkr
- same as the cellular data connection, install hardware adapter
- or use the phone as mobile hotspot for internet connection
- can require installation of third party software

# Configuring Window Firewall
## Enabling the Window Firewall
- firewall should always be enabled
- only disable to troubleshoot
- temporaly disable from main screen, requires elevated privalges
- can block all incoming connections and traffic
- notify when new app has traffic to decide what action to take
- allow app or feature with internet conenction
- configure port permissions, 
- custom rules are allowed and possible
- requires Windows Firewall rules configuration tool
- can apply rules to domain, private and public networks

# Windows IP address configuration
## DHCP
- by default Windows receives IP address via DHCP
- APIPA: when there is not DHCP server or static address then is default address link local. can communicate with devices locally but can not communicate with outside network
- static address: assign IP addres parametes manually, requires specific details adn manually tracked
## TCP/IP host address configuration
- IP address
- subnet mask
- gateway
- DNS server IP address
- loopback address send packets to itself.
## Backup for the DHCP server
- multiple DHCP server shoud be configured for redundancy
- is server is not available then APIPA is used by Windows
- or can configure address manually

can be access by going into control center and network and sharing 

# Netowork Adapter Properties
## Network Adapter properies
- link speed adn duplex settings
- auto negotiation does not always work
- available in power management to wake up on LAN. wake device from sleep from specific packet or frame to do maintanace
- QoS prioritice the network traffic for different applications
- differentiated services code points we can set priprities for diffferent types of traffic for the specifc machine
- manage under Local Computer Policy or group Policy
- set priuprities based on application and traffic type
## BIOS settings
- enable and disable devices. depends on BIOS type and version.
- set administrator password to prevent access to BIOS
