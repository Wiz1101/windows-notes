# windows-notes
Some Notes for Windows


To see what users are in the Administrators group, you can use the command:

 ```powershell
 Get-LocalGroupMember -Group “Administrators”
 ```

To see what tasks are scheduled on this system run:
 ```powershell
  Get-ScheduledTask
```

How to see some user last logon:

```shell
net user [Username] | findstr “Last”
```

## Useful  Tools
1. Task Scheduler
2. Windows Firewall
3. 