# Wireless encryption
- all wireless computers are radio transmitters and receives
- all data must be encrypted
- everyone gets a password or unique passwords
- only people with assword can transmit and listen
## WPA
- created from 2002 after WEP had significant vurnabilities
- neede for short term bridge between WEP and successor
- WOA: RC4 with TKIP (Tempora Key Integrity Protocol)
- each packet had 128 bit key
## TPKI
- mixed the keys to combine secret root key
- add sequnces with couter
- implements 64-bits message integrity check
- TKIP had other vurnabilities and deprecated in 802.11-2012 stanard
## WPA2 and CCMP
- began use in 2004
- AES(Advanced encryption standard) replace RC4
- CCMP(Counter mode with cipher code protocol) block chaining
- CCMP use AES, 128-bit key and 128-bit block size
- but require more resources to use 
- CCMP security services, data confidentiality, authentiation and access control
## Wireless security modes
- configure the authentication in WAP
- open system. no password
- WPA2-personal: pre-shared key for access to home network
- WPA2-Enterprise. authenticate with unie user id and password. enable and disable with account controls
## RADIUS (Remote authentication Dial un User Service)
- one of more common AAA protocols. supported on many platforms and devices
- centrlized authentcation for users
- router swtiches, firewalls, server authentication, remote vpn access, wifi access
- built in into many operating systems
- 
## TACACS
- terminal access controller access-control system. remote authentication protocol
- created to ctronl access to dial up lines adn ARPANET
- TACACS+: newer version to this thing. released as open standard in 1993
- 