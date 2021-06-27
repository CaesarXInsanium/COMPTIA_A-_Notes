# Backups
## Images
- bare metal backup using images
- operating system snapshot os hypervisor snapshots
- recover entire system at once
- make exact copy elsewhere
## file level
- copy individual files in backup
- may not include sytem files
- may need to rebuild the Os to get functional system
- then restore files
# critical application backups
- application software: ofen distributed accross multiple servers
- application data: databases, other data storage
- location of data: local vs cloud based
- all are needed for restoring
# baskupo testing
- its not enough to peform, must test first
- do disaster recovery testing
- confirm restoration, test restored application and data
- simualte disaster situation
- peform periodic audits
# UPS
- uninterruptible power supply: short term backup power incase of blackouts, brownouts and surges
UPS types
- Offline/standby: alway watches the voltage
- lineinterective: can slowly correct voltage
- on-line/double-conversion: always running from battery, always refreshing battery
- featues: autoshutdown messages, battery capacity, outlets, phone line supressions
# surge suppressor
- not all power is clean: self inflicted power spikes and noise
- storms, power grid changes
- spikes are diverted to the ground
- noise filters remove line noise
- ghigher Db is better filter
# cloud storage
- data is available anywhere any time any device
- require network
- no local hardware costs
- data is not under direct control. strong encryption is critical
# account recovery options
- apps wont work if users cant login
- windows domain will have foundation of recovery steps
- use other authentication methods
- two factor, RADIUS, TACACS, multi-factor
- have centralized administration. no local accounts. use domain
