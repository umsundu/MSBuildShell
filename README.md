# All Credit to:
* https://github.com/Cn33liz
* Casey Smith, Twitter: @subTee
  
# MSBuildShell
Slightly modified version of https://github.com/Cn33liz/MSBuildShell. MSBuildShell, a Powershell Host running within MSBuild.exe. 

## MSBuildShell, a Powershell Host running within MSBuild.exe
This code let's you Bypass Application Whitelisting and Powershell.exe restrictions and gives you a shell that almost looks and feels like a normal Powershell session (Get-Credential, PSSessions -> Works, Tab Completion -> Unfortunately not). It will also bypass the Antimalware Scan Interface (AMSI), which provides enhanced malware protection for Powershell scripts.

License: BSD 3-Clause

### Save This File And Execute The Following Command:

```
C:\Windows\Microsoft.NET\Framework\v4.0.30319\msbuild.exe C:\Scripts\MSBuildShell.csproj

Or

C:\Windows\Microsoft.NET\Framework64\v4.0.30319\msbuild.exe C:\Scripts\MSBuildShell.csproj
```

