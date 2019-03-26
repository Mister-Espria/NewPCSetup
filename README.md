# NewPCSetup
List of programs and tutorials

## Add “Run with PowerShell (Admin)” Context Menu for .PS1 Files
https://www.top-password.com/blog/add-run-with-powershell-admin-context-menu-for-ps1-files/

## Install Chocolatey
Run this in an Powershell (Admin)
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Chocolatey apps install script
```
# Install Applications

choco install GoogleChrome
choco install putty
choco install ccleaner
choco install spotify

# Install Utilities

choco install windirstat 

```
