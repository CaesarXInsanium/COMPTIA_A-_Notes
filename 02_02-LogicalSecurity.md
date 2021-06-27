# Logical Security
## Active Directory
- centralized management. Window domain services
- login script. map network drives. update security signatures
- udate application software
- grouo policy updates: password lenght and complexity, login times access
- organizational units are associated with departments of organization or location in organization
- home folder. assign drive as users home folder
- folder redirection to store files in to the server. store documents in the server1
## Mobile DEvice Management MDM
- manage company owned and user ownded mobile devices
- used in BYOD or company provided
- centralized management. set policies, apps, data, camera
- entire device or partition 
- manage access control. force screen locks, PINS into single users
## Port SEcurty
- prevent aunauthorized users from connecting to swtich interface
- alert or disable ports. can block interrace
- based on source MAC address. 
- each port can have unique nconfiguration
- can configure maximun number of source MAC address on interface
- switch monitoes the number of unique MAC address
- default is to disable interface and maybe create alert
## MAC filtering
- mdiea access control. 
- limit access trough the physical hardware address. 
- limit devices via MAC address
- very easy to do MAC spoofing.
- free-open-source software
- security trough obscurity
## SMart CArds
- user must have physical card to provide digital access. digital certificate
- use with multiple other factors
## certificate base authentication
- PIV: Perosnal identity verification 
- CAC: Common access card
- IEEE 802.1X: gain access to network via certiffication
## Anti-virus
- anti-malware software runs on the computer
- updates are completed on all the devices
- large organization need enterprize management. track updates, push, confirm, reports
- mobility makes everything much more difficult
## Host based firewall
- personal firewalls, software based
- included in many OS
- stop aunthorize network access to specific application
- window firewall allow to control traffic via port number of application
## Network-based firewall
- filters traffic by the port number
- can encrypt traffic in and out of the network
- can proxy traffic
- most firewalls can be layer 3 devices
## user authentification
- identifier: something unique. in windows each account can Security identifier SID
- credentials. tie account to user
- profile: information about the user, contact information
## strong password
- weak passwords are difficult to protect against
- hashed passwords can be brute forced
- passwords need complexity
## Multi-factor authentication
- something you are, something yo have, something you know, somewhere you are, something you do
- certain implementations can be expensive. seperate hardware tokens
- token generators can be software based
- pseudo random numbers are difficult to guess. this number changes constanly.
- saves money, free smarthphone application. no seperate devices
## Directory permissions
- NTFS permisions. can lock down access
- prevent accidental modification or deletion
- certain information should be seen
- user permissions, some can be administrator
- assign proper permissions
## VPN concentrator
- concentrator to encrypt and decrypt access device from remote location
- used with client software. can be built into the OS
## Data loss prevention
- wheres the data. SSN, credit card numbers, medical records
- stop the data before the bad guys get it
- there are a variaty of methods to transfor data
## access control list
- used to deny and allow traffic forNAT, QoS etc
- can be configered at router or switch
- ACLs evaluate on certain criteria. source IP and destination IP
## EMail filtering
- most vulnaburable prenetation vector
- filter unsolicited email. stop at gateway before it reache user
- can be on-site or cloud base
- can block executables, phishing attempts, unwanted content
## Trust and untrusted software source
-must always know the source and hash of the software
- trusted source, internal application, well known publishes, digitally-signed application
- untrsuted sources from third party sources, links in email, po-up and drive by downloads
## Least privilages
- user account is limited to only bare minimun for user to get there job done
- all user accounts must be limited
- dont allow users  to run with administrative privilages
