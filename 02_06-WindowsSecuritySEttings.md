# Users and Groups
- administraot has super user. has access to all of operating system
- guest users have limited access
- standard user that have access to their section of file system and can do things
- groups: set of users that have shared permissions and settings. power users have more control than regular user
# NTFS vs share permission
- NTFS permission apply from local and network connections
- share permissions apply to connections over the network
- most restrictive permisssion when in conflict will win. deny beats allow
- permission are inherited from parent object
- shares allow for things to be viewed accross the network
- administrative share are created during installation
|   - systems files and folders
# explicit and inherited permissions
- explicit permissions, set default permissions for share
- inherited permisions: propagated from parent object to child object. set permission once, applies to everything underneeath
- manually set explicit permissions for certain objects
# User authentication
- prove that you are a valid account holder
- username/password. and additional credentials
- SSO/ Single Sign-on: windows doamin, provide credentials one time. manageed trough kerberos
# run as administrator
- admins have special rights and permissions
- windows does not automatically provide permissions
- runs as admin
# Bitlocker
- envrypt an entire volume
- cannot be used unless key is provided
- data is always protected withoutkey
- Bitlocker to Go: for encrypted USB flash drives
# EFS
- envrypting files system. encrypte specific folders
- 7, 8 and 10 pro and enterprise
- uses username and password to encrypt so, even someone with admin rights may not be able to see things
