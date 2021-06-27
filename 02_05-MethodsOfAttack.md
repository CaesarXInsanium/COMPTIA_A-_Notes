# Social Engineering
- constantly evolving
- may involde single or multiple people organizations
- phone calls, aqggresive customers
- social manipulation
- authority: social engineer is in charge of situation. they be pretednt to police or CEO
- intimidation: bad things will happen if you dont do a thing
- consensus: social proof.convice based on what is normal expected
- scarcity: situation will not be same way for long
- urgency: no checks no thinking
- familiarity: liking: someone you know, we have common friends
- trust: 
**Phishing**: social enginnering with touch of spoofing. check the URL. fake login websites to steal you credentials.

**Vishing**: is done over the phone. fake security checks of bank updates

***Spear phishing**: pishing with inside information. whaling is specific targeting of CEOs or executives. 
- April 2011 Epsilon

**impersonation**: pretend to be someone else. use public details. attack wictin as someone of greater authority.
-be a buddy
## Shouldr Surfing
- many people want to see the things that are in the screen
- very easy to do and easier to hide the fect
- use privacy filter to see
- easier in big city
- webcam monitoring
## Tailgating
- use someoneelse to gain access to a building
- blend in with clothing, 3rd party with legitimate reason
- bring in donuts or treats
## Dumpster diving
- mobile garbage bin
- important information thrown out in the trash. gather details
- can be migitated by destrying the useful trash
- legal in US except under certain restrictions, like if in private property
- ask a lawyer
# Denial of Service
- forve a service to fail generally by overloading
- take advantage of desgin failure or vulnerability
- create smokescreen for some other attack
- turn of power an be considered DoS
- taing two switches and plugging them together using two wires, will couse the switch to loop data around eternally
- accidentaly DoS by overloading the network. can cause take down
- water line breaks, accident. must stop computers
## Distributed DEbianl of Service: DDOS**:
- launch army of bots in botnet wot send request to target in order to bring it down.
- super alrge botnets have reached the million of devices
- attacks are zombies, users do not know their computers are infected
## Mitigation
- use firewall rules of filter out traffic patterns
- use ISP to filter
- third party technologies
# Zero-day
- many application have vulnerabiities, ot found yet
- good guys and bad guys are looking for hem
- bad guys sell or keep.
- zero-day is when nobody except for one person or few know about a vulnerability and do not share but can be used
- zero day are more and more common
## examples
- CVE-2017-0199: wordpad remote code execution hat can be exploited by opening MS ofice
- 
# Man-in-the-middle
- intercelpt and view communication between two devices
- redirection of traffic, 
- ARP poisining: ARP has no security. 
## nitigation
- use encrypted protocols
- use client based VPN, secure channels
- makes data useless to others
# Brute force
**Password files**: passwords are hashed and store in file. cannot be reversed, easily. 
- trying every single version of password until one is found that works. 
- constant trial and error. 
- **Online**: trying thorhg the login process. most accounrs will lockout
- **offline**: obtain list og users and hashed passwords. calculate password hash and comprare to stored hash. 
- large computational resources required
## Dictionary attack
- using common words as passwords. start with the easy ones. dictionary terms
- common word lists available on net, by language and line or work
- dwill catch low hangin fruit
## Rainbow table
- oprtimized pre-buolt set of hashes. calculations have already been done.
-  large speed increase. specially for long password lenghts
- windows and linux store passwords stored in different ways
- salted hashes add additional values to riginal has so as to make the brute forcing that  the mroe painful
# Spoofing
- pretend something you arent: web server, DNS server, email address, caller ID, mac address
- use in man in the middle
- mac address spoofing is very easy, more drives allow this
- changin MAC addres can be legit, application or ISP or network reason
- difficult to detect. use other factors
- IP address spoofing: can be used for load balancing and testing
- ARP posining, DNS amplication DDoS.
- easier to detect IP spoofing as opposed to Mac spoofing
# Non-compliant Systems
- constant challange to make tests and changes and updates. to keep things compliant
- standard operatin enviromets SOE
- set of tested and approved hardware-software systems for production enviroments
- use standard operating system image
- operating system and application updates, must have patches, OS updates virus signatures
## Protection against non compliance
- operating system control
- monitor network application traffic
- peform periodic scans, requrie corrections before access can be granted
- 
