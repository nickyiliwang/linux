# Linux
Every command here is tested on the Amazon Linux 2 AMI 

## Table of contents
1. Basics
- [FileSystem](1.basics/0.FileSystem.md)
- [Permission](1.basics/1.Permission.md)
- [Text Processor](1.basics/2.Text.md)
2. SysAdmin  
- [Editor and sed](2.sysadmin/0.File-Editors.md)
- [User Accounts](2.sysadmin/1.UserAccounts.md)
- [Account Authentication](2.sysadmin/2.AccountAuthentication.md)
3. Shell Scripting
- [Advanced Scripts](3.shell-scripting/1.if-statements.md)
4. Networking
- [Networking Basics](4.networking/0.network-basics.md)
- [NIC](4.networking/1.NIC.md)
- [Network Utilities](4.networking/2.NetworkUtilities.md)
- [Network Protocols](4.networking/3.FileTransferProtocols.md)
5. Disk Management
- [System Levels](5.disk-management/0.SystemLevel.md)
6. TroubleShooting
- [Troubleshooting](6.troubleshooting/0.basics.md)

## General commands
```
whoami = Shows current user
ll = shortcut to "ls -l"
:color in Vi or Vim changes color scheme ie. :color desert
 rpm -qa | grep <package> = check if a package exist in the AMI
```

## Help commands
```
1. whatis <command>
2. <command> --help 
3. man <command>
```

## Packages
sudo yum -y install telnet
sudo yum -y install finger (user tracing pkg)

## Virtualization
1. Hypervisor = Host / Virtual Server software
2. 