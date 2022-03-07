# Linux
Every command here is tested on the Amazon Linux 2 AMI 

## Table of contents
1. Basics
- [Basics](1.basics/0.Basics.md)
- [Misc(MOTD, mail)](1.basics/0.1.Misc.md)
- [FileSystem](1.basics/0.FileSystem.md)
- [Permission](1.basics/1.Permission.md)
- [Text Processor](1.basics/2.Text.md)
- [Package management](1.basics/3.PkgManagement.md)
- [OS Performance](1.basics/4.Performance.md)
- [System Backup](1.basics/5.SysBackup.md)
2. SysAdmin
- [System Basics](2.sysadmin/0.SysBasics.md)
- [System Control](2.sysadmin/1.0.SysControl.md)
- [System Monitoring](2.sysadmin/1.1.SysMonitoring.md)
- [Log Monitoring](2.sysadmin/1.2.SysLogMonitoring.md)
- [Task Scheduling](2.sysadmin/2.TaskSchedule.md)
- [User Accounts](2.sysadmin/3.UserAccounts.md)
- [Account Authentication](2.sysadmin/4.AccountAuthentication.md)
3. Shell Scripting
- [Scripting Basics](3.shell-scripting/0.ShellBasics.md)
- [Advanced Scripts](3.shell-scripting/1.advanced-scripting.md)
4. Networking
- [Networking Basics](4.networking/0.NetBasics.md)
- [Network Security](4.networking/0.1.NetSecurity.md)
- [Network Interface Card](4.networking/1.NIC.md)
- [Network Utility](4.networking/2.NetUtilities.md)
- [File Transfer Protocols](4.networking/3.FileTransferProtocols.md)
- [Domain Name System](4.networking/4.DNS.md)
- [Network Time Protocol](4.networking/4.NTP.md)
5. Disk Management
- [System Levels](5.disk-management/0.SystemLevel.md)
- [Storage](5.disk-management/1.Storage.md)
- [Network File System](5.disk-management/1.1.NFS.md)
- [Logical Volume Management](5.disk-management/2.LVM.md)
- [Memory](5.disk-management/3.Memory.md)
6. TroubleShooting
- [Unreachable EC2 Web Server](6.troubleshooting/0.EC2WebServer.md)

## General commands
```
ll = shortcut to "ls -l"
:color in Vi or Vim changes color scheme ie. :color desert
 rpm -qa | grep <package> = check if a package exist in the AMI
```
## Help commands
```
1. whatis [command]
2. man [command]
3. [command] --help 
```
## Packages installed
- telnet
- finger (user tracing pkg)
- firewalld (OS level firewall, don't forget this exist and spend 1 hour "troubleshooting" lol )
- ntp (network time protocol pkg)
- tuned (system performance tuning)
- bind/bind-utils (DNS)

