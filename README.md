# Get-ADComputers-BitLockerInfo

Get BitLocker Recovery Information from Active Directory.
Generates a CSV file with computer names and BitLocker Recovery Keys.
 

## Requirement of the script


 - Active Directory PowerShell Module
 - Needed rights to view AD BitLocker Recovery Info
 


## Usage
```bash
.\Get-ADComputers-BitLockerInfo.ps1
```

  or

```bash
.\Get-ADComputers-BitLockerInfo.ps1 -OU "OU=Computers,OU=IT Department,DC=myDomain,DC=com"
```