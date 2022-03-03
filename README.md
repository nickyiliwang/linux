# Linux
Every command here is tested on the Amazon Linux 2 AMI 

## Table of contents
1. Basics
- [Basics](1.basics/0.Basics.md)
- [FileSystem](1.basics/0.FileSystem.md)
- [Permission](1.basics/1.Permission.md)
- [Text Processor](1.basics/2.Text.md)
1. SysAdmin  
- [Basic Admin CMD](2.sysadmin/0.SysBasics.md)
- [System Control](2.sysadmin/1.0.SysControl.md)
- [System Monitoring](2.sysadmin/1.1.SysMonitoring.md)
- [Log Monitoring](2.sysadmin/1.2.SysLogMonitoring.md)
- [Task Scheduling](2.sysadmin/2.TaskSchedule.md)
- [User Accounts](2.sysadmin/3.UserAccounts.md)
- [Account Authentication](2.sysadmin/4.AccountAuthentication.md)
1. Shell Scripting
- [Advanced Scripts](3.shell-scripting/1.if-statements.md)
4. Networking
- [Networking Basics](4.networking/0.network-basics.md)
- [NIC](4.networking/1.NIC.md)
- [Network Utility CMD](4.networking/2.NetworkUtilities.md)
- [Network Protocols](4.networking/3.FileTransferProtocols.md)
5. Disk Management
- [System Levels](5.disk-management/0.SystemLevel.md)
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
1. whatis <command>
2. man <command> 
3. <command> --help 
```
## Packages installed
sudo yum -y install telnet
sudo yum -y install finger (user tracing pkg)
sudo yum -y install firewalld (OS level firewall, don't forget this exist and spend 1 hour "troubleshooting" lol )

## Virtualization
1. Hypervisor = Host / Virtual Server software
2. 