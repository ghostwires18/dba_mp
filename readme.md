## Project : DBA Postgresql14.x
## ghostwires18 (Arry Hutomo) -MegaPerintis DataScience

#### Backend for Docker Engine
##### Enabled WSL dengan cara: di PowerShell 
##### Windows Subsystem for Linux menggunakan wsl dengan menggunakan PowerShell yang di jalankan dengan "Administration Permission"

     C:\Windows\system32> dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
#####
     C:\Windows\system32> dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
#####     
     C:\Windows\system32> wsl --set-default-version 2
     
##### For information on key differences with WSL 2 please visit https://aka.ms/wsl2
##### RESTART

      C:\Windows\system32> wsl -l
      
Windows Subsystem for Linux has no installed distributions.
Distributions can be installed by visiting the Microsoft Store:
https://aka.ms/wslstore


##### search coding script install docker (link:ghostwires18-ArryHutomoSources) 
      https://youtube.dimas-maryanto.com/posts/devops/docker/02a-install-on-windows10-wls
