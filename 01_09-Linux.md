# Linux Best Practices
## Scheduled backups
- has many options and techniques
- can be done via command line, scripts, automation and gui applications. even combinations of both
- distros can have utilities built it
- tar: command use to work with many different compression algorithms to backup information and do other things
- rsync: remote sync files between  storage devices

## Schedule disk maintainace
- very littel disk maintanace required
- to check file system. 
    1. file system must not be mounted. can be done as the systemd is rebooting and root directory is not mounted yet
    2. can be forced by adding file to root with command
    ```bash
    sudo touch /forcefsck
    ```
- clean up log space. move to external storage and delete from the system to free up space
## System uptdates
- use default system package manager to peform updates
- graphical update managers for easyness
- updates can be scheduled and micro managed
- most mainstream distros contain and linux app store to download apps
## Drive/firmwares updaes
- many drive are included in the kernel. updating kernel is the same as update device drives
- sometimes external drives are needed.  these can be managed yby using a distro specialize drive management tool or can be installed via the command line
## Anti-virus/anti-malware
- for personal desktop users best practices is all that is need to protect oneself by enteprise users should take every precaution to protect linux install
- ClamAV: opensource anti-virus engine
- same best practices. update virus signature database

# Linux Tools
## Backups
- backup solutions may be built into linux distro. however not always present, more likely to be found i enterprise targeting distros
- checks documenbtation for distro
- or you can download relevant packages that rpovide need functionality
- rsync: command.
- many options available
## image recovery
- minimal options in comparison to windows
- dd: command use to copy bytes of of a disk and into a file or vice versa
- backup and restore a partition. very powerful
- used with scripts
- GNU parted, Clonezilla
## Disk Maintanace
- distro has suffient disk maintanace
- clean up the log space
- file system check
## Terminal Emulator
- access to command line to control Os
- OS maintaqince. 
## SCreen Sharing
-  remote desktop utilities are available
- UltraVNC, REmmina are too options that are avaiable and open source

# Linux Commands
can be be started by using a terminal emulattor program
- commands are based from unix commands. GNU core utils
- use man command to view help one command. not always available
## ls
- list items and other directories in a directory. can take in a path to list items in that directory or can be run in current directory
- has support for color coding. 
- has many useful flags and options
## cd
- change current directory. same as windows
- linux uses forward slashes when noting directories
## grep
- find text stin in file. find matches
```bash
grep "pattern" file.txt
```
## sudo
-  run command as a root user with elevated rights
- root can do anything
- su command chages shell to root user
- sudo
## shutdown
- shut system down. within 1 minite by default
- can specify number of minues or reboot
```bash
sudo shutdown -r 2
```
- will reboot machine after 2 minutes
- shutdown -c to cancel the shutdown proccess
## pwd vs passwd
-  pwd: print full working directory
- passwd: will change password for account. requires elevated privilages
## mv
- move file from one location to another
```bash
mv source.txt destination/SOURCE.txt
```
- offently used to rename files
## cp
- copies file to destination location or new name
## rm
- removes file or directories
- will not remove directories by default requires -r flag
```bash
rm -r /usr/bin
```
## mkdir
- creates a directory. create folder for file storage
## chmod
- can change modes and permissions for user, group and public permisions
```bash
chmod 744 script.sh
```
- will give - rwx r-- r-- permisions. full permisions for user. read only for other users
- tree digit number
- can use a-w sort of format with three leters
- can use u+x will enable execute permision for the user
## chown
- allows to change the file owner and group of file
## iwconfig/ifconfing
- iwconfig: allows one to view or change wireless networking configuraition
- essid, freq, channel, mode, rate
- requies knowledge of wireless network
- ifconfig: wier ethernet info
- slowly being migrated to the ip command
## apt-get:
- debian and debian based distros advaanced packagin tool, default package manager
- allows to install and manage applications that are installed to a computer
- install, update, remove.
## ps
- view the corrent proccesses thaty are running and PID
- ps -r | more. will list are proccesses with more pagin
## vi
- terminal based text editor. visual mode editor
- full screen with copy past and full features
- press i to begging typing
- esc to finish and ":wq" to write to file and exit
## dd
- convert and convert a file
- dd if=source_file_name of=target_file_name [OPTIONS]
- can create fdisk image. will output to img file format
- can restore from image
## closing programs
- killall: will kill instances of certain program
- xkill: kill thing with gui
- kill using PID

