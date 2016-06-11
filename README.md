# CMD-Tips
Some tips for command line fixes.

## Reset your TCP/IP stack
```cmd
netsh int tcp reset
```

[Source MSDN](https://support.microsoft.com/en-us/kb/299357)
## Open control panel from the command line
```cmd
control
```
## Open the advanced user config
Usage Example: 
- Allows you to not enter a password in order to login to your computer.

```cmd
control userpasswords2
```
## Resetting the group policy database
```cmd
esentutl /p %windir%\security\Database\secedit.sdb
```
