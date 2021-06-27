# Windows Troubleshooting
## Slow System
-  check task manager
- high CPU utilization and I/O
- threads and appication that are hogging resources
- windows update
- check disk space: need enough space for programsna dswap
- HDDs need defrag
- laptops use power saving mode and heat management
- anti-virus scan for infection
## Limited Connectivity
- check the netowkr settings
- check wiresless signal,interferance
- check ethernet cable, router/swtich connection
- reboot
- check for connection to internet, self and other devices in network
- ping default gateway adn exgternal IP
## Boot Errors
- cant fint OS
- bootloader replaced or changed: multiple OS
- check boot drives and check boot order
- windows installation media includes startup repair
- modify the Window Boot Configuration database
- run command from recovery console. will check for operating systems and add to bootloader
```powershell
bootrec /rebuildbcd 
```
## startup repair
- **missing NTLDR: main windows boot loader is missing.** 
- ***run startup repair or replace manually ad reboot. disconnect removable media, DVD/CD, USB flash drive**
- missing os: run startup repair or manually configure BCD store
- Boot into safe mode: run startup repair
## application crashes
- ProgramX has stoppedworking
- Check the event log
- check reliability monitor to check history. will show graph application programs and events from history
- reinstall application. contact application support
## Bluescreen and Spintenous Shutdown
- startup shutdown BSOD: bad hardware. bad drivers, bad application. windows stops itself safely so as to not cause real damage from the true error
- rollback to good system restore or rollback driver
- try safe mode
- reseat or remove the hardware. check connection
- run hardware diagnostics provided by manufacturer
## Black Screen
- no login dialog, no desktop
- driver corruption OS file corruption
- start in VGA,
- run SFC: system file checker. wil go trough all files in operating system and check for corruption and damage
- update drive in safe mode. download from trusted source. 
- run refresh: will replace the OS files and boot
## Test printer
- print or scan a test page. built into Windows
- use diagnostic tools, web based, vendor specific, generic options are available
## starting system
- device not starting:
check device manager and evetn viewer. remove or replace the driver to good one
One or more services failed to start
- bad driver, bad hardware
- try starting manually
- check account permissions
- confirm service dependencies
- windows service, check system files
- application service
check the windows services utility
## Slow boot
boot proccess hangs or is slow
- manage startup apps
- check task manager for bloat
- disable everything until we find the bloat
## slow profile load
- roaming user profile. desktop follow user profile on any computer
- network latency to domain controller. slow login script transfers, slow application of computer and user policies
- may require many queries
- client workstation picks remote domain controller instead of local DC
# Troubleshooting Solutions
## Defragmentation
- move file fragments so that they are continous. instead of in pieces all over the hard drive
- improve read and write time
- only available for spining hard drives
```powershell
defrag
```
## Reboot
- bug in router software reboot to change into good software
- application is using too many resources
- memory leak slowly consumes all RAM, reboot will clear RAM
## Kill task
- find problem and kill it
- sort by resource usage
## Restart services
- application that run in background. user interaction
- can have same problems as other applicatrions
## update netowkr settings
- one incorrect configuration can cause network slowdowns
- check speed and duplex
- driver may not show negotiation
- view in command line or the event viewer
- device should match switch. 
## Reimage or reload OS
- windows is big.
- spend time trying to find the needle. or built the haystack
- many organization have prebuilt images and can be booted into. generally faster this way
- Windows 10 have reset option
## Rollback
- restore points. go back in time to previous config and keeps installed application at time of restore point
- restore point created during application installations
- device drives can break windows. rollback froms tart menu
## update and patch
- window update: update utility. change active hours, manage metered connection
- set automatic or manual updates
- applications must be patched
- security issues dont stop OS
## Repair application
- application issues. some application can have repair options
- fix missing broken files, fix application shortcuts
- repair registry entries
- update reconfigure drives
## update boot order
- try to boot from USB drive
- does not even try
- set boot order and devices
- each BIOS is different. configuration can always be found
## Disable Startup services/apps
- can be difficult to find problem child
- trial and error. disable one at a time until problem app is found
- managed in task manger control panel, administrative tools and services
## Safe mode - 7, 8/8.1
- press F8 in advanced boot options
- safe mode. only neccesary drivers for seeing screen
- safe mode with networking. internet connection
- safe mode with command prompt
- no windows explorer. very quick and dirty way
- use low-resolution VGA mode
## Safe mode windows 10
- F8 does not work. window recovers from hibernate mode
- settings / update and security / recovery / advance startup / restart now
- system configuration (ms config)
- interrupt boot proccess three times until it works
- has no wallpaper, has safe mode on screen, show window version and build
## Rebuild window profile
- profiles can be corrupted
- user profile service failed the logon
- profile must be recreated and cannot be rapired
## Deleting Window Profiles
- login computer with domain admin rights
- rename user name folder
- backup user's registry
- export for backup
- delete registry entry. at next logon the profile will be recreated
## recontruction window sProfiles
- login computer with user account, user profile will be rebuild
- login as admin: copy over important fiels from old profile
- do not copy entire profile. only the most imporatn things
- login as user account