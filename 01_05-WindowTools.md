# Windows Administrative Tools

### Local Security Policy
- big companies have big policies
- managed via active directory. requires edu, pro and enterprise education
- different policies are managed by different 

### Peformance Monitor
- gathers long term statistics on peformace on the hard of the systme
- system load: cpu usage, disk usage, etc.
- sets alerts and automatecd actions
- can determine wahta metrics to watch

### Services
- background process, no user interaction, anti-virus and browsing
- useful to check when startup is having problems
- command line control- net start, net stop
- can be managed via the control panel
- different policies with services can be determined

### Task Scheduler
- Schedule application opening or batch file of commands to run
- plan for the future, backups, shutdown
- includes useful predefined schedule
- managed with folders
- allows for easy definition of scripts and applications

### Component Services
- microsoft COM+, compoenent object model
- allows for creation of object oriented distributed application for enterprise
- manage COM+ apps, event viewe

### ODBC Data Sources
- open database connectivity
- allows for developer can write applicationi that writes to database with no regard for underlying databse technolgy, very flexible
- application independeance, database and Os does not matter
- can be configured with Control Panel and Administrative tools
- can be set ot excel spreadsheet, SQL or paradox driver

### Print Management
- control panel
- allows for sharing of printers. add and manage printer drivers
- view and manage the printers, print servers

### Memory Diagnostics
- is the memory working?
- can be notified automatically. allows for multiple passes
- checking the memory modules, on next start or restarts the the machine to begin the utility

### Event viewer
- central event consolidation, 
- catagories application, security, setup, system
- levels warning, error, critical, succesful audit and failure audit
- also shows the statistics of the events that can be seen
-

# Windows Firewall and Advanced Security
Window includes firewall that protects the system
- stateful firewall: understand and remembers state of traffic that goes outbound and inbound
- block unknown traffic automatically

### Window Defender(Firewall)
- intergrated into operating syste,
- configuration in control panel and windows firewall
### allowed apps
- declaration of fundamental firewall for certain applications
- rules based on applications, little detailed control
- disable or enable all traffic adn nothing else
- no scope all traffic, no connection security rules

### Advanced Secuirty features
- inbound rules
- outbound rules
- connection security rules
- granular controls: program, port, predefined services, custom rules, 
- custom rules: program, protocol/prot, scope, action and profile of the rules

# System Configuration

### System Configuration
- ms config: manage boot proccess, startup, services and other applications
- found in Control panel
### General Tab
- control startup, normal, diagnostics load basic services 
- selective startup where we define the services to start
### boot tab
- controls the boot location. multiple location and operating systems
- linux dual boot!
- advanced options, number of cores to use, maximun memory, 
- boot options 
- safe boot, remove gui, create lgo file, vase video, OS boot information, show drivers as they load, set timeout for booting
Services
- enable anddisable windows services
- easier to manage services than services applet
- useful fopr trial and error to find and fix the root of problems. coult take many reboots to find solution
### startup Tab
- manage which programs start with windows login
- multiple reboot to find problematic application
- most have moved to the task manager
- 
### tools tab

# Task Manager
- get realtime statistics on CPU, disk access, memory usage and others
- cntrl alt del and select task manager
- has more features from windows 7 onward
### applications tab
- list user interective applications, apps in desktop
- administer the applications in question
- now combined with processes tab in window s8
### processes
- view all running processes
interective and system tray apps
- view from all users
- manage the view, move columns, metrics,
- later version combine all apps, processes into a single tab
### Peformance
- what is happening, shows the full history from past
- statistical use
### Networking
- peformance, utilization, link speeds adn interface connection state
- view trends in system
### Users
- who is connected? what are they doing?
- user ,ist disconnect logoff and send message
- seperate processes, peformance statistis for the logged in users
# Disk Management
### utility
- manage disk operations, individial computers and file servers
- computer management, and storage
- **MIGHT ERASE DATA**
### Disk Status
- **healthy**: volume is working normaly. Drive letter, size, filesystem
- **healthy(at risk)**: drive is working normally but initial errors are beginning
- **initializing**: normal startup message
- **Failed**: cannot be started, disk is damanged or file system corrupted
- **Failed Redundancy**: Drive failer in RAID 1/5
- **Resynching**: mirrored volume is synching data between drives
- **Regenerating**: recreateing data from missing drive on parity drive
### Mounting drives
- Extend available storagr space, mount storage device as folder
- mount on empty folder, instant storage space
- mounting data on thing
### Storage Spaces
- storage for data centers and clound infrastracture
- multiple tiers
- storage pool: a group of storage drive, combine different storage devices into a single pool. easy add and remove space in the pool
- storage space: allocate virtual disks from the available space in the pool.
- allows for mirroing and parity. hot spare availity
# System Utilities
### The Run Line
- start an application by typing in the filename of the application
- we can run or search for app
### CMD
- command prompt
- start Utilities, from the command line
### Regedit
- windows registry
- large database used by windows and apps
- used by kernel, device drives, security account manager user interface and applications
- backup of registry is required for stability
- classes root, current user, local machine, users, current config
### Services.msc
- control panel, run line, 
- used for troubleshooting and operation of background services
- allows to see dependencies bewtween applications
### MMC
- microsoft management console
- used with snap ins and plugins for custom mana framework
- used for other tools
### MSTC: Microsoft Terminal Services Connection
- microsoft remote desktop connection
- common for headless servers with no screen or keyboard
### notepad
- view and edit text files, log files
- included in windows all version
### Explorer
- file explorer with GUI
- allows for management of remote files
### msinfo32
- view windows version
- hardware installed, components
- memory, DMA, IRQ's
- software enviroment, drivers, print jobs
### dxdiag
- directx diagnostic tool, manage directx isntallation
- multimedia API, 3d graphics, audio, input options
- generic graphics diagnostic tool
### Defrag
- disk defragmenntation, moves file fragments so that they are continous
- improves read and write item. 
- not require for solid state drives. graphical version in drive properties
- requires elevated permissions
- degrag C:
- will do analysis of drive before starting defrag
### System Restore
- create frequent restore points, go back in tome to correct problems
- F8, adavance boot options - repair
- takes system and reverts
- does not guarantee recovery from virus infection
### Windows update
- keep OS up to date, security patches, bug fixes
- automatic installation, or manual installation.
- download but wait for install
- check bot dont download
- allows for scheduling of restart
