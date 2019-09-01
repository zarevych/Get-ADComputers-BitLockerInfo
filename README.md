# Get-ADComputers-BitLockerInfo.ps1

DESCRIPTION
Get BitLocker Recovery Information from Active Directory.
Generates a CSV file with computer names and BitLocker Recovery Keys:
ComputerName;OperatingSystem;Date;Time;GMT;PasswordID;RecoveryPassword;DistinguishedName
 
Requirement of the script:
 - Active Directory PowerShell Module
 - Needed rights to view AD BitLocker Recovery Info
 
 Usage:
  .\Get-ADComputers-BitLockerInfo.ps1
  or
  .\Get-ADComputers-BitLockerInfo.ps1 -OU "OU=Computers,OU=IT Department,DC=myDomain,DC=com"
